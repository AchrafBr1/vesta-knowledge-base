# VESTA 167

**Shutter Control (SCM-5ZW)**

**Introduction**

SCM-5ZW is a Z-Wave Shutter Control. The user can control the SCM via Z-Wave network at a remote distance or manually by linking a switch to the SCM.

Automatically or remotely roll up, down or stop mid-way, the SCM-5ZW is directly connected to and controls motorized window treatments, interior and exterior shades and blinds, projection screen, and garage door or driveway gate of your home.

The Shutter Control is compatible only with Z-Wave Gateway/Control Panel. Z-Wave is a wireless communication protocol that uses a low-power RF radio. By taking advantage of the Z-Wave mesh network, commands can be routed to their destination via intermediary “listening” Z-Wave products.

![](<.gitbook/assets/0 (69).jpeg>)

**Parts Identification**

1. **LED indicator**
   * Power ON: LED flashes twice.
   * Successful Learning: LED flashes 3 times.
   * Factory Reset: LED flashes twice.
2. **Function Button**
   * Press the function button and the Shutter Control will send a multilevel report.
   * Press the function button 3 times within 1.5 seconds to include or exclude the Shutter Control in/from Z-Wave network.
   * Press and Hold Function button for 10 seconds to reset.
3. **Power input N (Neutral Lead) connection cable (Blue)**
4. **Power Input L (Live Lead) connection cable (Brown)**
5. **Local Switch S2 (Down Direction) connection cable (Orange)**

If SCM is connected according to _**Installation**_ below, the shutter will roll down for 4 minutes after the switch is activated.

Activating this switch when the shutter is rolling up will stop the shutter.

**6. Local Switch S1 (Up Direction) connection cable (Red)**

If SCM is connected according to _**Installation**_ below, the shutter will roll up for 4 minutes after the switch is activated.

Activating this switch when the shutter is rolling down will stop the shutter.

**7. Motor Output O1 (Up Direction) connection cable (Yellow)**

Connect to the Up terminal of the Shutter Motor.

**8. Motor Output O2 (Down Direction) connection cable (Green)**

Connect to the Down terminal of the Shutter Motor.

**Specification**

* Power Supply: 110 - 230VAC, 50/60Hz
* Supported Load Current: 1/4 HP (Horse power); 1.8Amps for motors with compensated power factor (inductive loads)
* Communication Protocol: Z-Wave Plus 500 series module

![](<.gitbook/assets/1 (64).jpeg>)

**Caution**

* All works on the device, including installation and maintenance, must be performed by a qualified and licensed electrician.
* Before installation or any maintenance work, make sure the power supply has been disconnected.
* Do not connect the device to loads exceeding supported load current.
* Please connect the device to AC powered motor only.

1

**Features**

* _**Adding Device (Inclusion)**_

This product can be included and operated in any Z-Wave network with other Z-Wave certified devices from other manufactures and/or other applications. All non-battery operated nodes within the network will act as repeaters regardless of vendor to increase reliability of the network.

*
  * Connect the power to Shutter Control (see manual’s **Installation**).
  * Put the Z-wave gateway or control panel into **Inclusion mode** (please refer to the Z-wave gateway or control panel manual).
  * Within 1.5 seconds, press the Function Button 3 times.
  * Refer to the operation manual of the Z-wave gateway or control panel to complete the adding process.
  * If the device has already been added (included) into another Z-wave Gateway/Control Panel, or if the device is unable to be added into the current Z-wave Gateway/Control Panel, try removing it first (see _**Removing Device**_).
* _**Removing Device (Exclusion)**_

The device must be removed from existing Z-wave network before being added into another.

**Exclusion Mode**

* Put the Z-wave gateway or control panel into **Exclusion mode** (please refer to the Z-wave gateway or control panel manual).
* Within 1.5 seconds, press the Function Button 3 times and the device will be removed from the Z-wave network.

**Factory Reset**

_(Only use factory reset when network Control Panel/Gateway is missing or inoperable)._

Factory resetting the device will restore it to factory default settings (i.e. not included into any Z-wave network).

*
  * Press and hold the Function Button of the device for 10 seconds to factory reset.
* _**Range Test**_

To test whether the device is able to communicate with the Z-wave gateway or control panel:

* Put the gateway/panel into range test mode (Walk Test).
* Press the Function Button on the device.
* The gateway/panel should display if the device is within the operation range (please refer to the operation manual of the gateway / panel).

**Installation**

* _**Wiring with Splicing Connector**_
  * SCM-5 comes with embedded terminal wires and clamps (Wago 221 Splicing Connectors).
  * The 2-wire connectors accommodate solid and stranded wires from 0.2 to 4 mm² (24–12 AWG).
  * Please connect SCM-5 to AC power, local switches, and shutter motor with the connectors.
  * Before wiring, please make sure the power is off. To connect the wires:
    1. Lift the lever and insert the wire. **(Picture 1, 2)**

**Picture1** **Picture 2**

![](<.gitbook/assets/2 (68).png>)

1. Push the lever back down. The transparent housing allows you to check if the wire is connected properly. Make sure the wire is held in place tightly and won't come off. **(Picture 3, 4)**

2

**Picture 3** **Picture 4**

![](<.gitbook/assets/3 (67).png>)

*
  1. In the same way as step 1 & 2, connect the other wires with connectors.
* SCM-5 should be connected according to the diagram below:

![](<.gitbook/assets/4 (45).jpeg>)

* Connect N terminal of SCM to the N terminal of Power Supply.
* Connect L terminal of SCM to the L terminal of Power Supply.
* Connect O1 terminal of SCM to the Open terminal of the Shutter Motor.
* Connect O2 terminal of SCM to the Close terminal of the Shutter Motor.
* **(Optional local switch)** Connect S2 and S1 terminals of SCM to the L terminal of Power Supply.

**Operation**

* _**Shutter Control**_
  * **Manual Control**

If an optional Local Switch is connected, the user can press and hold the button on the up/down Local Switch (S1 up; S2 down) for 1 second to control the shutter. When activated, the shutter will roll up/down. When the shutter is rolling, the user can stop the shutter by pressing the opposite direction button.

*
  * **Z-Wave Network**

After the Shutter Control has been successfully included in a Z-Wave network, the Z-Wave controller can control the shutter with Z-wave command Switch Binary Set or Switch Multilevel Set, using parameters below:

*
  *
    * Value: 0x00\~0x63 (0%\~99%, 0% = Full Close, 99% = Full Open)
    * Dimming Duration : 0x00
  * As each up/down movement starts, the Multilevel Switch Start level Change Command is sent to initiate the transition to the new level. While the SCM is in motion, you can send Multilevel Switch Stop Level Change Command to stop the SCM.

3

* _**Calibration**_
  * The Shutter Control default activation time is **4** minutes.

When the Up/Down button is pressed, it will activate the shutter motor for 4 minutes.

When a Z-Wave command is received from Z-Wave controller, it will determine the shutter travel percentage using 4 minutes as basis for calculation.

*
  * For the Shutter Control to work properly, its activation time must be calibrated according to actual shutter travel distance. There are two ways to adjust the activation time:
    * **Manual Calibration:** Calibrate the activation according to procedure below:
      1. Before calibration, the external local switches must be connected to the Shutter Control.
      2. Press and hold the Function button for 3 seconds and release to enter Calibration mode. The Shutter motor will roll up for 4 minutes when the Shutter Control enters Calibration mode.
      3. Wait for 4 minutes for Shutter motor to stop rolling, and then press “Down” button to roll down the shutter. (If the shutter reached the open position less than 4 minutes, you can press the “Down” button to stop the shutter motor. Then press the “Down” button again to roll down the shutter.)
      4. As soon as the shutter is fully closed, press the “Up” button. The Shutter control will record the time it took for the shutter to roll from open to close as the new “**close time**”.
      5. After the “Up” button is pressed the moment the shutter is fully closed, the shutter will roll up towards the open direction.
      6. Press the “Down” button the moment the shutter is fully opened. The Shutter control will record the time it took for the shutter to roll from close to open as the new “**open time**”.
      7. The Shutter Control will send a multilevel report (0x63), with its current value, target value, and/or duration, to the controller whenever its level changed.
    * For Example, if it takes the shutter 30 seconds to move from “Up” to “Down” position, its new close time will be 30 seconds. After calibration, whenever the “Down” button is pressed, the shutter will roll down for 30 seconds.
    * If it takes the shutter 40 seconds to move from “Down” to “Up” position, its new open time will be 40 seconds. After calibration, whenever the “Up” button is pressed, the shutter will roll up for 40 seconds.
    * **Z-Wave Command:** Besides manual calibration, users can also adjust the activation time by sending command from the Z-Wave Controller with Configuration CC command, using parameters below:

| **Setting**        | **Parameter Number** | **Size** | **Value**      | **Default**      |
| ------------------ | -------------------- | -------- | -------------- | ---------------- |
| Open Time Setting  | 0x01                 | 0x02     | 0x0000\~0x00F0 | 0x00F0 (240 sec) |
|                    |                      |          | (sec)          |                  |
|                    |                      |          |                |                  |
| Close Time Setting | 0x02                 | 0x02     | 0x0000\~0x00F0 | 0x00F0 (240 sec) |
|                    |                      |          | (sec)          |                  |
|                    |                      |          |                |                  |
| Current Position   | 0x03                 | 0x02     | 0x0000\~0x0063 | 0x0063 (99%)     |
|                    |                      |          | (%)            | Full Open        |
|                    |                      |          |                |                  |

* Parameter Number : 0x01\~0x03
  * For parameter 1, users can set the open time (from down to up) to a value that ranges from 0 to 255 seconds.
  * For parameter 2, users can set the close time (from up to down) time to a value that ranges from 0 to 255 seconds.
  * For parameter 3, users can set the current position to a value that ranges from %0 to %99.
* Size: 0x02. This filed is used to specify the size of the actual value.
* Configuration Value : 0x0000\~0x00F0 (seconds)
* The shutter control will start movement upon receiving Z-wave command Switch Binary Set or Switch Multilevel Set, and the movement will be executed based on current position setting.

Example for Configuration Setting:

| Parameter Number | Size | Value |               |
| ---------------- | ---- | ----- | ------------- |
|                  |      |       |               |
| 01               | 02   | 0064  | (100 seconds) |
|                  |      |       |               |
| 02               | 02   | 0064  | (100 seconds) |
|                  |      |       |               |
| 03               | 02   | 0032  | (50%)         |
|                  |      |       |               |

SWITCH\_MULTILEVEL\_SET: 0x00 (0%)

SCM will roll down (from up to down) for 50 seconds: (100/100)\*(100-50)

* The activation time will be reset to **4** minutes whenever the Shutter Control is included in Z-Wave network, or when it is factory reset.

_**\<NOTE>:**_ The Shutter Control’s default Current Position is set to 99% (Full Open). It is recommended to fully open the shutter before calibrating with Z-Wave command, otherwise please also re-adjust the Current Position setting with command.

4

* _**Z-Wave Information**_

**Generic Device Class:** SWITCH\_MULTILEVEL

**Specific Device Class:** CLASS\_C\_MOTOR\_CONTROL

**Role Type:** SLAVE\_ALWAYS\_ON

**Command Class Support/Control**

**Mandatory CC Support:**

Z-Wave Plus Info CC

Transport Service CC

Security\_2 CC

Supervision CC

Switch Binary (S2)

Switch Multilevel CC (S2)

Association Group Information CC (S2)

Device Reset Locally CC (S2)

Configuration CC (S2)

Manufacturer Specific CC, V2 (S2)

Power level CC (S2)

Firmware Update Md CC, V4 (S2)

Association CC, V2 (S2)

Version CC, V2 (S2)

Multi Channel Association CC, V3 (S2)

* _**Z-Wave’s Groups (Association Command Class Version 2)**_

_**Group 1 for “LifeLine”: (maximum node x 1)**_

Switch Multilevel CC, (COMMAND\_CLASS\_SWITCH\_MULTILEVEL)

\#.SWITCH\_MULTILEVEL\_REPORT

\#.SWITCH\_MULTILEVEL\_START\_LEVEL\_CHANGE

\#.SWITCH\_MULTILEVEL\_STOP\_LEVEL\_CHANGE

Device Reset Locally CC, (COMMAND\_CLASS\_DEVICE\_RESET\_LOCALLY)

* When SCM begins to move, it will send \[SWITCH\_MULTILEVEL\_START\_LEVEL\_CHANGE]
* When SCM stops moving, it will send \[SWITCH\_MULTILEVEL\_STOP\_LEVEL\_CHANGE]
* Whenever SCM changes its position, it will send \[SWITCH\_MULTILEVEL\_REPORT]

5
