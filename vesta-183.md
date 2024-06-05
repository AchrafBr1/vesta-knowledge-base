# VESTA 183

**TRV-1ZBS Thermostatic Radiator Valve**

**Introduction**

TRV-1ZBS is a ZigBee Radiator Valve designed to control the surrounding temperature by controlling the flow of hot water of radiators in the ZigBee network, i.e. indoor room temperatures.

The Radiator Valve utilizes ZigBee technology for wireless signal transmission. ZigBee is a wireless communication protocol that is reliable and has low power consumption and high transmission efficiency. Based on the IEEE802.15.4 standard, ZigBee allows a large amount of devices to be included in a network and coordinated for data exchange and signal transmission.

The Radiator Valve serves as an end device in the ZigBee network. It can be included in the ZigBee network to transmit signal upon activation, it can be controlled manually or remotely.

**Parts Identification**

1. **Valve Cap**
2. **LCD Display**

![](<.gitbook/assets/0 (63).png>) ![](<.gitbook/assets/1 (74).jpeg>)

1. ![](<.gitbook/assets/2 (62).jpeg>) **ON** when device is already learned into Zig-Bee network.
2. ![](<.gitbook/assets/3 (59).jpeg>) **Low Battery Indicator.**
3. ![](<.gitbook/assets/4 (52).jpeg>) On: Device set to default temperature 17°C.

![](<.gitbook/assets/5 (39).jpeg>) Flash: Valve closing.

![](<.gitbook/assets/6 (50).jpeg>) On: Device set to default temperature 21°C.

![](<.gitbook/assets/7 (47).jpeg>) Flash: Valve opening.

1. **Auto / Manual Mode.**
2. **Boost function.**
3. **Open Window**.
4. **Temperature Indicator.**

![](<.gitbook/assets/8 (50).png>)

**Others: InS**: When power on device (also for learning period).

**AdA:** device motor working.

**F1/F3:** the valve is jammed, **F2:** no valve installed.

**3. Function Buttons**

\-**Manual/Auto:** Enter Manual or Auto mode.

\-**Boost/ ZigBee:** Speed up heating process/learn into ZigBee Network.

\- ![](<.gitbook/assets/9 (28).jpeg>) Press this button to instantly switch day and night temperatures.

_**Default day**_ ![](<.gitbook/assets/10 (21).jpeg>) _temperature: 21_ °C_, **Default night**_ ![](<.gitbook/assets/11 (25).jpeg>) _temperature: 17_°C

1. **Temperature Sensor**
2. **Control Knob**

Adjust temperature manually.

**6. Battery Compartment**

The Radiator Valve is powered by two 1.5V AA alkaline batteries.

1

**Features**

![](<.gitbook/assets/12 (40).png>)

* _**Power ON / Manual / Auto mode**_

**Power ON**: When the Radiator Valve powers on, it’s motor starts working with LCD displaying **InS**, device is ready for installation and start learning process. (see **Installation** for details)

**Manual Mode:** In the Manual mode, you can use the following functions:

*
  * ![](<.gitbook/assets/13 (24).jpeg>) button: switch day/night temperatures instantly.
  * **Boost button:** Speed up heating, learning device into Control Panel.
* **Control Knob**: Control temperature, set to ON (summer season mode) and OFF (winter season mode).

**Auto Mode:** The Auto mode is only available when device is learned with a control panel. After learning with the Control Panel you can control and set the time schedule for the Radiator Valve automatically through the control panel (please refer to your control panel manual for details).

In the Auto Mode, you can use the same functions as in Manual mode except the Control Knob Set to ON and OFF function.

![](<.gitbook/assets/14 (30).png>)

* _**Anti-frosting**_

When the Radiator Valve detects a frosting hazard, it will automatically open the valve for hot water to flow in order to maintain the temperature and to prevent further frosting.

![](<.gitbook/assets/15 (29).png>)

* _**Anti-calcification**_

The Radiator Valve will open and close the valve weekly to prevent calcification. During anti-calcification process the LCD will display a **CAL**.

The default value for anti-calcification process is 23:00p.m every Saturday.

![](<.gitbook/assets/16 (31).png>)

* _**Boost Function**_

Press the Boost button to temporarily speed up heating process by further opening the valve. The boost function lasts 5 minutes (LCD displays: 300 seconds countdown). If you wish to cancel boost function, press the button again.

![](<.gitbook/assets/17 (24).png>)

* _**Setpoint Offset**_

The device is usually installed at the corner of the room and near the heating pipe. As a result its temperature reading may deviate from room temperature at center of room. Use the Setpoint Offset function to compensate the deviation.

To calculate setpoint offset, simply subtract room temperature with device temperature.

For example: If device temperature is 20°C and room temperature is 18°C, then setpoint offset = 18 – 20 = -2°C.

After setpoint offset is applied, the device will operate according to adjusted temperature.

For example: If device temperature reading is 20°C, setpoint offset is -2°C, the device will operate using 18°C as actual reference.

To program Setpoint Offset:

*
  1. Press and hold the ![](<.gitbook/assets/18 (11).jpeg>) button for 3 seconds to enter offset adjustment.
  2. Rotate the Control Knob to desired offset temperature.
  3. Press any key to finish and exit offset adjustment.
* _**Open Window**_

![](<.gitbook/assets/19 (28).png>)

If Radiator Valve detects indoor temperature drops rapidly by opening the window, the Radiator Valve will activate Open Window function by partly closing the valve to reduce temperature setting for 15 minutes. The

![](<.gitbook/assets/20 (12).jpeg>)

LCD will display symbol, the device will check the temperature every minute. After 15 minutes, the Radiator Valve will return to the set temperature with valve opening again, Open Window Function closes.

* _**Control Knob**_

Rotate the Control Knob to adjust the temperature, rotate clockwise to reduce temperature and anti-clockwise to increase the temperature. The adjustable temperature range is 5°C to 30°C. If you rotate the Control Knob over 30°C to ON, after 1 minute, the Radiator Valve will open the valve completely, to preserve battery power. If you rotate the Control Knob lower than 5°C to OFF, after 1 minute, the Radiator Valve will close the valve completely. To disable ON/Off status please rotate the control knob or press button.

**ON:** When turned to ON, the valve is opened completely. This function is used to preserver battery life during summer, when heating is not required. Do not use this function in winter when heater is activated, otherwise the room temperature will rise uncontrolled.

**OFF:** When turn to OFF, the valve is closed completely. This function is used when heater is activated but heating is not required in a room with no occupants.

2

* _**Key Lock Function**_

Press and hold both the Auto/Manual button and the  button for 3 seconds to enable key lock function.

If successful the LCD will display the  symbol. All keys and Control Knob actions will not respond**.** If

you wish to cancel key lock function, please press and hold both the Auto/Manual button and button for 3 seconds likewise.

* _**Remote Control**_

After the Radiator Valve joins a ZigBee network, you can control the Radiator Valve via ZigBee network coordinator or gateway. Please refer to your ZigBee coordinator/gateway manual for more information.

The following functions are only available for setting via ZigBee coordinator and gateway:

* **Schedule:**

You can only program Schedule configuration via ZigBee network coordinator/gateway.

Schedule Setting: Up to 5 schedules can be programmed for every weekday with Mode, Setpoint and Start time.

Schedule Control:

Normal - The Radiator Valve will execute programmed schedule setting accordingly.

No Schedule – The Radiator Valve will not execute any set schedule until it is set to Normal again.

**Zig-Bee Network Setup and Installation**

* _**ZigBee Device Guideline**_

ZigBee is a wireless communication protocol that is reliable and has low power consumption and high transmission efficiency. Based on IEEE802.15.4 standard, ZigBee allows a large amount of devices to be included in a network and coordinated for data exchange and signal transmission.

Due to the fundamental structure of ZigBee network, ZigBee device will actively seek and join network after powering on. Since performing a task in connecting network may consume some power, it is required to follow the instructions to avoid draining battery of a ZigBee device.

*
  * Ensure your ZigBee network router or coordinator is powered on before inserting battery into ZigBee device.
  * Ensure the ZigBee network router or coordinator is powered on and within range while a ZigBee device is in use.
  * Do not remove a ZigBee device from the ZigBee network router or coordinator without removing the battery from a ZigBee device.
* _**Joining the ZigBee Network and Installation**_

As a ZigBee device, the Radiator Valve needs to join a ZigBee network for user to control it remotely. Joining ZigBee network should be performed together with installation at the same time. Please follow the steps bellow to join the Radiator Valve into the ZigBee network.

1. Remove the Radiator Valve back cover and insert 2 AA Alkaline batteries to power up the Radiator Valve,

LCD will display **InS** and  icon will flash to indicate Radiator Valve’s motor is working.

1. Press and hold the Boost button for 10 seconds, LCD will flash **888** to indicate release button to join ZigBee network. Please make sure the permit-join feature on the router or coordinator of your ZigBee network is enabled.
2. Wait for several seconds for the Radiator Valve to join ZigBee network. Please check the security system control panel or CIE (Control and Indicating Equipment) to confirm if joining and registration is successful.
3. When the motor stops working and  icon changes to steady on, attach the Valve cap to the pipe.
4. Rotating the Valve cap clockwise to tighten the Radiator Valve.
5. Press the Auto/Manual button, LCD displays **AdA** and valve motor starts working again, the  icon will flash. The device motor is measuring the distance to adjust the current temperature.
6. When the valve motor stops, the system will enter Manual mode with LCD displaying the default set

3

temperature 18.0°C, the installation is now complete.

*
  1. After joining ZigBee network and completing installation, the ZigBee connection icon  will appear on LCD display.
  2. After joining the ZigBee network, if the Radiator Valve loses connection to current ZigBee network, the ZigBee connection icon will disappear after 10 minutes. Please check the ZigBee network condition and Radiator Valve signal range to correct the situation.
* _**Removing Device from ZigBee Network (Factory Reset)**_

To remove the Radiator Valve from current ZigBee network, the device must be put to Factory Reset to complete device removal. Factory Reset function will clear the Radiator Valve of its stored setting and information and prompt it to search for new ZigBee network.

**Before removing device, make sure the Radiator Valve is within current ZigBee network signal range**

1. Press and hold the function button for 10 seconds, then release the button to reset Radiator Valve.
2. Upon reset, the Radiator Valve will clear current ZigBee network setting and transmit signal to ZigBee coordinator to remove itself from current ZigBee network. It will then actively search for available ZigBee network again and join the network automatically.

**Appendix(For developers only.)**

* _**Thermostat Cluster ID**_

**Device ID: ZCL\_HA\_DEVICEID\_THERMOSTAT 0x0301**

**Endpoint: 0x01**

| **Server Side** |               | **Client Side** |
| --------------- | ------------- | --------------- |
|                 |               |                 |
|                 | **Mandatory** |                 |

Basic (0x0000)

Power Config(0x0001)

Identify(0x0003)

HVAC THERMOSTAT (0x0201)

_Identify(0x0003)_

_TIME(0x000A)_

**Optional**

_None_

_None_

* _**Attribute of Basic Cluster Information**_

| **Identifier** | **Name**                                                     | **Type**         |   | **Range**    |                | **Access**   | **Default** | **Mandatory** |   |             |               |   |
| -------------- | ------------------------------------------------------------ | ---------------- | - | ------------ | -------------- | ------------ | ----------- | ------------- | - | ----------- | ------------- | - |
|                |                                                              | **/ Optional**   |   |              |                |              |             |               |   |             |               |   |
|                |                                                              |                  |   |              |                |              |             |               |   |             |               |   |
| 0x0000         | _ZCLVersion_                                                 | Unsigned 8-bit   |   | 0x00 –0xff   |                | Read only    | 0x01        | M             |   |             |               |   |
| integer        |                                                              |                  |   |              |                |              |             |               |   |             |               |   |
|                |                                                              |                  |   |              |                |              |             |               |   |             |               |   |
|                |                                                              |                  |   |              |                |              |             |               |   |             |               |   |
| 0x0001         | ApplicationVersion                                           | Unsigned 8-bit   |   | 0x00 –0xff   |                | Read only    | 0x00        | O             |   |             |               |   |
| integer        |                                                              |                  |   |              |                |              |             |               |   |             |               |   |
|                |                                                              |                  |   |              |                |              |             |               |   |             |               |   |
| 0x0003         | _HWVersion_                                                  | Unsigned 8-bit   |   | 0x00 –0xff   |                | Read only    | 0           | O             |   |             |               |   |
| integer        |                                                              |                  |   |              |                |              |             |               |   |             |               |   |
|                |                                                              |                  |   |              |                |              |             |               |   |             |               |   |
| 0x0004         | _ManufacturerName_                                           | Character String |   | 0 – 32 bytes |                | Read only    | Climax      | O             |   |             |               |   |
|                |                                                              | Technology       |   |              |                |              |             |               |   |             |               |   |
|                |                                                              |                  |   |              |                |              |             |               |   |             |               |   |
|                |                                                              |                  |   |              |                |              |             |               |   |             |               |   |
| 0x0005         | _ModelIdentifier_                                            | Character String |   | 0 – 32 bytes |                | Read only    | (Model      | O             |   |             |               |   |
|                |                                                              | Version)         |   |              |                |              |             |               |   |             |               |   |
|                |                                                              |                  |   |              |                |              |             |               |   |             |               |   |
| 0x0006         | _DateCode_                                                   | Character String |   | 0 – 16 bytes |                | Read only    |             | O             |   |             |               |   |
|                |                                                              |                  |   |              |                |              |             |               |   |             |               |   |
| 0x0007         | _PowerSource_                                                | 8-bit            |   | 0x00 –0xff   |                | Read only    |             | M             |   |             |               |   |
| 0x0010         | _LocationDescription_                                        | Character String |   | 0 – 32 bytes |                | Read /       |             | O             |   |             |               |   |
|                |                                                              | Write            |   |              |                |              |             |               |   |             |               |   |
|                |                                                              |                  |   |              |                |              |             |               |   |             |               |   |
| 0x0011         | _PhysicalEnvironment_                                        | 8-bit            |   | 0x00 –0xff   |                | Read /       | 0x00        | O             |   |             |               |   |
|                |                                                              | Write            |   |              |                |              |             |               |   |             |               |   |
|                |                                                              |                  |   |              |                |              |             |               |   |             |               |   |
| 0x0012         | _DeviceEnabled_                                              | Boolean          |   | 0x00 –0x01   |                | Read /       | 0x01        | M             |   |             |               |   |
|                |                                                              | Write            |   |              |                |              |             |               |   |             |               |   |
|                |                                                              |                  |   |              |                |              |             |               |   |             |               |   |
|                |  _**Attribute of Power Configuration Cluster Information**_ |                  |   |              |                |              |             |               |   |             |               |   |
|                |                                                              |                  |   |              |                |              |             |               |   |             |               |   |
| **Identifier** | **Name**                                                     | **Type**         |   |              | **Range**      |              |             | **Access**    |   | **Default** | **Mandatory** |   |
|                |                                                              |                  |   |              | **/ Optional** |              |             |               |   |             |               |   |
|                |                                                              |                  |   |              |                |              |             |               |   |             |               |   |
| 0x0035         | BatteryAlarmMask                                             | Bitmap (8-bits)  |   | 0000 - 000x  |                | Read / Write |             | 0000 0000     | O |             |               |   |
|                |                                                              |                  |   | 4            |                |              |             |               |   |             |               |   |

* _**Attribute of Identify Cluster Information**_

| **Identifier** | **Name**       | **Type** | **Range**    | **Access** | **Default** | **Mandatory** |   |
| -------------- | -------------- | -------- | ------------ | ---------- | ----------- | ------------- | - |
| **/ Optional** |                |          |              |            |             |               |   |
|                |                |          |              |            |             |               |   |
| 0x0000         | _IdentifyTime_ | Unsigned | 0x00 –0xffff | Read /     | 0x0000      | M             |   |
| 16-bit integer | Write          |          |              |            |             |               |   |
|                |                |          |              |            |             |               |   |

* _**Attribute of Thermostat Cluster Information**_

| **Identifier**   | **Name**                  | **Type**             | **Range**           | **Access** | **Default** | **Mandatory** |   |
| ---------------- | ------------------------- | -------------------- | ------------------- | ---------- | ----------- | ------------- | - |
| **/ Optional**   |                           |                      |                     |            |             |               |   |
|                  |                           |                      |                     |            |             |               |   |
| 0x0000           | _LOCAL\_TEMPERATURE_      | 16-bit               | 0x954d – 0x7fff     | Read       | 0x0000      | M             |   |
| only             |                           |                      |                     |            |             |               |   |
|                  |                           |                      |                     |            |             |               |   |
| 0x0003           | _MIN\_HEAT\_SETPOINT\_LI_ | 16-bit               | 0x954d – 0x7fff     | Read       | 0x01F4      | O             |   |
| _MIT_            | only                      |                      |                     |            |             |               |   |
|                  |                           |                      |                     |            |             |               |   |
| 0x0004           | _MAX\_HEAT\_SETPOINT\_LI_ | 16-bit               | 0x954d – 0x7fff     | Read       | 0x0DAC      | O             |   |
| _MIT_            | only                      |                      |                     |            |             |               |   |
|                  |                           |                      |                     |            |             |               |   |
|                  | _OCCUPIED\_HEATING\_SET_  |                      | _Min Heat Setpoint_ | Read /     |             |               |   |
| 0x0012           | 16-bit                    | _Limit_ – _Max Heat_ | 0x07D0              | M          |             |               |   |
| _POINT_          | Write                     |                      |                     |            |             |               |   |
|                  |                           | _Setpoint Limit_     |                     |            |             |               |   |
|                  |                           |                      |                     |            |             |               |   |
| 0x001B           | _CTRL\_SEQ\_OF\_OPER_     | 8-bit                | 0x00 – 0x05         | Read /     | 0x04        | M             |   |
| Enumeration      | Write                     |                      |                     |            |             |               |   |
|                  |                           |                      |                     |            |             |               |   |
| 0x001C           | _SYSTEM MODE_             | 8-bit                | 0x00 – 0x09         | Read /     | 0x04        | M             |   |
| Enumeration      | Write                     |                      |                     |            |             |               |   |
|                  |                           |                      |                     |            |             |               |   |
| 0x0020           | _START OF WEEK_           | 8-bit                | 0x00 – 0x06         | Read       | -           | O             |   |
| Enumeration      |                           |                      |                     |            |             |               |   |
|                  |                           |                      |                     |            |             |               |   |
| 0x0021           | _NUMBER OF WEEKLY_        | 8-bit                | 0x00 – 0xFF         | Read       | N/A         | O             |   |
| _TRANSITIONS_    | unsigned                  |                      |                     |            |             |               |   |
|                  |                           |                      |                     |            |             |               |   |
| 0x0022           | _NUMBER OF DAILY_         | 8-bit                | 0x00 – 0xFF         | Read       | N/A         | O             |   |
| _TRANSITIONS_    | unsigned                  |                      |                     |            |             |               |   |
|                  |                           |                      |                     |            |             |               |   |
| 0x0023           | _TEMPERATURE_             | 8-bit                | 0x00- 0x01          | Read/      | 0x00        | O             |   |
| _SETPOINT HOLD_  | enumeration               | Write                |                     |            |             |               |   |
|                  |                           |                      |                     |            |             |               |   |
|                  | _TEMPERATURE_             | 16-bit               |                     | Read/      |             |               |   |
| 0x0024           | _SETPOINT HOLD_           | 0xFFFF – 0x05A0      | 0xFFFF              | O          |             |               |   |
| unsigned         | Write                     |                      |                     |            |             |               |   |
|                  | _DURATION_                |                      |                     |            |             |               |   |
|                  |                           |                      |                     |            |             |               |   |
| 0x0025           | _PROGRAMMING_             | 8-bit bitmap         | 00xxxxxx            | Read/      | 00000000    | O             |   |
| _OPERATION MODE_ | Write                     |                      |                     |            |             |               |   |
|                  |                           |                      |                     |            |             |               |   |

5
