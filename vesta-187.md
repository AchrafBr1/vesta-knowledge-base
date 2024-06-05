# VESTA 187

**WSS-4E-ZBS Smart Scenario Switch**

**Introduction**

WSS-4E-ZBS is a ZigBee Four Touch Button Scenario Switch designed to control a group of pre-programmed home automation devices by simply pressing the scenario touch buttons under the same ZigBee network.

The Scenario Switch utilizes ZigBee technology for wireless signal transmission. ZigBee is a wireless communication protocol that is reliable and has low power consumption and high transmission efficiency. Based on the IEEE802.15.4 standard, ZigBee allows a large amount of devices to be included in a network and coordinated for data exchange and signal transmission.

The Scenario Switch serves as an end device in the ZigBee network. It can be included in the ZigBee network to transmit signal upon activation, and can control any ZigBee device, but cannot permit any other ZigBee device to join the network through the Scenario Switch.

The WSS-4E ZigBee Four Touch Button Scenario Switch includes the following models:

WSS-4E-ZBS

WSS-4E-ZBS-OTA

![](<.gitbook/assets/0 (84).jpeg>)

**Device Introduction**

**1. Scenario LED**

There are four Scenario LEDs, the LED will light up according to the correspondent Scenario touch button pressed.

When the Scenario Switch receives acknowledge from the Control Panel after a button press, it will flash once and emit a beep as indication.

If the LED flashes twice upon touch button press, it means the ZigBee control panel was unable to receive signal sent from Scenario Switch, please check ZigBee connectivity.

**2. Scenario Touch Button**

The Scenario Switch has 4 scenario touch buttons:

Touch Button 1

![](<.gitbook/assets/1 (78).jpeg>)

Touch Button 2

Touch Button 3

Touch Button 4

1. **Battery Compartment**
2. **Function Button**
   * Press and hold for 10 seconds to reset.
3. **ZigBee LED (Red)**

Red LED lights up in the following situations:

*
  * Flashes once:

When sending control, resetting, or learning signal.

When the Scenario Switch receives acknowledgement from the Control Panel after a button press.

*
  * Flashes twice:

The Scenario Switch has successfully joined a ZigBee network.

1. **Function Button Hole**

**Features**

![](<.gitbook/assets/2 (65).jpeg>)

* _**Battery and Low Battery Detection**_

The Scenario Switch uses two 1.5V AA Alkaline batteries as its power source. The Scenario Switch feature Low Battery Detection function. When the battery voltage is low, the Scenario Switch will transmit Low Battery signal to the ZigBee network coordinator.

1

* ![](<.gitbook/assets/3 (75).png>)_**Scenario**_

When a Scenario Touch Button is pressed, the Scenario Switch will send a signal to the Control Panel to activate the correspondent scenario (see Control Panel for details).

**ZigBee Network Setup**

![](<.gitbook/assets/4 (53).jpeg>)

* _**ZigBee Device Guideline**_

ZigBee is a wireless communication protocol that is reliable and has low power consumption and high transmission efficiency. Based on IEEE802.15.4 standard, ZigBee allows a large amount of devices to be included in a network and coordinated for data exchange and signal transmission.

Due to the fundamental structure of ZigBee network, ZigBee device will actively seek and join network after powering on. Since performing a task in connecting network may consume some power, it is required to follow the instructions to avoid draining battery of a ZigBee device.

*
  * Ensure your ZigBee network router or coordinator is powered on before inserting battery into ZigBee device.
  * Ensure the ZigBee network router or coordinator is powered on and within range while a ZigBee device is in use.
  * Do not remove a ZigBee device from the ZigBee network router or coordinator without removing the battery from a ZigBee device.
* _**Joining the ZigBee Network**_

![](<.gitbook/assets/5 (40).jpeg>)

As a ZigBee device, the Scenario Switch needs to join a ZigBee network to connect to the ZigBee devices.

Please follow the steps bellow to join the Scenario Switch into the ZigBee network.

*
  1. Remove the cover by using a screwdriver.
  2. Insert the battery then replace the cover.
  3. Press and hold the Function Button for 10 seconds and release when the Red LED flashes once to join ZigBee network. Please make sure to enable the permit-join feature on the router or coordinator of your ZigBee network.
  4. If the Scenario Switch successfully joins a ZigBee network, the Red LED Indicator will flash twice to confirm.
  5. After joining the ZigBee network, the Scenario Switch will be registered in the network automatically. Please check the ZigBee network coordinator, system control panel or CIE (Control and Indicating Equipment) to confirm if joining and registration is successful.
* _**Removing Device from ZigBee Network (Factory Reset)**_

![](<.gitbook/assets/6 (54).png>)

To remove the Scenario Switch from current ZigBee network, the switch must be put to Factory Reset to complete device removal. Factory Reset function will clear the d of its stored setting information and prompt the Scenario Switch to search for new ZigBee network.

**Before removing device, make sure the Scenario Switch is within current ZigBee network signal range**

*
  1. Press and hold the function button for 10 seconds, then release the button to reset Scenario Switch.
  2. Upon reset, the Scenario Switch will clear current ZigBee network setting and transmit signal to ZigBee coordinator to remove itself from current ZigBee network. It will then actively search for available ZigBee network again and join the network automatically.
* _**OTA Firmware Upgrade (For OTA version only)**_

![](<.gitbook/assets/7 (49).png>)

The Four Touch Button Scenario Switch supports OTA firmware upgrade feature via ZigBee network, which can be initiated from the ZigBee network coordinator. Follow steps below to perform OTA firmware upgrade. **Step 1.** You have to access your ZigBee Coordinator to perform the firmware upgrade on the air.

**Step 2.** On the configuration webpage, select the device that you wish to upgrade and select the new ZigBee firmware provided. Please refer to ZigBee Coordinator User Manual for detail.

**Step 3.**Press“OK”to start upgrading process, and the LED will keep flashing. During the OTA process,

please do not perform any other actions, or power down the panel.

**Step 4.**The length of an upgrade will take approximately 20 to 30 minutes. Please note that the duration may vary based on file size or distance between your accessory and coordinator.

**Step 5.**Wait for firmware to complete update. When the progress reaches 100%, the Device will reset automatically. You can also refresh the webpage again to ensure if the Device firmware is successfully updated with the newest version displayed.

**Installation**

* The Scenario Switch is designed to be mounted on a flat surface with fixing screws.
* The base has 3 knockouts, where the plastic is thinner, for mounting purpose.
  1. Remove the cover by using a screwdriver.
  2. Break through the appropriate knockouts on the base.
  3. Using the holes as a template, drill holes in the surface.
  4. Screw the base into the surface.
  5. Replace the cover back onto the base and secure it by tightening the fixing screw.

2

![](<.gitbook/assets/8 (41).jpeg>)

* **Appendix (For developers only)**
  * _**Scene Selector Cluster ID**_

**Device ID: Scene Selector 0x0004**

**Endpoint: 0x01**

| **Server Side**             |         |                       |                                                 |                  |              |                 |                   | **Client Side** |                 |                 |   |
| --------------------------- | ------- | --------------------- | ----------------------------------------------- | ---------------- | ------------ | --------------- | ----------------- | --------------- | --------------- | --------------- | - |
|                             |         |                       |                                                 |                  |              |                 |                   |                 |                 |                 |   |
|                             |         |                       |                                                 | **Mandatory**    |              |                 |                   |                 |                 |                 |   |
|                             |         |                       |                                                 |                  |              |                 |                   |                 |                 |                 |   |
| Basic (0x0000)              |         |                       |                                                 |                  |              |                 | Identify (0x0003) |                 |                 |                 |   |
|                             |         |                       |                                                 |                  |              |                 |                   |                 |                 |                 |   |
| Identify(0x0003)            |         |                       |                                                 |                  |              | Groups (0x0004) |                   |                 |                 |                 |   |
|                             |         |                       |                                                 |                  |              |                 |                   |                 |                 |                 |   |
|                             |         |                       |                                                 |                  |              |                 |                   |                 | Scenes (0x0005) |                 |   |
|                             |         |                       |                                                 |                  |              |                 |                   |                 |                 |                 |   |
|                             |         |                       |                                                 | **Optional**     |              |                 |                   |                 |                 |                 |   |
|                             |         |                       |                                                 |                  |              |                 |                   |                 |                 |                 |   |
| Power Configuration(0x0001) |         |                       |                                                 |                  |              |                 | _None_            |                 |                 |                 |   |
|                             |         |                       |                                                 |                  |              |                 |                   |                 |                 |                 |   |
|                             |         |                      | _**Attribute of Basic Cluster Information**_    |                  |              |                 |                   |                 |                 |                 |   |
|                             |         |                       |                                                 |                  |              |                 |                   |                 |                 |                 |   |
| _**Identifier**_            |         |                       | _**Name**_                                      | _**Type**_       |              | _**Range**_     |                   | _**Access**_    | _**Default**_   | _**Mandatory**_ |   |
|                             |         |                       |                                                 | _**/ Optional**_ |              |                 |                   |                 |                 |                 |   |
|                             |         |                       |                                                 |                  |              |                 |                   |                 |                 |                 |   |
| 0x0000                      |         |                       | _ZCLVersion_                                    | Unsigned 8-bit   |              | 0x00 –0xff      |                   | Read            | 0x01            | M               |   |
|                             |         | integer               |                                                 |                  | only         |                 |                   |                 |                 |                 |   |
|                             |         |                       |                                                 |                  |              |                 |                   |                 |                 |                 |   |
| 0x0001                      |         | ApplicationVersion    | Unsigned 8-bit                                  | 0x00 – 0xff      |              | Read            | 0x00              | O               |                 |                 |   |
|                             | integer |                       | only                                            |                  |              |                 |                   |                 |                 |                 |   |
|                             |         |                       |                                                 |                  |              |                 |                   |                 |                 |                 |   |
| 0x0003                      |         |                       | _HWVersion_                                     | Unsigned 8-bit   |              | 0x00 –0xff      |                   | Read            | 0               | O               |   |
|                             |         | integer               |                                                 |                  | only         |                 |                   |                 |                 |                 |   |
|                             |         |                       |                                                 |                  |              |                 |                   |                 |                 |                 |   |
| 0x0004                      |         | _ManufacturerName_    | Character                                       | 0 – 32 bytes     |              | Read            | Climax            | O               |                 |                 |   |
|                             | String  |                       | only                                            | Technology       |              |                 |                   |                 |                 |                 |   |
|                             |         |                       |                                                 |                  |              |                 |                   |                 |                 |                 |   |
| 0x0005                      |         |                       | _ModelIdentifier_                               | Character        | 0 – 32 bytes |                 | Read              | (Model Number)  | O               |                 |   |
|                             |         | String                |                                                 | only             |              |                 |                   |                 |                 |                 |   |
|                             |         |                       |                                                 |                  |              |                 |                   |                 |                 |                 |   |
| 0x0006                      |         |                       | _DateCode_                                      | Character        | 0 – 16 bytes |                 | Read              |                 | O               |                 |   |
|                             |         | String                |                                                 | only             |              |                 |                   |                 |                 |                 |   |
|                             |         |                       |                                                 |                  |              |                 |                   |                 |                 |                 |   |
| 0x0007                      |         |                       | _PowerSource_                                   | 8-bit            |              | 0x00 –0xff      |                   | Read            |                 | M               |   |
|                             |         |                       |                                                 | only             |              |                 |                   |                 |                 |                 |   |
|                             |         |                       |                                                 |                  |              |                 |                   |                 |                 |                 |   |
| 0x0010                      |         | _LocationDescription_ | Character                                       | 0 – 32 bytes     |              | Read /          |                   | O               |                 |                 |   |
|                             | String  |                       | Write                                           |                  |              |                 |                   |                 |                 |                 |   |
|                             |         |                       |                                                 |                  |              |                 |                   |                 |                 |                 |   |
| 0x0011                      |         | _PhysicalEnvironment_ | 8-bit                                           |                  | 0x00 –0xff   |                 | Read /            | 0x00            | O               |                 |   |
|                             |         |                       | Write                                           |                  |              |                 |                   |                 |                 |                 |   |
|                             |         |                       |                                                 |                  |              |                 |                   |                 |                 |                 |   |
| 0x0012                      |         |                       | _DeviceEnabled_                                 | Boolean          | 0x00 –0x01   |                 | Read /            | 0x01            | M               |                 |   |
|                             |         |                       | Write                                           |                  |              |                 |                   |                 |                 |                 |   |
|                             |         |                       |                                                 |                  |              |                 |                   |                 |                 |                 |   |
|                             |         |                      | _**Attribute of Identify Cluster Information**_ |                  |              |                 |                   |                 |                 |                 |   |
|                             |         |                       |                                                 |                  |              |                 |                   |                 |                 |                 |   |
| **Identifier**              |         |                       | **Name**                                        | **Type**         |              | **Range**       |                   | **Access**      | **Default**     | **Mandatory**   |   |
|                             |         |                       |                                                 | **/ Optional**   |              |                 |                   |                 |                 |                 |   |
|                             |         |                       |                                                 |                  |              |                 |                   |                 |                 |                 |   |
| 0x0000                      |         |                       | _IdentifyTime_                                  | Unsigned         | 0x00 –0xffff |                 | Read /            | 0x0000          | M               |                 |   |
|                             |         | 16-bit integer        |                                                 | Write            |              |                 |                   |                 |                 |                 |   |
|                             |         |                       |                                                 |                  |              |                 |                   |                 |                 |                 |   |

* _**Attribute of Power Configuration Cluster Information**_

| **Identifier** | **Name**         | **Type** | **Range**   | **Access** | **Default** | **Mandatory** |   |
| -------------- | ---------------- | -------- | ----------- | ---------- | ----------- | ------------- | - |
| **/ Optional** |                  |          |             |            |             |               |   |
|                |                  |          |             |            |             |               |   |
| 0x0035         | BatteryAlarmMask | Bitmap   | 0000 - 000x | Read /     | 0000 0000   | O             |   |
| (8-bits)       | Write            |          |             |            |             |               |   |
|                |                  |          |             |            |             |               |   |

3
