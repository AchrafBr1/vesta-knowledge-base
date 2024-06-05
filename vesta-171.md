# VESTA 171

**TRV-1ZW Thermostatic Radiator Valve**

**Introduction**

TRV-1ZW is a Z-Wave Radiator Valve is designed to control the surrounding temperature by controlling the flow of hot water of radiators in the Z-Wave network, i.e. indoor room temperatures.

The Radiator Valve is a Z-Wave enabled device and is fully compatible with any Z-Wave enabled network.

Z-Wave is a wireless communication protocol that uses a low-power RF radio. By taking advantage of the Z-Wave mesh network, commands can be routed to their destination via intermediary “listening” Z-Wave products.

**Parts Identification**

1. **Valve Cap**
2. **LCD Display**

![](<.gitbook/assets/0 (62).png>) ![](<.gitbook/assets/1 (67).jpeg>)

1. ![](<.gitbook/assets/2 (56).jpeg>) **ON** when device is already added into Z-Wave network.
2. ![](<.gitbook/assets/3 (53).jpeg>) **Low Battery Indicator.**
3. ![](<.gitbook/assets/4 (47).jpeg>) On: Device set to default temperature 17 °C.

![](<.gitbook/assets/5 (35).jpeg>) Flash: Valve closing.

![](<.gitbook/assets/6 (47).jpeg>) On: Device set to default temperature 21 °C.

![](<.gitbook/assets/7 (45).jpeg>) Flash: Valve opening.

1. **Auto / Manual Mode.**
2. **Boost function.**
3. **Open Window**.
4. **Temperature Indicator.**

![](<.gitbook/assets/8 (47).png>)

**Others: InS**: When power on device (also for learning period).

**AdA:** device motor working.

**F1/F3:** the valve is jammed, **F2:** no valve installed.

**3. Function Buttons**

\-**Manual/Auto:** Enter Manual or Auto mode.

\-**Boost/ Z-Wave:** Speed up heating process/add into Z-Wave network.

\- ![](<.gitbook/assets/9 (24).jpeg>) Press this button to instantly switch day and night temperatures.

_**Default day**_ ![](<.gitbook/assets/10 (18).jpeg>) _temperature: 21_ °C_, **Default night**_ ![](<.gitbook/assets/11 (22).jpeg>) _temperature: 17_ °C

1. **Temperature Sensor**
2. **Control Knob**

Adjust temperature manually.

**6. Battery Compartment**

The Radiator Valve is powered by two 1.5V AA alkaline batteries.

1

**Features**

![](<.gitbook/assets/12 (38).png>)

* _**Battery**_

The Radiator Valve uses two 1.5V AA alkaline batteries as power source. The Radiator Valve will report its battery percentage to the Gateway/Control Panel respectively at 100%, 75%, 50%, 25%. If the battery voltage is low (25%), a Low Battery signal will be sent to the Gateway/Control Panel to notify the user.

The Radiator Valve can detect if the battery is low. When low battery voltage is detected, a low battery signal

will be sent to the Z-Wave Gateway/Control Panel with the LCD will display ![](<.gitbook/assets/13 (21).jpeg>) icon to notify the user.

![](<.gitbook/assets/14 (26).png>)

* _**Power ON / Manual / Auto mode**_

**Power ON**: When the Radiator Valve powers on, it’s motor starts working with LCD displaying **InS**, device is ready for installation and start learning process. (see **Installation** for details)

**Manual Mode:** In the Manual mode, you can use the following functions:

* ![](<.gitbook/assets/15 (17).jpeg>) button: switch day/night temperatures instantly.
* **Boost button:** Speed up heating / Adding device into Z-Wave Gateway or Control Panel.
* **Control Knob**: Control temperature, set to ON (summer season mode) and OFF (winter season mode).

**Auto Mode:** The Auto mode is only available when device is learned with a control panel. After learning with the Control Panel you can control and set the time schedule for the Radiator Valve automatically through the control panel (please refer to your control panel manual for details).In the Auto Mode, you can use the same functions as in Manual mode except the Control Knob Set to ON and OFF function.

![](<.gitbook/assets/16 (29).png>)

* _**Anti-frosting**_

When the Radiator Valve detects a frosting hazard, it will automatically open the valve for hot water to flow in order to maintain the temperature and to prevent further frosting.

![](<.gitbook/assets/17 (22).png>)

* _**Anti-calcification**_

The Radiator Valve will open and close the valve weekly to prevent calcification. During anti-calcification process the LCD will display a **CAL**.

The default value for anti-calcification process is 23:00p.m every Saturday.

![](<.gitbook/assets/18 (24).png>)

* _**Boost Function**_

Press and hold the Boost button for 3 seconds to temporarily speed up heating process by further opening the valve. The boost function lasts 5 minutes (LCD displays: 300 seconds countdown). If you wish to cancel boost function, press and hold the button for 3 seconds again.

![](<.gitbook/assets/19 (25).png>)

* _**Setpoint Offset**_

The device is usually installed at the corner of the room and near the heating pipe. As a result its temperature reading may deviate from room temperature at center of room. Use the setpoint Offset function to compensate the deviation.

To calculate setpoint offset, simply subtract room temperature with device temperature.

Example: If device temperature is 20°C and room temperature is 18°C, then setpoint offset =18 – 20= -2°C.

After setpoint offset is applied, the device will operate according to adjusted temperature.

For example: If device temperature reading is 20°C, setpoint offset is -2°C, the device will operate using 18°C as actual reference.

To program setpoint Offset:

*
  1. Press and hold the ![](<.gitbook/assets/20 (11).jpeg>) button for 3 seconds to enter offset adjustment.
  2. Rotate the Control Knob to desired offset temperature.
  3. Press any key to finish and exit offset adjustment.
* _**Open Window**_

If Radiator Valve detects indoor temperature drops rapidly by opening the window, the Radiator Valve will activate Open Window function by partly closing the valve to reduce temperature setting for 15 minutes. The

LCD will display symbol, the device will check the temperature every minute. After 15 minutes, the Radiator Valve will return to the set temperature with valve opening again, Open Window Function closes.

* _**Control Knob**_

Rotate the Control Knob to adjust the temperature, rotate clockwise to reduce temperature and anti-clockwise to increase the temperature. The adjustable temperature range is 5°C to 30°C. If you rotate the Control Knob lower than 5°C to On, after 1 minute, the Radiator Valve will open the valve completely, to preserve battery power, if you rotate the Control Knob lower than 5°C to Off, after 1 minute, the Radiator Valve will close the valve completely. To disable ON/Off status please rotate the control knob or press

button . The Boost Function is unavailable under Control Knob set to ON/Off status.

**ON:** When turned to ON, the valve is opened completely. This function is used to preserver battery life during summer, when heating is not required. Do not use this function in winter when heater is activated,

2

otherwise the room temperature will rise uncontrolled.

**OFF:** When turn to OFF, the valve is closed completely. This function is used when heater is activated but heating is not required in a room with no occupants.

* _**Key Lock Function**_

Press and hold both Auto/Manual button and  button for 3 seconds to enable key lock function. If

successful the LCD will display  symbol. All keys and Control Knob actions will not respond**.** If you wish

to cancel key lock function, please press and hold both Auto/Manual button and button for 3 seconds likewise.

* _**Remote Control**_

After the Radiator Valve joins a Z-Wave network, you can control the Radiator Valve via Z-Wave network coordinator or gateway. Please refer to your Z-Wave coordinator/gateway manual for more information. The following functions are only available for setting via Z-Wave coordinator and gateway:

*
  * **Schedule:**

You can only program Schedule configuration via Z-Wave network coordinator/gateway.

Schedule Setting: Up to 5 schedules can be programmed for every weekday with Mode, Setpoint and Start time.

Schedule Control:

Normal - The Radiator Valve will execute programmed schedule setting accordingly.

No Schedule – The Radiator Valve will not execute any set schedule until it is set to Normal again.

* _**Adding Device (Inclusion)**_

This product can be included and operated in any Z-Wave network with other Z-Wave certified devices from other manufactures and/or other applications. All non-battery operated nodes within the network will act as repeaters regardless of vendor to increase reliability of the network.

* Remove the Radiator Valve back cover and insert 2 AA Alkaline batteries to power up the Radiator

Valve, LCD will display **InS** and  icon will flash to indicate Radiator Valve’s motor is working.

* Put Z-Wave control panel into **Inclusion mode** (please refer to the Z-Wave control panel manual).
* Within 1.5 seconds, press the Boost Button 3 times
* Refer to operation manual of the Z-Wave gateway or control panel to complete the adding process.
* If the device has already been added (included) into another Z-Wave Gateway/Control Panel, or if the device is unable to be added into the current Z-Wave Gateway/Control Panel, try removing it first (see _**Removing Device**_).
* When the motor stops working and  icon changes to steady on, attach the Valve cap to the pipe.
* Rotating the Valve cap clockwise to tighten the Radiator Valve.
*
* _**Removing Device (Exclusion)**_

The device must be removed from existing Z-Wave network before being added into another. **Exclusion Mode**

* Put the Z-Wave gateway or control panel into **Exclusion mode** (please refer to the Z-Wave or control panel manual).

3

*
  * Within 1.5 seconds, press Boost Button 3 times and device will be removed from Z-Wave network.

**Factory Reset**

Factory resetting the device will restore it to factory default settings (i.e. not included into any Z-Wave network). Please only use this procedure if the Z-Wave gateway or control panel is lost or otherwise inoperable.

*
  * Press and hold the Boost Button for 10 seconds to factory reset.
* _**Range Test**_

To test whether the device is able to communicate with the Z-Wave gateway or control panel:

*
  * Put the gateway / panel into range test mode (Walk Test).
  * Press and hold the Boost Button for one second.
  * The gateway / panel should display if the device is within the operation range (please refer to the operation manual of the gateway / panel).
* _**Z-Wave Sleep Mode**_
  * The Radiator Valve will enter Z-Wave Sleep mode (to conserve power) after waking up for a short period of time (\~10 seconds). While in Z-Wave sleep mode, Z-Wave gateways or control panels are unable to send commands to the Radiator Valve.
  * To program the Radiator Valve using the Z-Wave Gateway/Control Panel, please send command(s) to the Radiator Valve within the wake-up period.
* _**Configuration Set Command**_
  * The Radiator Valve allows the user to set open-delay and close-delay values. The default value is 2 minutes (max: 5 minutes).
  * If 4 minutes is set for open-delay, the device will send an operate-state open report 4 minutes after the valve is opened. If 4 minutes is set for close-delay, the valve will be closed 4 minutes after an operate-state close report is sent.
  * The valve also features periodic status report; the default value is 60 minutes. The timer will be reset whenever operate-state is changed.
  * The Configuration Set Command is used to set the value of a configuration parameter:

| 7                             |                                  | 6                           |                                             | 5    |                            | 4                     |   | 3 |   | 2         |   |      | 1 |   | 0 |
| ----------------------------- | -------------------------------- | --------------------------- | ------------------------------------------- | ---- | -------------------------- | --------------------- | - | - | - | --------- | - | ---- | - | - | - |
|                               |                                  |                             | Command Class=COMMAND\_CLASS\_CONFIGURATION |      |                            |                       |   |   |   |           |   |      |   |   |   |
|                               |                                  |                             |                                             |      | Command=CONFIGURATION\_SET |                       |   |   |   |           |   |      |   |   |   |
|                               |                                  |                             |                                             |      |                            | Parameter Number      |   |   |   |           |   |      |   |   |   |
| Default                       |                                  |                             |                                             |      | Reserved                   |                       |   |   |   |           |   | Size |   |   |   |
|                               |                                  |                             |                                             |      |                            | Configuration Value 1 |   |   |   |           |   |      |   |   |   |
|                               |                                  |                             |                                             |      |                            |                       | … |   |   |           |   |      |   |   |   |
|                               |                                  |                             |                                             |      |                            | Configuration Value N |   |   |   |           |   |      |   |   |   |
|                               |                                  |                             |                                             |      |                            |                       |   |   |   |           |   |      |   |   |   |
| COMMAND\_CLASS\_CONFIGURATION |                                  | Parameter Number            |                                             | Size |                            | Value                 |   |   |   |           |   |      |   |   |   |
|                               |                                  |                             |                                             |      |                            |                       |   |   |   |           |   |      |   |   |   |
|                               |                                  | Setpoint\_offset            |                                             |      |                            | 0                     |   |   |   |           | 2 | 0000 |   |   |   |
|                               |                                  |                             |                                             |      |                            |                       |   |   |   |           |   |      |   |   |   |
|                               | Operate State Open Report Delay  |                             | 1                                           |      |                            |                       |   | 1 |   | 2 (mins)  |   |      |   |   |   |
|                               |                                  |                             |                                             |      |                            |                       |   |   |   |           |   |      |   |   |   |
|                               | Operate State Close Report Delay |                             | 2                                           |      |                            |                       |   | 1 |   | 2 (mins)  |   |      |   |   |   |
|                               |                                  |                             |                                             |      |                            |                       |   |   |   |           |   |      |   |   |   |
|                               |                                  | Operate State Period Report |                                             | 3    |                            |                       |   |   | 1 | 60 (mins) |   |      |   |   |   |
|                               |                                  |                             |                                             |      |                            |                       |   |   |   |           |   |      |   |   |   |

* Setpoint Offset Value : 0x0064 = 100 = 1.00℃.

**Z-Wave Information**

**Device Type:** Thermostat

**Role Type:** Listening Sleeping Slave (LSS)

**Command Class Support/Control**

**Mandatory CC Support:** Association CC, v2 or newer

Association Group Information CC

Battery CC

Device Reset Locally CC

Manufacturer Specific CC

Power Level CC

Version CC, v2 or newer

Z-Wave Plus Info CC

Thermostat mode CC

Thermostat Setpoint CC

Schedule CC

4

Sensor Multilevel CC

Time CC

Firmware Update Metadata CC

Thermostat Operating State CC

* _**Z-Wave’s Groups (Association Command Class Version 2)**_

Group 1 for “LifeLine”:

Battery Report CC

Device Reset Locally CC (COMMAND\_CLASS\_DEVICE\_RESET\_LOCALLY)

Thermostat mode CC

Thermostat Setpoint CC

Sensor Multilevel CC

Group 2 for “Thermostat Operating State”

Thermostat Operating State CC

* Factory Reset

When the Radiator Valve is reset to factory default, it will send Device Reset Locally to all nodes in Group 1.

5
