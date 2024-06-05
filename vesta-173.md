# VESTA 173

**RSB-1ZBS**

**RGBW Smart Bulb**

**Introduction**

![](<.gitbook/assets/0 (73).jpeg>)

The RSB-1ZBS is a ZigBee Smart LED Color Light Bulb. It features both multicolor adjustment and light level control. When joined into a ZigBee network, the user will be able to control Light Bulb remotely from the ZigBee network coordinator.

The Light Bulb utilizes ZigBee technology for wireless signal transmission. ZigBee is a wireless communication protocol that is reliable and has low power consumption and high transmission efficiency. Based on the IEEE802.15.4 standard, ZigBee allows a large amount of devices to be included in a network and coordinated for data exchange and signal transmission

The Light Bulb also serves as a route in the ZigBee network. After being included in the ZigBee network, it allows other ZigBee devices to join the network through the Light Bulb.

**ZigBee Network Setup**

![](<.gitbook/assets/1 (68).jpeg>)

* _**ZigBee Device Guideline**_

ZigBee is a wireless communication protocol that is reliable, has low power consumption and has high transmission efficiency. Based on the IEEE802.15.4 standard, ZigBee allows a large amount of devices to be included in a network and coordinated for data exchange and signal transmission.

Due to the fundamental structure of ZigBee network, ZigBee device will actively seek and join network after powering on.

*
  * Ensure your ZigBee network router or coordinator is powered on before powering on the ZigBee device.
  * Ensure your ZigBee network router or coordinator is powered on and within range while a ZigBee device is in use.
  * Do not remove a ZigBee device from the ZigBee network router or coordinator without powering down the ZigBee device.
* _**Joining the ZigBee Network**_

![](<.gitbook/assets/2 (57).jpeg>)

As a ZigBee device, the Light Bulb needs to join a ZigBee network to send and receive command signals. Please follow the steps below to add the Light Bulb into the ZigBee network.

Step 1. Scroll the Light Bulb into the lamp socket. Do not supply power yet.

Step 2. Enable the permit-join feature on the router or coordinator of your ZigBee network.

Step 3. Switch ON Light Bulb for 3\~5 seconds. (No more than 5 seconds), then switch OFF.

Step 4. Repeat Step 3 for three (3) times for a total of four (4) ON/OFF cycles.

Step 5. Switch ON Light Bulb for the 5th time, the device will reset and start searching for new ZigBee network.

Step 6. After joining the ZigBee network, the Light Bulb will be registered in the security system in the network automatically. Please check the ZigBee network coordinator, system control panel, or CIE (Control and Indicating Equipment) to confirm if joining and registration was successful.

![](<.gitbook/assets/3 (71).png>) ![](<.gitbook/assets/4 (48).jpeg>)

* _**Removing Device from ZigBee Network (Factory Reset)**_

To remove the Light Bulb from current ZigBee network, the device must be placed on Factory Reset to complete device removal. Factory Reset function will clear the Light Bulb of its stored setting and information and prompt the Light Bulb to search for new ZigBee network.

**Before removing device, make sure the Light Bulb is within current ZigBee network signal range**

1. Delete the Light Bulb from current control panel / CIE.
2. Power off the Light Bulb.
3. Switch ON Light Bulb for 3\~5 seconds. (No more than 5 seconds), then switch OFF.
4. Repeat Step 3 for 3 times for a total of 4 ON/OFF cycles
5. Switch ON Light Bulb for the 5th time, the device will reset and start searching for new ZigBee network.
6. Upon reset, the Light Bulb will clear current ZigBee network setting and transmit signal to ZigBee coordinator to remove itself from current ZigBee network. It will then actively search for available ZigBee network again and join the network automatically.

1

![](<.gitbook/assets/5 (36).jpeg>) ![](<.gitbook/assets/6 (48).jpeg>)

* _**ZigBee Router Device Capacity**_

The Light Bulb with Router function allows other ZigBee devices to join the ZigBee Network through the Router. The Light Bulb has a maximum capacity of 7 devices, including 4 routers.

**Features**

![](<.gitbook/assets/7 (46).png>)

* _**Color and Saturation Adjustment**_

The Light Bulb’s color and saturation may be adjusted from the ZigBee Coordinators remotely by sending commands.

![](<.gitbook/assets/8 (49).png>)

* _**Light Level Adjustment**_

The Light Bulb has dimmable lighting, the light percentage maybe adjusted from the ZigBee Coordinators remotely by sending commands.

![](<.gitbook/assets/9 (50).png>)

* _**Supervision**_

The Light Bulb will transmit a supervision signal to report its condition regularly according to user setting. The factory default interval is 10 minutes.

**Appendix (For developers only)**

![](<.gitbook/assets/10 (45).png>)

* _**Light Bulb Cluster ID**_

**Device ID: Color\_Dimmable\_Light: 0x0102**

**Endpoint: 0x01**

| **Server Side**       |                                                                |                                                         | **Client Side** |        |   |   |
| --------------------- | -------------------------------------------------------------- | ------------------------------------------------------- | --------------- | ------ | - | - |
|                       |                                                                |                                                         |                 |        |   |   |
|                       |                                                                | **Mandatory**                                           |                 |        |   |   |
|                       |                                                                |                                                         |                 |        |   |   |
| Basic (0x0000)        |                                                                |                                                         |                 | _None_ |   |   |
|                       |                                                                |                                                         |                 |        |   |   |
| Identify(0x0003)      |                                                                |                                                         |                 |        |   |   |
|                       |                                                                |                                                         |                 |        |   |   |
| Groups(0x0004)        |                                                                |                                                         |                 |        |   |   |
|                       |                                                                |                                                         |                 |        |   |   |
| Scenes(0x0005)        |                                                                |                                                         |                 |        |   |   |
|                       |                                                                |                                                         |                 |        |   |   |
| OnOff(0x0006)         |                                                                |                                                         |                 |        |   |   |
|                       |                                                                |                                                         |                 |        |   |   |
| Level Control(0x0008) |                                                                |                                                         |                 |        |   |   |
|                       |                                                                |                                                         |                 |        |   |   |
| Color Control(0x0300) |                                                                |                                                         |                 |        |   |   |
|                       |                                                                |                                                         |                 |        |   |   |
|                       |                                                                | **Optional**                                            |                 |        |   |   |
|                       |                                                                |                                                         |                 |        |   |   |
| _None_                |                                                                |                                                         |                 | _None_ |   |   |
|                       |                                                                |                                                         |                 |        |   |   |
|                       |                                                                |                                                         |                 |        |   |   |
| **Report Cluster**    |                                                                | On/Off (0x0006)                                         |                 |        |   |   |
| **Report Attribute**  |                                                                | ATTRID\_ON\_OFF (0x0000)                                |                 |        |   |   |
| **Datatype**          |                                                                | ZCL\_DATATYPE\_BOOLEAN                                  |                 |        |   |   |
| **minReportInt**      |                                                                | 0                                                       |                 |        |   |   |
| **maxReportInt**      |                                                                | default value: 0x258 sec (600 sec)                      |                 |        |   |   |
|                       |                                                                |                                                         |                 |        |   |   |
| **Report Cluster**    |                                                                | Level Control (0x0008)                                  |                 |        |   |   |
| **Report Attribute**  |                                                                | ATTRID\_LEVEL\_CURRENT\_LEVEL (0x0000)                  |                 |        |   |   |
| **Datatype**          |                                                                | ZCL\_DATATYPE\_UINT8                                    |                 |        |   |   |
| **minReportInt**      |                                                                | 0                                                       |                 |        |   |   |
| **maxReportInt**      |                                                                | default value: 0x258 sec (600 sec)                      |                 |        |   |   |
|                       |                                                                |                                                         |                 |        |   |   |
| **Report Cluster**    |                                                                | Color Control (0x0300)                                  |                 |        |   |   |
| **Report Attribute**  |                                                                | ATTRID\_LIGHTING\_COLOR\_CONTROL\_CURRENT\_HUE (0x0000) |                 |        |   |   |
| **Datatype**          |                                                                | ZCL\_DATATYPE\_UINT8                                    |                 |        |   |   |
|                       | ATTRID\_LIGHTING\_COLOR\_CONTROL\_CURRENT\_SATURATION (0x0001) |                                                         |                 |        |   |   |
|                       |                                                                |                                                         |                 |        |   |   |
| **Datatype**          |                                                                | ZCL\_DATATYPE\_UINT8                                    |                 |        |   |   |
|                       | ATTRID\_LIGHTING\_COLOR\_CONTROL\_COLOR\_TEMPERATURE (0x0007)  |                                                         |                 |        |   |   |
|                       |                                                                |                                                         |                 |        |   |   |
| **Datatype**          |                                                                | ZCL\_DATATYPE\_UINT16                                   |                 |        |   |   |
| **minReportInt**      |                                                                | 0                                                       |                 |        |   |   |
| **maxReportInt**      |                                                                | default value:0x258 sec (600 sec)                       |                 |        |   |   |
|                       |                                                                | 2                                                       |                 |        |   |   |

![](<.gitbook/assets/11 (23).jpeg>) ![](<.gitbook/assets/12 (20).jpeg>)

* ![](<.gitbook/assets/13 (33).png>)_**Attribute of Basic Cluster Information**_

| **Identifier**                                    | **Name**              | **Type**       | **Range**    | **Access** | **Default**       | **Mandatory** |   |
| ------------------------------------------------- | --------------------- | -------------- | ------------ | ---------- | ----------------- | ------------- | - |
| **/ Optional**                                    |                       |                |              |            |                   |               |   |
|                                                   |                       |                |              |            |                   |               |   |
| 0x0000                                            | _ZCLVersion_          | Unsigned 8-bit | 0x00 –0xff   | Read only  | 0x01              | M             |   |
| integer                                           |                       |                |              |            |                   |               |   |
|                                                   |                       |                |              |            |                   |               |   |
| 0x0003                                            | HWVersion             | Unsigned 8-bit | 0x00 –0xff   | Read only  | 0                 | O             |   |
| integer                                           |                       |                |              |            |                   |               |   |
|                                                   |                       |                |              |            |                   |               |   |
| 0x0004                                            | _ManufacturerName_    | Character      | 0 – 32 bytes | Read only  | Climax Technology | O             |   |
| String                                            |                       |                |              |            |                   |               |   |
|                                                   |                       |                |              |            |                   |               |   |
| 0x0005                                            | _ModelIdentifier_     | Character      | 0 – 32 bytes | Read only  | SLCB\_00.00.03.01 | O             |   |
| String                                            | TC                    |                |              |            |                   |               |   |
|                                                   |                       |                |              |            |                   |               |   |
| 0x0006                                            | _DateCode_            | Character      | 0 – 16 bytes | Read only  | 20170124          | O             |   |
| String                                            |                       |                |              |            |                   |               |   |
|                                                   |                       |                |              |            |                   |               |   |
| 0x0007                                            | _PowerSource_         | 8-bit          | 0x00 –0xff   | Read only  |                   | M             |   |
| Enumeration                                       |                       |                |              |            |                   |               |   |
|                                                   |                       |                |              |            |                   |               |   |
| 0x0010                                            | _LocationDescription_ | Character      | 0 – 32 bytes | Read/Write |                   | O             |   |
| string                                            |                       |                |              |            |                   |               |   |
|                                                   |                       |                |              |            |                   |               |   |
| 0x0011                                            | _PhysicalEnvironment_ | 8-bit          | 0x00 –0xff   | Read/Write | 0x00              | O             |   |
| Enumeration                                       |                       |                |              |            |                   |               |   |
|                                                   |                       |                |              |            |                   |               |   |
| 0x0012                                            | _DeviceEnabled_       | Boolean        | 0x00 –0x01   | Read/Write | 0x01              | M             |   |
|  _**Attribute of Identify Cluster Information**_ |                       |                |              |            |                   |               |   |

![](<.gitbook/assets/14 (27).png>)

| **Identifier**                                 | **Name**       | **Type** | **Range**    | **Access**   | **Default** | **Mandatory /** |   |
| ---------------------------------------------- | -------------- | -------- | ------------ | ------------ | ----------- | --------------- | - |
| **Optional**                                   |                |          |              |              |             |                 |   |
|                                                |                |          |              |              |             |                 |   |
| 0x0000                                         | _IdentifyTime_ | Unsigned | 0x00 –0xffff | Read / Write | 0x0000      | M               |   |
| 16-bit integer                                 |                |          |              |              |             |                 |   |
|                                                |                |          |              |              |             |                 |   |
|  _**Attribute of Group Cluster Information**_ |                |          |              |              |             |                 |   |

![](<.gitbook/assets/15 (27).png>)

| **Identifier**                                         | **Name**                 |                         |                        |                 |              | **Type**     |          |           |             | **Range**   |                |                | **Access**   |            |             | **Default** | **Mandatory /** |                 |   |   |   |   |   |   |   |
| ------------------------------------------------------ | ------------------------ | ----------------------- | ---------------------- | --------------- | ------------ | ------------ | -------- | --------- | ----------- | ----------- | -------------- | -------------- | ------------ | ---------- | ----------- | ----------- | --------------- | --------------- | - | - | - | - | - | - | - |
|                                                        |                          |                         |                        |                 |              |              |          |           |             |             |                | **Optional**   |              |            |             |             |                 |                 |   |   |   |   |   |   |   |
|                                                        |                          |                         |                        |                 |              |              |          |           |             |             |                |                |              |            |             |             |                 |                 |   |   |   |   |   |   |   |
| 0x0000                                                 | _NameSupport_            |                         |                        |                 | 8-bit bitmap |              |          | X0000000  |             | Read only   |                |                |              | -          |             | M           |                 |                 |   |   |   |   |   |   |   |
|  _**Attribute of Scenes Cluster Information**_        |                          |                         |                        |                 |              |              |          |           |             |             |                |                |              |            |             |             |                 |                 |   |   |   |   |   |   |   |
| **Identifier**                                         | **Name**                 |                         |                        |                 |              | **Type**     |          |           |             | **Range**   |                |                | **Access**   |            | **Default** |             | **Mandatory**   |                 |   |   |   |   |   |   |   |
|                                                        |                          |                         |                        |                 |              |              |          |           |             |             | **/ Optional** |                |              |            |             |             |                 |                 |   |   |   |   |   |   |   |
|                                                        |                          |                         |                        |                 |              |              |          |           |             |             |                |                |              |            |             |             |                 |                 |   |   |   |   |   |   |   |
| 0x0000                                                 | _SceneCount_             |                         | Unsigned 8-bit integer |                 | 0x00 – 0xff  |              |          | Read only |             | 0x00        |                | M              |              |            |             |             |                 |                 |   |   |   |   |   |   |   |
| 0x0001                                                 | _CurrentScene_           |                         | Unsigned 8-bit integer |                 | 0x00 – 0xff  |              |          | Read only |             | 0x00        |                | M              |              |            |             |             |                 |                 |   |   |   |   |   |   |   |
| 0x0002                                                 | _CurrentGroup_           | Unsigned 16-bit integer |                        | 0x0000 – 0xfff7 |              | Read only    |          | 0x00      |             | M           |                |                |              |            |             |             |                 |                 |   |   |   |   |   |   |   |
| 0x0003                                                 | _SceneValid_             |                         |                        |                 |              | Boolean      |          |           |             | 0x00 – 0x01 |                |                | Read only    |            | 0x00        |             | M               |                 |   |   |   |   |   |   |   |
| 0x0004                                                 | _NameSupport_            |                         |                        |                 |              | 8-bit bitmap |          |           |             | X0000000    |                |                | Read only    |            | -           |             | M               |                 |   |   |   |   |   |   |   |
|  _**Attribute of On/Off Cluster Information**_        |                          |                         |                        |                 |              |              |          |           |             |             |                |                |              |            |             |             |                 |                 |   |   |   |   |   |   |   |
| **Identifier**                                         | **Name**                 |                         |                        |                 |              | **Type**     |          |           |             |             | **Range**      |                |              |            | **Access**  |             | **Default**     | **Mandatory /** |   |   |   |   |   |   |   |
|                                                        |                          |                         |                        |                 |              |              |          |           |             |             |                |                | **Optional** |            |             |             |                 |                 |   |   |   |   |   |   |   |
|                                                        |                          |                         |                        |                 |              |              |          |           |             |             |                |                |              |            |             |             |                 |                 |   |   |   |   |   |   |   |
| 0x0000                                                 | _OnOff_                  |                         |                        |                 |              | Boolean      |          |           | 0x00 – 0x01 |             |                | Read Only      |              | 0x00       |             | M           |                 |                 |   |   |   |   |   |   |   |
|  _**Attribute of Level Control Cluster Information**_ |                          |                         |                        |                 |              |              |          |           |             |             |                |                |              |            |             |             |                 |                 |   |   |   |   |   |   |   |
| **Identifier**                                         | **Name**                 |                         |                        |                 |              | **Type**     |          |           |             | **Range**   |                |                | **Access**   |            | **Default** |             | **Mandatory**   |                 |   |   |   |   |   |   |   |
|                                                        |                          |                         |                        |                 |              |              |          |           |             |             | **/ Optional** |                |              |            |             |             |                 |                 |   |   |   |   |   |   |   |
|                                                        |                          |                         |                        |                 |              |              |          |           |             |             |                |                |              |            |             |             |                 |                 |   |   |   |   |   |   |   |
| 0x0000                                                 | _CurrentLevel_           |                         | Unsigned 8-bit integer |                 | 0x00 – 0xff  |              |          | Read only |             | 0x00        |                | M              |              |            |             |             |                 |                 |   |   |   |   |   |   |   |
|  _**Attribute of Color Control Cluster Information**_ |                          |                         |                        |                 |              |              |          |           |             |             |                |                |              |            |             |             |                 |                 |   |   |   |   |   |   |   |
| **Identifier**                                         | **Name**                 |                         |                        |                 |              | **Type**     |          |           |             | **Range**   |                |                |              | **Access** |             | **Default** |                 | **Mandatory**   |   |   |   |   |   |   |   |
|                                                        |                          |                         |                        |                 |              |              |          |           |             |             |                | **/ Optional** |              |            |             |             |                 |                 |   |   |   |   |   |   |   |
|                                                        |                          |                         |                        |                 |              |              |          |           |             |             |                |                |              |            |             |             |                 |                 |   |   |   |   |   |   |   |
| 0x0000                                                 | _CurrentHue_             |                         |                        |                 |              | Unsigned     |          |           |             | 0x00 – 0xff |                |                |              | Read only  |             |             | 0x00            |                 | M |   |   |   |   |   |   |
|                                                        |                          |                         |                        | 8-bit integer   |              |              |          |           |             |             |                |                |              |            |             |             |                 |                 |   |   |   |   |   |   |   |
|                                                        |                          |                         |                        |                 |              |              |          |           |             |             |                |                |              |            |             |             |                 |                 |   |   |   |   |   |   |   |
| 0x0001                                                 | _CurrentSaturation_      |                         |                        |                 | Unsigned     |              |          |           | 0x00 – 0xfe |             |                |                | Read only    |            |             | 0x00        |                 | M               |   |   |   |   |   |   |   |
|                                                        |                          |                         | 8-bit integer          |                 |              |              |          |           |             |             |                |                |              |            |             |             |                 |                 |   |   |   |   |   |   |   |
|                                                        |                          |                         |                        |                 |              |              |          |           |             |             |                |                |              |            |             |             |                 |                 |   |   |   |   |   |   |   |
| 0x0007                                                 | _ColorTemperatureMireds_ |                         | Unsigned               |                 |              |              | 0x0000 – |           |             |             | Read only      | 0x00fa (4000K) |              | M          |             |             |                 |                 |   |   |   |   |   |   |   |
|                                                        | 16-bit integer           |                         |                        |                 | 0xfeff       |              |          |           |             |             |                |                |              |            |             |             |                 |                 |   |   |   |   |   |   |   |
|                                                        |                          |                         |                        |                 |              |              |          |           |             |             |                |                |              |            |             |             |                 |                 |   |   |   |   |   |   |   |
| 0x0008                                                 | _ColorMode_              |                         |                        |                 |              | 8-bit        |          |           | 0x00 – 0x02 |             | Read only      |                |              | 0x01       |             | M           |                 |                 |   |   |   |   |   |   |   |
|                                                        |                          |                         |                        | enumeration     |              |              |          |           |             |             |                |                |              |            |             |             |                 |                 |   |   |   |   |   |   |   |
|                                                        |                          |                         |                        |                 |              |              |          |           |             |             |                |                |              |            |             |             |                 |                 |   |   |   |   |   |   |   |

![](<.gitbook/assets/16 (30).png>) ![](<.gitbook/assets/17 (23).png>) ![](<.gitbook/assets/18 (25).png>) ![](<.gitbook/assets/19 (26).png>)

3
