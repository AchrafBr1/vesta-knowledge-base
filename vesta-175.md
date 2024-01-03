# VESTA 175

**PRS5-ZBS(R)/PRM5-ZBS(R)**

**Power Relay Switch Series**

**Introduction**

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

![](<.gitbook/assets/0 (66).jpeg>)

| **Model No.**     | **Meter** | **ZigBee Router** | **OTA** |
| ----------------- | --------- | ----------------- | ------- |
|                   |           |                   |         |
| **PRS5-ZBS**      | **No**    | **No**            | **No**  |
|                   |           |                   |         |
| **PRS5-ZBS-OTA**  | **No**    | **No**            | **Yes** |
|                   |           |                   |         |
| **PRS5-ZBSR**     | **No**    | **Yes**           | **No**  |
|                   |           |                   |         |
| **PRS5-ZBSR-OTA** | **No**    | **Yes**           | **Yes** |
|                   |           |                   |         |
| **PRM5-ZBS**      | **Yes**   | **No**            | **No**  |
|                   |           |                   |         |
| **PRM5-ZBS-OTA**  | **Yes**   | **No**            | **Yes** |
|                   |           |                   |         |
| **PRM5-ZBSR**     | **Yes**   | **Yes**           | **No**  |
|                   |           |                   |         |
| **PRM5-ZBSR-OTA** | **Yes**   | **Yes**           | **Yes** |
|                   |           |                   |         |

**Parts Identification**

**1. LED indicator**

The LED indicator is used to indicate Power Relay Switch status:

*
  * On:

The Power Relay Switch is turned on.

*
  * Off:

The Power Relay Switch is turned off.

*
  * Flashes twice:

The Power Relay Switch has successfully joined a ZigBee network.

*
  * Flashes 5 times

The Power Relay Switch has successfully bound with a controller

*
  * Flashes every 20 minutes

The Power Relay Switch has lost connection to its current ZigBee network

1. **Function Button**

**Function Button Usage:**

*
  * Press the button to toggle on/off the Power Relay Switch
  * Press and hold the button for 10 seconds then release to reset the Power Relay Switch.
  * Press and hold the button for 3 seconds then release to bind with a controller

1. **External Switch connection cable 1**

1

1. **External Switch connection cable 2**
2. **AC Line Power Load Output**
3. **AC Neural Power Input/AC Neutral Power Load Output**
4. **AC Line Power Input**

**ZigBee Network Setup**

* _**ZigBee Device Guideline**_

ZigBee is a wireless communication protocol that is reliable, has low power consumption and has high transmission efficiency. Based on the IEEE802.15.4 standard, ZigBee allows a large amount of devices to be included in a network and are coordinated for data exchange and signal transmission.

Due to the fundamental structure of ZigBee network, ZigBee device will actively seek and join network after powering on.

* _**Joining the ZigBee Network**_

As a ZigBee device, the Power Relay Switch needs to join a ZigBee network to receive commands and transmit energy consumption information. Please follow the steps bellow to join the Power Relay Switch into a ZigBee network.

*
  1. Connect the Power Relay Switch to power cable.
  2. Press and hold the Function button for 10 seconds, then release it to join the network. Please make sure the permit-to-join feature on the router or coordinator of your ZigBee network is enabled.
  3. If the Power Relay Switch successfully joins a ZigBee network, the LED Indicator will flash twice to confirm.
  4. After joining the ZigBee network, the Power Relay Switch will be registered in the network automatically. Please check the Zigbee network coordinator, system control panel or CIE (Control and Indicating Equipment) to confirm if joining and registration is successful.
  5. If registration and joining to the network is unsuccessful, please check your ZigBee network coordinator, system control panel or CIE setting to ensure the permit-to-join function is available, and then use the Factory Reset function below to join the ZigBee network.
* _**Binding with Controller**_

After joining the ZigBee network, the Power Relay Switch can bind itself with a controller device which can be used to adjust the Power Relay Switch’s power output level. To bind the Power Relay Switch and the device:

*
  1. Press and hold the Function Button for 3 seconds, then release the button. The Power Relay Switch will send binding request to the coordinator.
  2. Refer to your controller manual to send binding request for the device within 16 seconds.
  3. If binding is successful, the Power Relay Switch LED indicator will flash 5 times to confirm. You can now use the controller to adjust power output level for the Power Relay Switch.
  4. If binding is unsuccessful, please retry the binding process.
* _**Removing Device from ZigBee Network (Factory Reset)**_

To remove the Power Switch from current ZigBee network, the Power Switch must be put to Factory Reset to complete device removal. Factory Reset function will clear the Power Switch of its stored setting and information and prompt the Power Switch to search for new ZigBee network.

**Before removing device, make sure the Power Switch is within current ZigBee network signal range**

*
  1. Press and hold the function button for 10 seconds, then release the button to reset Power Switch.
  2. Upon reset, the Power Switch will clear current ZigBee network setting and transmit signal to ZigBee coordinator to remove itself from current ZigBee network. It will then actively search for available ZigBee network again and join the network automatically.
* _**ZigBee Router Device Capacity (PRS5-ZBSR/PRM5-ZBSR Only)**_

The Power Switch models with Router function allow other ZigBee devices to join the ZigBee Network through the Router. The Power Switch Router has maximum capacity of 40 devices, including 10 routers; the Power Switch Meter Router has maximum capacity of 10 devices including 5 routers.

| **Model No.**         | **Maximum ZigBee Device** | **Maximum ZigBee** |   |
| --------------------- | ------------------------- | ------------------ | - |
| **+ Router Capacity** | **Router Capacity**       |                    |   |
|                       |                           |                    |   |
|                       |                           |                    |   |
| **PRS5-ZBSR**         | **40**                    | **10**             |   |
|                       |                           |                    |   |
| **PRM5-ZBSR**         | **10**                    | **5**              |   |
|                       |                           |                    |   |

* _**OTA Firmware Upgrade (For OTA version only)**_

The Power Relay Switch supports OTA firmware upgrade feature via ZigBee network, which can be initiated from the ZigBee network coordinator. Follow steps below to perform OTA firmware upgrade.

2

**Step 1.** You have to access your ZigBee Coordinator to perform the firmware upgrade on the air. **Step 2.** On the configuration webpage, select the device that you wish to upgrade and select the new

ZigBee firmware provided. Please refer to ZigBee Coordinator User Manual for details.

**Step 3.**Press“OK”to start upgrading process, and the LED will keep flashing. During the OTA process,

please do not perform any other actions, or power down the panel.

**Step 4.**The length of an upgrade will take approximately 20 to 30 minutes. Please note that the duration may vary based on file size or distance between your accessory and coordinator.

**Step 5.**Wait for firmware to complete update. When the progress reaches 100%, the Device will reset automatically. You can also refresh the webpage again to ensure that the Device firmware is successfully updated with the newest version displayed.

**Caution**

* All works on the device, including installation and maintenance, must be performed by a qualified and licensed electrician.
* Before installation or any maintenance work, make sure the power supply has been disconnected.
* Do not connect the device to loads exceeding supported load current.

**Installation**

* _**Wiring with Splicing Connector**_
  * The Power Relay Switch comes with embedded cable for connecting to AC power, appliance, and external switch. Five Wago 221 Splicing Connectors are provided for connection.
  * The 2-wire/3-wire connectors accommodate solid and stranded wires from 0.2 to 4 mm² (24–12 AWG).
  * Before wiring, please make sure the power is off. To connect the wires:
    1. Lift the lever and insert the brown wire. **(Picture 1, 2)**

![](<.gitbook/assets/1 (55).png>)

**Picture1** **Picture 2**

1. Push the lever back down. The transparent housing allows you to check if the wire is connected properly. Make sure the wire is held in place tightly and won't come off. **(Picture 3, 4)**

![](<.gitbook/assets/2 (60).png>)

|                                               | **Picture 3**                           | **Picture 4** |   |
| --------------------------------------------- | --------------------------------------- | ------------- | - |
| 3) In the same way as step 1 & 2, insert into | another pole the wire for connecting to |               |   |
| AC Line Power Input. **(Picture 5)**          |                                         |               |   |
|                                               |                                         |               |   |
|                                               |                                         |               |   |

![](<.gitbook/assets/3 (48).jpeg>)

**Picture 5**

3

1. Repeat step 1 & 2 & 3 to connect the other wires with connectors.

Please be noted that the blue wire must be connected to a 3-wire connector and then connected to AC Neural Power Input and AC Neutral Power Load Output. **(Picture 6)**

![](<.gitbook/assets/4 (61).png>)

**Picture 6**

**Operation**

* _**Wire Connection Diagram**_
  * Refer to the diagram to connect your home lighting to the Power Relay Switch.
* _**Installation**_
  * Connect the Power Relay Switch to power cable.
  * Connect the Power Relay Switch to your home lighting. The lighting must be in ON status.
  * You can connect an external switch to the Power Relay Switch according to the diagram to turn on/off the Power Relay Switch
  * _**IMPORTANT NOTE**_**:** The Power Relay Switch does not have a backup battery and will be powered down when AC power fails. **DO NOT** use the Power Relay Switch as router for your security sensor or alarm control devices such as Door Contact, PIR Sensor…etc., otherwise the sensors will lose connection to ZigBee network if the Power Relay Switch is disconnected from AC power. Plan the installation locations of these security sensors without using the Power Relay Switch and only use a router with backup battery for them. The router function of the Power Switch should **ONLY** be used to provide signal range extension for other Power Switches/Dimmer.
* _**Appliance Control**_
  * After the Power Relay Switch has successfully joined a ZigBee network, the coordinator can remotely turn on/off the Appliance.
  * You can also press the button on the Power Relay Switch to toggle on/off the light.
  * You can turn on/off the Power Relay Switch with an external switch.
  * If you have bound a controller with the Power Relay Switch, you can also use the controller to turn on/off the Power Relay Switch.
  * If the AC Power input is disconnected from the Power Relay Switch, its previous on/off status will be restored within 1 minute after reconnecting the AC Power input to the Power Relay Switch.
* _**Energy Consumption Monitor (PRM5-ZBS/PRM5-ZBSR Only)**_
  * The Power Relay Switch will transmit a signal with its power consumption data every two minutes to the ZigBee network coordinator.
  * Whenever the Power Switch energy output changes by +/- 2W, it will automatically transmit a signal with power consumption data to the ZigBee network coordinator for update.
  * The Power Switch transmits a signal with power data to coordinator whenever accumulated power usage increases by 0.1kW/hr.
  * The Meter has an accuracy of +/- 5%.
  * To clear the Power Switch of its accumulated power consumption data, follow steps below:
    1. Disconnect the Power Relay Switch from power outlet.
    2. Press and hold the function button and reconnect power when holding down the button.
    3. Keep holding the button and release after 3 seconds. The accumulated power consumption data will be cleared.

![](<.gitbook/assets/5 (30).jpeg>)

4

* _**Maximum Operation Load**_
  * For 110V: the maximum operation load is 1100W and 10A.
  * For 230V: the maximum operation load is 2300W and 10A.
  * If the Power Relay Switch is overheating, it will cut off power automatically as a safety measure. The user must disconnect and reconnect AC power to the Power Relay Switch after cut off to resume normal operation.

**Appendix (For developers only)**

_**Power Relay Switch with Meter Cluster ID**_

**Device ID: Mains Power Outlet :0x0009**

**Endpoint:0x01**

| **Server Side**                             |               | **Client Side** |
| ------------------------------------------- | ------------- | --------------- |
|                                             |               |                 |
|                                             | **Mandatory** |                 |
|                                             |               |                 |
| Basic (0x0000)                              |               | _None_          |
|                                             |               |                 |
| Identify(0x0003)                            |               |                 |
|                                             |               |                 |
| Groups(0x0004)                              |               |                 |
|                                             |               |                 |
| Scenes(0x0005)                              |               |                 |
|                                             |               |                 |
| On/Off(0x0006)                              |               |                 |
|                                             |               |                 |
|                                             | **Optional**  |                 |
|                                             |               |                 |
| Metering (0x0705) (PRM5-ZBS/PRM5-ZBSR only) |               | None            |
|                                             |               |                 |

 _**Attribute of Basic Cluster Information**_

| **Identifier**                                       | **Name**              |                  | **Type**        |          |               | **Range**      |                 |              | **Access**   |        | **Default** | **Mandatory** |               |               |   |   |
| ---------------------------------------------------- | --------------------- | ---------------- | --------------- | -------- | ------------- | -------------- | --------------- | ------------ | ------------ | ------ | ----------- | ------------- | ------------- | ------------- | - | - |
|                                                      |                       |                  |                 |          |               | **/ Optional** |                 |              |              |        |             |               |               |               |   |   |
|                                                      |                       |                  |                 |          |               |                |                 |              |              |        |             |               |               |               |   |   |
| 0x0000                                               | _ZCLVersion_          | Unsigned 8-bit   |                 |          | 0x00 –0xff    |                |                 | Read only    |              | 0x01   | M           |               |               |               |   |   |
|                                                      | integer               |                  |                 |          |               |                |                 |              |              |        |             |               |               |               |   |   |
|                                                      |                       |                  |                 |          |               |                |                 |              |              |        |             |               |               |               |   |   |
| 0x0001                                               | ApplicationVersion    | Unsigned 8-bit   |                 |          | 0x00 – 0xff   |                |                 | Read only    |              | 0x00   | O           |               |               |               |   |   |
|                                                      | integer               |                  |                 |          |               |                |                 |              |              |        |             |               |               |               |   |   |
|                                                      |                       |                  |                 |          |               |                |                 |              |              |        |             |               |               |               |   |   |
| 0x0003                                               | _HWVersion_           | Unsigned 8-bit   |                 |          | 0x00 –0xff    |                |                 | Read only    | 0            | O      |             |               |               |               |   |   |
|                                                      | integer               |                  |                 |          |               |                |                 |              |              |        |             |               |               |               |   |   |
|                                                      |                       |                  |                 |          |               |                |                 |              |              |        |             |               |               |               |   |   |
| 0x0004                                               | _ManufacturerName_    | Character String |                 |          | 0 – 32 bytes  |                |                 | Read only    |              | Climax | O           |               |               |               |   |   |
|                                                      |                       |                  |                 |          | Technology    |                |                 |              |              |        |             |               |               |               |   |   |
|                                                      |                       |                  |                 |          |               |                |                 |              |              |        |             |               |               |               |   |   |
| 0x0005                                               | _ModelIdentifier_     | Character String |                 |          | 0 – 32 bytes  |                |                 | Read only    |              | (Model | O           |               |               |               |   |   |
|                                                      |                       |                  |                 |          | Version)      |                |                 |              |              |        |             |               |               |               |   |   |
|                                                      |                       |                  |                 |          |               |                |                 |              |              |        |             |               |               |               |   |   |
| 0x0006                                               | _DateCode_            | Character String |                 |          | 0 – 16 bytes  |                |                 | Read only    |              |        | O           |               |               |               |   |   |
|                                                      |                       |                  |                 |          |               |                |                 |              |              |        |             |               |               |               |   |   |
| 0x0007                                               | _PowerSource_         |                  | 8-bit           |          |               | 0x00 –0xff     |                 |              | Read only    |        |             | M             |               |               |   |   |
| 0x0010                                               | _LocationDescription_ | Character String |                 |          | 0 – 32 bytes  |                |                 | Read / Write |              |        | O           |               |               |               |   |   |
| 0x0011                                               | _PhysicalEnvironment_ |                  | 8-bit           |          |               | 0x00 –0xff     |                 |              | Read / Write |        | 0x00        | O             |               |               |   |   |
| 0x0012                                               | _DeviceEnabled_       |                  | Boolean         |          |               | 0x00 –0x01     |                 |              | Read / Write |        | 0x01        | O             |               |               |   |   |
| 0xFFFD                                               | _ClusterRevision_     |                  | uint16          |          | 0x0001-0xFFFE |                |                 | Read only    | 1            | M      |             |               |               |               |   |   |
|  _**Attribute of Identify Cluster Information**_    |                       |                  |                 |          |               |                |                 |              |              |        |             |               |               |               |   |   |
|                                                      |                       |                  |                 |          |               |                |                 |              |              |        |             |               |               |               |   |   |
| **Identifier**                                       | **Name**              |                  |                 | **Type** |               |                | **Range**       | **Access**   |              |        | **Default** | **Mandatory** |               |               |   |   |
|                                                      |                       |                  |                 |          |               | **/ Optional** |                 |              |              |        |             |               |               |               |   |   |
|                                                      |                       |                  |                 |          |               |                |                 |              |              |        |             |               |               |               |   |   |
| 0x0000                                               | _IdentifyTime_        |                  | Unsigned 16-bit |          |               | 0x00 –0xffff   | Read / Write    |              | 0x0000       | M      |             |               |               |               |   |   |
|                                                      |                       | integer          |                 |          |               |                |                 |              |              |        |             |               |               |               |   |   |
|                                                      |                       |                  |                 |          |               |                |                 |              |              |        |             |               |               |               |   |   |
| 0xFFFD                                               | _ClusterRevision_     |                  |                 | uint16   |               |                | 0x0001-0xFFFE   | Read only    |              | 1      | M           |               |               |               |   |   |
|  _**Attributes of the Groups cluster Information**_ |                       |                  |                 |          |               |                |                 |              |              |        |             |               |               |               |   |   |
|                                                      |                       |                  |                 |          |               |                |                 |              |              |        |             |               |               |               |   |   |
| **Identifier**                                       | **Name**              |                  | **Type**        |          |               | **Range**      |                 | **Access**   |              |        |             | **Default**   | **Mandatory** |               |   |   |
|                                                      |                       |                  |                 |          |               | **/ Optional** |                 |              |              |        |             |               |               |               |   |   |
|                                                      |                       |                  |                 |          |               |                |                 |              |              |        |             |               |               |               |   |   |
| 0x0000                                               | _NameSupport_         |                  | 8-bit bitmap    |          |               | x0000000       |                 | Read only    |              | -      | M           |               |               |               |   |   |
| 0xFFFD                                               | _ClusterRevision_     |                  | uint16          |          |               | 0x0001-0xFFFE  |                 | Read         |              | 1      | M           |               |               |               |   |   |
|                                                      |                       |                  |                 | only     |               |                |                 |              |              |        |             |               |               |               |   |   |
|                                                      |                       |                  |                 |          |               |                |                 |              |              |        |             |               |               |               |   |   |
|  _**Attributes of the Scenes cluster Information**_ |                       |                  |                 |          |               |                |                 |              |              |        |             |               |               |               |   |   |
|                                                      |                       |                  |                 |          |               |                |                 |              |              |        |             |               |               |               |   |   |
| **Identifier**                                       | **Name**              |                  |                 | **Type** |               |                | **Range**       |              | **Access**   |        |             |               | **Default**   | **Mandatory** |   |   |
|                                                      |                       |                  |                 |          |               |                | **/ Optional**  |              |              |        |             |               |               |               |   |   |
|                                                      |                       |                  |                 |          |               |                |                 |              |              |        |             |               |               |               |   |   |
| 0x0000                                               | _NameSupport_         |                  | 8-bit bitmap    |          |               | x0000000       |                 | Read only    |              |        | 0x00        | M             |               |               |   |   |
| 0x0001                                               | _CurrentScene_        |                  | Unsigned 8-bit  |          |               | 0x00 – 0xff    |                 | Read only    |              |        |             | 0x00          | M             |               |   |   |
|                                                      |                       | integer          |                 |          |               |                |                 |              |              |        |             |               |               |               |   |   |
|                                                      |                       |                  |                 |          |               |                |                 |              |              |        |             |               |               |               |   |   |
| 0x0002                                               | _CurrentGroup_        |                  |                 | Unsigned |               |                | 0x0000 – 0xfff7 |              | Read only    |        |             |               | 0x00          | M             |   |   |
|                                                      | 16-bit integer        |                  |                 |          |               |                |                 |              |              |        |             |               |               |               |   |   |
|                                                      |                       |                  |                 |          |               |                |                 |              |              |        |             |               |               |               |   |   |
| 0x0003                                               | _SceneValid_          |                  |                 | Boolean  |               |                | 0x00 – 0x01     |              | Read only    |        |             | 0x00          | M             |               |   |   |
| 0x0004                                               | _NameSupport_         |                  | 8-bit bitmap    |          |               | x0000000       |                 | Read only    |              | -      | M           |               |               |               |   |   |
| 0xFFFD                                               | _ClusterRevision_     |                  |                 | uint16   |               |                | 0x0001-0xFFFE   |              | Read         |        | 1           | M             |               |               |   |   |
|                                                      |                       |                  |                 |          | only          |                |                 |              |              |        |             |               |               |               |   |   |
|                                                      |                       |                  |                 |          |               |                |                 |              |              |        |             |               |               |               |   |   |

5

* _**Attribute of On/Off Cluster Information**_

| **Identifier** | **Name**          | **Type** | **Range**     | **Access** | **Default** | **Mandatory** |   |
| -------------- | ----------------- | -------- | ------------- | ---------- | ----------- | ------------- | - |
| **/ Optional** |                   |          |               |            |             |               |   |
|                |                   |          |               |            |             |               |   |
| 0x0000         | _OnOff_           | Boolean  | 0x00 –0x01    | Read only  | 0x00        | M             |   |
| 0xFFFD         | _ClusterRevision_ | uint16   | 0x0001-0xFFFE | Read       | 1           | M             |   |
| only           |                   |          |               |            |             |               |   |
|                |                   |          |               |            |             |               |   |

 _**Attributes of the Metering cluster Information (Reading Information Attribute Set)**_

| **Identifier** | **Name**         | **Type**        | **Range**      |    | **Access** | **Defaul** | **Mandatory** |   |
| -------------- | ---------------- | --------------- | -------------- | -- | ---------- | ---------- | ------------- | - |
|                | **t**            | **/ Optional**  |                |    |            |            |               |   |
|                |                  |                 |                |    |            |            |               |   |
| 0x00           | CurrentSummation | Unsigned 48-bit | 0x000000000000 | to | Read Only  |            | M             |   |
| Delivered      | Integer          | 0xFFFFFFFFFFFF  |                |    |            |            |               |   |
|                |                  |                 |                |    |            |            |               |   |

 _**Attributes of the Metering cluster Information (Formatting Attribute Set)**_

| **Identifier** | **Name**           | **Type**          | **Range**    | **Access** | **Default** | **Mandatory** |   |
| -------------- | ------------------ | ----------------- | ------------ | ---------- | ----------- | ------------- | - |
| **/ Optional** |                    |                   |              |            |             |               |   |
|                |                    |                   |              |            |             |               |   |
| 0x00           | UnitofMeasure      | 8-bit Enumeration | 0x00 to 0xFF | Read Only  | 0x00        | M             |   |
| 0x01           | Multiplier         | Unsigned 24-bit   | 0x000000 to  | Read Only  | 1           | O             |   |
| Integer        | 0xFFFFFF           |                   |              |            |             |               |   |
|                |                    |                   |              |            |             |               |   |
| 0x02           | Divisor            | Unsigned 24-bit   | 0x000000 to  | Read Only  | 10000       | O             |   |
| Integer        | 0xFFFFFF           |                   |              |            |             |               |   |
|                |                    |                   |              |            |             |               |   |
| 0x03           | SummationFormating | 8-bit BitMap      | 0x00 to 0xFF | Read Only  | 0xF9        | M             |   |
| 0x04           | DemandFormating    | 8-bit BitMap      | 0x00 to 0xFF | Read Only  | 0x93        | O             |   |
| 0x06           | MeteringDeviceType | 8-bit BitMap      | 0x00 to 0xFF | Read Only  | 0x00        | M             |   |

 _**Attributes of the Metering cluster Information (Historical Attribute Set)**_

| **Identifier** | **Name**            | **Type**      | **Range**     | **Access** | **Default** | **Mandatory** |   |
| -------------- | ------------------- | ------------- | ------------- | ---------- | ----------- | ------------- | - |
| **/ Optional** |                     |               |               |            |             |               |   |
|                |                     |               |               |            |             |               |   |
| 0x00           | InstantaneousDemand | Signed 24-bit | -8,388,607 to | Read Only  | 0x00        | O             |   |
| Integer        | 8,388,607           |               |               |            |             |               |   |
|                |                     |               |               |            |             |               |   |
| 0xFFFD         | _ClusterRevision_   | uint16        | 0x0001-0xFFF  | Read       | 1           | M             |   |
| E              | only                |               |               |            |             |               |   |
|                |                     |               |               |            |             |               |   |

6
