# VESTA-186

## **PSS-29ZBS(R) / PSM-29ZBS(R) Power Switch Series**

## **Introduction**

The Power Switch series include the following models:

**PSS-29ZBS:** ZigBee Power Switch

**PSS-29ZBSR:** ZigBee Power Switch with Router function

**PSM-29ZBS:** ZigBee Power Switch with Meter

**PSM-29ZBSR:** ZigBee Power Switch with Meter and Router function

The Power Switches are capable of receiving wireless signals from the coordinator in the ZigBee network to toggle On/Off of appliances that are attached to it.

The Power Switch utilizes ZigBee technology for wireless signal transmission. ZigBee is a wireless communication protocol that is reliable, has low power consumption and has high transmission efficiency. Based on the IEEE802.15.4 standard, ZigBee allows a large amount of devices to be included in a network and coordinated for data exchange and signal transmission.

Models with Meter functions (PSM-29ZBS / PSM-29ZBSR) have the extra feature of keeping tracks of energy consumption with built-in power meter and transmit the data to coordinator regularly.

Models with router function (PSS-29ZBSR / PSM-29ZBSR) also serve as a router in the ZigBee network. After being included in the ZigBee network, it allows other ZigBee device to join the network through the Power Switch.

| **Model No.**  | **Meter** | **ZigBee Router** |
| -------------- | --------- | ----------------- |
|                |           |                   |
| **PSS-29ZBS**  | **No**    | **No**            |
|                |           |                   |
| **PSS-29ZBSR** | **No**    | **Yes**           |
|                |           |                   |
| **PSM-29ZBS**  | **Yes**   | **No**            |
|                |           |                   |
| **PSM-29ZBSR** | **Yes**   | **Yes**           |
|                |           |                   |

## **Parts Identification**

1. **Function Button aka LED indicator**

The Function Button also doubles as the LED Indicator. The function button is used to control the Power Switch. The LED indicator is used to indicate Power Switch status.

**LED Indication:**

The LED indicator lights up in the following conditions:

* On:

The Power Switch is turned on.

* Off:

The Power Switch is turned off.

* Flashes twice:

The Power Switch has successfully joined a ZigBee network.

* Flashes 5 times

The Power Switch has successfully bound with a controller

* Flashes every 20 minutes

The Power Switch has lost connection to its current ZigBee network

(**PSS-29ZBS and PSM-29ZBS only**)

**Function Button Usage:**

* Press the button to toggle on/off the Power Switch
* Press and hold the button for 10 seconds then release to reset the Power Switch.
* Press and hold the button for 3 seconds then release to bind with a controller.

_**Type F**_ _**Type B**_

![](<.gitbook/assets/0 (83).jpeg>)

_**Type L**_ _**Type J**_

1

**ZigBee Network Setup**

![](<.gitbook/assets/1 (77).jpeg>)

* _**ZigBee Device Guideline**_

ZigBee is a wireless communication protocol that is reliable, has low power consumption and has high transmission efficiency. Based on the IEEE802.15.4 standard, ZigBee allows a large amount of devices to be included in a network and are coordinated for data exchange and signal transmission.

![](<.gitbook/assets/2 (64).jpeg>)

* _**Joining the ZigBee Network**_

As a ZigBee device, the Power Switch needs to join a ZigBee network to receive commands and transmit energy consumption information. Follow the steps bellow to join the Power Switch into a ZigBee network.

*
  1. Plug in the Power Switch into a power outlet.
  2. Press and hold the function button for 10 seconds as the Power Switch resets and starts searching for existing ZigBee network. Please make sure the permit-to-join feature on the router or coordinator of your ZigBee network is enabled.
  3. If the Power Switch successfully joins a ZigBee network, the LED Indicator will flash twice to confirm.
  4. After joining the ZigBee network, the Power Switch will be registered in the network automatically. Please check the ZigBee network coordinator, system control panel or CIE (Control and Indicating Equipment) to confirm if joining and registration is successful.
  5. If registration and joining to the network is unsuccessful, please check your ZigBee network coordinator, system control panel or CIE setting to ensure the permit-to-join function is available, and then use the Factory Reset function below to join the ZigBee network.
* _**Binding with Controller**_

![](<.gitbook/assets/3 (60).jpeg>)

After joining the ZigBee network, the Power Switch can bind itself with a controller device which can be used to turn on/off the Power Switch. To bind the Power Switch and the device:

*
  1. Press and hold the Function Button for 3 seconds, then release the button. The Power Switch will send binding request to the coordinator.
  2. Refer to your controller manual to send binding request for the device within 16 seconds.
  3. If binding is successful, the Power Switch LED indicator will flash 5 times to confirm. You can now use the controller to adjust power output level for the Power Switch.
  4. If binding is unsuccessful, please retry the binding process.
* _**Removing Device from ZigBee Network (Factory Reset)**_

![](<.gitbook/assets/4 (73).png>)

To remove the Power Switch from current ZigBee network, the Power Switch must be put to Factory Reset to complete device removal. Factory Reset function will clear the Power Switch of its stored setting and information and prompt the Power Switch to search for new ZigBee network.

**Before removing device, make sure the Power Switch is within current ZigBee network signal range**

*
  1. Press and hold the function button for 10 seconds, then release the button to reset Power Switch.
  2. Upon reset, the Power Switch will clear current ZigBee network setting and transmit signal to ZigBee coordinator to remove itself from current ZigBee network. It will then actively search for available ZigBee network again and join the network automatically.
* _**ZigBee Router Device Capacity (PSS-29ZBSR / PSM-29ZBSR Only)**_

![](<.gitbook/assets/5 (75).png>)

The Power Switch models with Router function allow other ZigBee devices to join the ZigBee Network through the Router. The Power Switch Router has maximum capacity of 40 devices, including 10 routers; the Power Switch Meter Router has maximum capacity of 10 devices including 5 routers.

| **Model No.**         | **Maximum ZigBee Device** | **Maximum ZigBee** |   |
| --------------------- | ------------------------- | ------------------ | - |
| **+ Router Capacity** | **Router Capacity**       |                    |   |
|                       |                           |                    |   |
|                       |                           |                    |   |
| **PSS-29ZBS**         | **40**                    | **10**             |   |
|                       |                           |                    |   |
| **PSM-29ZBSR**        | **10**                    | **5**              |   |
|                       |                           |                    |   |

**Operation**

![](<.gitbook/assets/6 (51).jpeg>)

* _**Installation**_
  * Plug the Power Switch into a power outlet, then Plug the appliance into the socket of the Power Switch. The appliance must be in ON status.
  * _**IMPORTANT NOTE**_**:** The Power Switch does not have a backup battery and will be powered down when AC power fails. **DO NOT** use the Power Switch as router for your security sensor or alarm control devices such as Door Contact, PIR Sensor…etc., otherwise the sensors will lose connection to ZigBee network if the Power Switch is disconnected from AC power. Plan the installation locations of these security sensors without using the Power Switch and only use a router with backup battery for them. The router function of the Power Switch should **ONLY** be used to provide signal range extension for other Power Switches/Dimmer.

2

* ![](<.gitbook/assets/7 (48).jpeg>)_**Appliance Control**_
  * After the Power Switch has successfully joined a ZigBee network, the coordinator can remotely turn on/off the Power Switch to control the appliance
  * You can also press the button on the Power Switch to toggle its on/off status
  * If you have bound a controller with the Power Switch, you can also use the controller to turn on/off the Power Switch.
  * If the Power Switch is removed from power outlet, after re-plugging the Power Switch, its previous on/off status will be restored within 1 minute.
* _**Energy Consumption Monitor (PSM-29ZBS / PSM-29ZBSR Only)**_
  * Power Switch models with built-in meter will transmit a signal with its power consumption data every 10 minutes to the ZigBee network coordinator.
  * Whenever the Power Switch energy output changes by +/- 2W, it will automatically transmit a signal with power consumption data to the ZigBee network coordinator for update.
  * The Power Switch transmits a signal with power data to coordinator whenever accumulated power usage increases by 0.1kW/hr.
  * The Meter has an accuracy of +/- 5%.
  * To clear the Power Switch of its accumulated power consumption data, follow steps below:
    1. Unplug the Power Switch from power outlet.
    2. Press and hold the function button and plug in the Power Switch again when holding down the button.
    3. Keep holding the button and release after 3 seconds. The accumulated power consumption data will be cleared.
* _**Maximum Operation Load**_
  * For 110V: the maximum operation load is 1760W and 16A.
  * For 230V: the maximum operation load is 3680W and 16A.
  * If the Power Switch is overheating, It will cut off power automatically as a safety measure. The Power Switch must be unplugged and re-plugged after cut off to resume normal operation.

![](<.gitbook/assets/8 (40).jpeg>) ![](<.gitbook/assets/9 (29).jpeg>)

**Appendix (For developers only)**

![](<.gitbook/assets/10 (46).png>)

 _**Power Switch Cluster ID**_

| **Device ID: Mains Power Outlet :0x0009** | **/ SMART\_PLUG : 0x0051** |                 |
| ----------------------------------------- | -------------------------- | --------------- |
| **Endpoint:0x01**                         |                            |                 |
|                                           |                            |                 |
| **Server Side**                           |                            | **Client Side** |
|                                           |                            |                 |
|                                           | **Mandatory**              |                 |

Basic (0x0000)

Identify(0x0003)

On/Off(0x0006)

Groups(0x0004)

Scenes(0x0005) (**PSS-29ZBS / PSS-29ZBSR Only**)

Metering(0x0702)(**PSM-29ZBS /PSM-29ZBSR Only**)

**Optional**

Groups(0x0004)

_None_

_None_

* _**Attribute of Basic Cluster Information**_

| **Identifier** | **Name**           | **Type**   | **Range**  | **Access** | **Default** | **Mandatory** |   |
| -------------- | ------------------ | ---------- | ---------- | ---------- | ----------- | ------------- | - |
| **/ Optional** |                    |            |            |            |             |               |   |
|                |                    |            |            |            |             |               |   |
| 0x0000         | _ZCLVersion_       | Unsigned   | 0x00 –0xff | Read only  | 0x01        | M             |   |
| 8-bit integer  |                    |            |            |            |             |               |   |
|                |                    |            |            |            |             |               |   |
| 0x0001         | ApplicationVersion | Unsigned   | 0x00 –0xff | Read only  | 0x00        | O             |   |
| 8-bit integer  |                    |            |            |            |             |               |   |
|                |                    |            |            |            |             |               |   |
| 0x0003         | _HWVersion_        | Unsigned   | 0x00 –0xff | Read only  | 0           | O             |   |
| 8-bit integer  |                    |            |            |            |             |               |   |
|                |                    |            |            |            |             |               |   |
| 0x0004         | _ManufacturerName_ | Character  | 0–32       | Read only  | Climax      | O             |   |
| String         | bytes              | Technology |            |            |             |               |   |
|                |                    |            |            |            |             |               |   |
| 0x0005         | _ModelIdentifier_  | Character  | 0–32       | Read only  | (Model      | O             |   |
| String         | bytes              | Version)   |            |            |             |               |   |
|                |                    |            |            |            |             |               |   |
| 0x0006         | _DateCode_         | Character  | 0–16       | Read only  |             | O             |   |
| String         | bytes              |            |            |            |             |               |   |
|                |                    |            |            |            |             |               |   |
| 0x0007         | _PowerSource_      | 8-bit      | 0x00 –0xff | Read only  |             | M             |   |
|                |                    |            | 3          |            |             |               |   |

| 0x0010                                               | _LocationDescription_ | Character      | 0–32         |   |            | Read / Write |             | O             |   |   |
| ---------------------------------------------------- | --------------------- | -------------- | ------------ | - | ---------- | ------------ | ----------- | ------------- | - | - |
| String                                               | bytes                 |                |              |   |            |              |             |               |   |   |
|                                                      |                       |                |              |   |            |              |             |               |   |   |
| 0x0011                                               | _PhysicalEnvironment_ | 8-bit          | 0x00 –0xff   |   |            | Read / Write | 0x00        | O             |   |   |
| 0x0012                                               | _DeviceEnabled_       | Boolean        | 0x00 –       |   |            | Read / Write | 0x01        | M             |   |   |
| 0x01                                                 |                       |                |              |   |            |              |             |               |   |   |
|                                                      |                       |                |              |   |            |              |             |               |   |   |
|  _**Attribute of Identify Cluster Information**_    |                       |                |              |   |            |              |             |               |   |   |
|                                                      |                       |                |              |   |            |              |             |               |   |   |
| **Identifier**                                       | **Name**              | **Type**       | **Range**    |   | **Access** |              | **Default** | **Mandatory** |   |   |
|                                                      |                       | **/ Optional** |              |   |            |              |             |               |   |   |
|                                                      |                       |                |              |   |            |              |             |               |   |   |
| 0x0000                                               | _IdentifyTime_        | Unsigned       | 0x00 –0xffff |   | Read /     |              | 0x0000      | M             |   |   |
| 16-bit integer                                       |                       | Write          |              |   |            |              |             |               |   |   |
|                                                      |                       |                |              |   |            |              |             |               |   |   |
|  _**Attributes of the Groups cluster Information**_ |                       |                |              |   |            |              |             |               |   |   |
|                                                      |                       |                |              |   |            |              |             |               |   |   |
| **Identifier**                                       | **Name**              | **Type**       | **Range**    |   | **Access** |              | **Default** | **Mandatory** |   |   |
|                                                      |                       | **/ Optional** |              |   |            |              |             |               |   |   |
|                                                      |                       |                |              |   |            |              |             |               |   |   |
| 0x0000                                               | _NameSupport_         | 8-bit bitmap   | x0000000     |   | Read only  |              | -           | M             |   |   |

![](<.gitbook/assets/11 (37).png>) ![](<.gitbook/assets/12 (41).png>) ![](<.gitbook/assets/13 (25).jpeg>)

* _**Attributes of the Scenes cluster Information**_

![](<.gitbook/assets/14 (22).jpeg>)

| **Identifier**                                  | **Name**       | **Type**        | **Range**       | **Access** | **Default** | **Mandatory** |   |
| ----------------------------------------------- | -------------- | --------------- | --------------- | ---------- | ----------- | ------------- | - |
| **/ Optional**                                  |                |                 |                 |            |             |               |   |
|                                                 |                |                 |                 |            |             |               |   |
| 0x0000                                          | SceneCount     | Unsigned 8-bit  | 0x00 – 0xff     | Read only  | 0x00        | M             |   |
| integer                                         |                |                 |                 |            |             |               |   |
|                                                 |                |                 |                 |            |             |               |   |
| 0x0001                                          | _CurrentScene_ | Unsigned 8-bit  | 0x00 – 0xff     | Read only  | 0x00        | M             |   |
| integer                                         |                |                 |                 |            |             |               |   |
|                                                 |                |                 |                 |            |             |               |   |
| 0x0002                                          | _CurrentGroup_ | Unsigned 16-bit | 0x0000 – 0xfff7 | Read only  | 0x00        | M             |   |
|                                                 | integer        |                 |                 |            |             |               |   |
|                                                 |                |                 |                 |            |             |               |   |
| 0x0003                                          | _SceneValid_   | Boolean         | 0x00 – 0x01     | Read only  | 0x00        | M             |   |
| 0x0004                                          | _NameSupport_  | 8-bit bitmap    | x0000000        | Read only  | -           | M             |   |
|  _**Attribute of On/Off Cluster Information**_ |                |                 |                 |            |             |               |   |

![](<.gitbook/assets/15 (30).png>)

| **Identifier** | **Name** | **Type** | **Range**  | **Access** | **Default** | **Mandatory** |   |
| -------------- | -------- | -------- | ---------- | ---------- | ----------- | ------------- | - |
| **/ Optional** |          |          |            |            |             |               |   |
|                |          |          |            |            |             |               |   |
| 0x0000         | _OnOff_  | Boolean  | 0x00 –0x01 | Read only  | 0x00        | M             |   |

![](<.gitbook/assets/16 (32).png>)

 _**Attributes of the Metering cluster Information (Reading Information Attribute**_

![](<.gitbook/assets/17 (16).jpeg>)

_**Set) (PSM-29ZBS / PSM-29ZBSR Only)**_

| **Identifier** | **Name**         | **Type**       | **Range**         | **Access** | **Default** | **Mandatory** |   |
| -------------- | ---------------- | -------------- | ----------------- | ---------- | ----------- | ------------- | - |
| **/ Optional** |                  |                |                   |            |             |               |   |
|                |                  |                |                   |            |             |               |   |
| 0x00           | CurrentSummation | Unsigned       | 0x000000000000 to | Read       |             | M             |   |
| Delivered      | 48-bit Integer   | 0xFFFFFFFFFFFF | Only              |            |             |               |   |
|                |                  |                |                   |            |             |               |   |

![](<.gitbook/assets/18 (27).png>)

 _**Attributes of the Metering cluster Information (Formatting Attribute Set)**_

![](<.gitbook/assets/19 (7).jpeg>)

_**(PSM-29ZBS / PSM-29ZBSR Only)**_

| **Identifier** | **Name**           | **Type**     | **Range**    | **Access** | **Default** | **Mandatory** |   |
| -------------- | ------------------ | ------------ | ------------ | ---------- | ----------- | ------------- | - |
| **/ Optional** |                    |              |              |            |             |               |   |
|                |                    |              |              |            |             |               |   |
| 0x00           | UnitofMeasure      | 8-bit        | 0x00 to 0xFF | Read Only  | 0x00        | M             |   |
| Enumeration    |                    |              |              |            |             |               |   |
|                |                    |              |              |            |             |               |   |
| 0x01           | Multiplier         | Unsigned     | 0x000000 to  | Read Only  | 1           | O             |   |
| 24-bit Integer | 0xFFFFFF           |              |              |            |             |               |   |
|                |                    |              |              |            |             |               |   |
| 0x02           | Divisor            | Unsigned     | 0x000000 to  | Read Only  | 10000       | O             |   |
| 24-bit Integer | 0xFFFFFF           |              |              |            |             |               |   |
|                |                    |              |              |            |             |               |   |
| 0x03           | SummationFormating | 8-bit BitMap | 0x00 to 0xFF | Read Only  | 0xF9        | M             |   |
| 0x04           | DemandFormating    | 8-bit BitMap | 0x00 to 0xFF | Read Only  | 0x93        | O             |   |
| 0x06           | MeteringDeviceType | 8-bit BitMap | 0x00 to 0xFF | Read Only  | 0x00        | M             |   |

![](<.gitbook/assets/20 (21).png>)

* _**Attributes of the Metering cluster Information (Historical Attribute Set) (PSM-29ZBS / PSM-29ZBSR Only)**_

| **Identifier** | **Name**            | **Type**      | **Range**     | **Access** | **Default** | **Mandatory** |   |
| -------------- | ------------------- | ------------- | ------------- | ---------- | ----------- | ------------- | - |
| **/ Optional** |                     |               |               |            |             |               |   |
|                |                     |               |               |            |             |               |   |
| 0x00           | InstantaneousDemand | Signed 24-bit | -8,388,607 to | Read Only  | 0x00        | O             |   |
| Integer        | 8,388,607           |               |               |            |             |               |   |
|                |                     |               |               |            |             |               |   |

4
