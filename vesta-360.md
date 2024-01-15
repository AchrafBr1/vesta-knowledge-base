# VESTA 360

**Wired Door Contact / Shock Sensor (DCSV-29-BUS)**

DCSV-29-BUS is a Wired Door Contact / Shock Sensor that is capable of sending wired signals over BUS to the Control Panel upon detection of door/window opening or window glass break & shock detection.

The Wired Door Contact / Shock Sensor design consists of a cover and base. The cover contains all electronics and the base provides a means for fixing the device. An enclosed PCB tamper switch provides tamper protection against unauthorized device opening and/or removal.

**Parts Identification**

![](<.gitbook/assets/0 (3).png>)

1. **LED Indicator / Test Button**

\- Press the button once to enter test mode for 3 minutes.

1. **Cover Fixing Screw**
2. **Terminal Resistor Jumper Switch**

When the Door Contact / Shock Sensor is connected as the furthest BUS device on a BUS line, please set the Door Contact / Shock Sensor 's terminal resistor jumper and the first BUS device’s (usually the Hybrid Panel’s) Jumper Switch to ON to serve as terminating resistors. The connected BUS line’s communication ability will be enhanced.

![](<.gitbook/assets/1 (2).jpeg>) ![](<.gitbook/assets/2 (2).png>)

**Jumper On**

![](<.gitbook/assets/3 (2).jpeg>)

The jumper link is inserted, connecting the two pins.

**Jumper Off**

The jumper link is removed or “parked” on one pin.

*
  * If the jumper is ON, the communication ability is enhanced.
  * If the jumper is OFF, the communication ability is in normal level.

1. **BUS Terminal**
2. **Tamper Switch**
   * Provides tamper protection against unauthorized device opening and/or removal from mounting surface.
3. **Reed Switch Jumper Switch**

![](<.gitbook/assets/4 (3).jpeg>) ![](<.gitbook/assets/5 (5).png>)

**Jumper On**

![](<.gitbook/assets/6 (3).jpeg>)

The jumper link is inserted, connecting the two pins.

**Jumper Off**

The jumper link is removed or “parked” on one pin.

*
  * Jumper ON: Reed Switch is **enabled**. The device works as a Door Contact and a Shock Sensor (Factory Default).
  * Jumper OFF: Reed Switch is **disabled** and the device only works as a Shock Sensor.

1. **Mounting Holes**
2. **Wiring Holes**
3. **Magnet**
4. **Magnet Screw hole**
5. **Magnet Spacer**

1

**Features**

![](<.gitbook/assets/7 (2).jpeg>)

* _**LED Indicator**_
  * In Normal Operation Mode, the LED will not light up when the device is activated.
  * When the tamper switch is triggered, the LED will flash once. When the tamper condition continues, the LED will flash once whenever the device is triggered.
  * When under Test mode, the LED will flash once every time the device is triggered.
  * The LED will not flash if the device tamper is normal and the device is not under test mode.
* _**Door Opening Detection & Shock Detection**_

![](<.gitbook/assets/8 (1) (1).jpeg>)

The device is triggered by door/window opening or a shock detection which exceeds detection threshold.

![](<.gitbook/assets/9 (1).jpeg>)

* _**Materials of Mounting Surface**_

The device supports shock detection on various materials including glass, wood, metal, and concrete. After installation, you can select the material of the mounting surface on the Control Panel. The default is set as **Wood**.

![](<.gitbook/assets/10 (6).png>)

* _**Sensitivity**_
  * The sensitivity required to activate the Wired Door Contact / Shock Sensor is determined by the Control Panel.
  * Three sensitivity levels are selectable: **Low**, **Medium**, and **High**. The default is set as **Medium**.
* _**Power Supply**_
  * When DCSV-29-BUS is hardwired to a Hybrid Panel, 13.5V power supply can be provided by the Hybrid Panel.
* _**Tamper Protection**_
  * The Wired Door Contact / Shock Sensor is protected by a tamper switch which is depressed against the mounting surface when the Door Contact / Shock Sensor is mounted in place. Whenever the Wired Door Contact / Shock Sensor is removed from the mounting surface or its cover is opened, the tamper switch will be activated and the device will send a tamper open signal to remind the user of the condition.
  * The tamper open signal will be transmitted with the device’s regular signal transmission to the Control Panel. The tamper fault status will be displayed in the DC device zone and the Shock Sensor device zone on the Control Panel.
* _**Supervision**_
  * When in normal operation, the Wired Door Contact / Shock Sensor will send a supervision signal to the Control Panel separately at random intervals of 20-30 seconds.
  * If the Control Panel has not received the supervision signal from the Wired Door Contact / Shock Sensor for a preset period of time, the Control Panel will indicate that the particular Wired Door Contact / Shock Sensor is experiencing an out-of-signal problem.
* _**Test Mode**_
  * Under Normal Mode, press the Test Button to transmit a test signal to the Control Panel. The Wired Door Contact / Shock Sensor will enter the Test Mode for 3 minutes.
  * Under Test Mode, the LED will flash once whenever the Wired Door Contact / Shock Sensor is triggered.
  * Each additional press of the Test Button will reset the Test Mode time to 3 minutes.
* _**Caution**_
  *
    * Wiring of the Door Contact / Shock Sensor should only be performed by certified technicians with proper knowledge and training in electric equipment.
    * Before installation or any maintenance work, make sure the power supply has been disconnected.

![](<.gitbook/assets/11 (2).jpeg>) ![](<.gitbook/assets/12 (1).jpeg>) ![](.gitbook/assets/13.jpeg) ![](<.gitbook/assets/14 (1).jpeg>) ![](<.gitbook/assets/15 (3).jpeg>) ![](<.gitbook/assets/16 (6).png>)

2

* ![](<.gitbook/assets/17 (2).jpeg>)_**Door Contact / Shock Sensor Wiring**_
  * Before connecting the Wired Door Contact/Shock Sensor to the system’s BUS, please switch the power off.
  * To assist with cable connections, the terminal blocks on each BUS system module are color-coded.

![](.gitbook/assets/18.jpeg)

| **Red**    | VDD  |
| ---------- | ---- |
| **Black**  | GND  |
| **Yellow** | 485A |
| **Green**  | 485B |

* Multiple BUS devices can be connected in series to the Hybrid Panel.For optimal communication of the the connected BUS line devices, ensure the terminal resistor jumper switches of the first (usually the Hybrid Panel) and the furthest BUS devices on a BUS line are set to ON to serve as terminating resistors. Be sure to only enable the aforementioned 2 jumper switches, and do not set the jumper switches to ON for any other BUS devices in between.

_\<NOTE>_

*
  * The pluggable design of BUS terminal blocks improves upon installation efficiency. Before wiring, you can remove the terminal blocks from the PCB board for ease of use, and plug in again after wiring.
  * After unplugging the terminal, when re-installing the terminal back to the board, make sure to install the terminal in the same direction to avoid potential hazards.
* Incorrect connections will result in failure or improper operation. Inspect wiring and ensure proper connections before applying power.

![](<.gitbook/assets/19 (5).png>)

* _**Learning**_

Please follow the steps below to learn the device into the Hybrid Panel.

Step 1. Connect the device to the Panel. Then, power the Panel on.

Step 2. On the Panel’s webpage, click “**Learning**” to enter learn page.

Step 3. Click “**Start**” to enter learning mode.

_When learnt into the Control Panel, DCSV-29-BUS will be recognized as 2 separate devices (Door Contact & Shock Sensor) and will occupy 2 zones in the Panel._

Step 4. Click “**Add**” to include the device into the Panel.

3

Step 5. If the device is successfully learnt into the Panel, it will be displayed in the “Learned Device” section.

![](<.gitbook/assets/20 (1).jpeg>)

* _**Setting Material & Sensitivity Level**_

Step 1. Select the material and sensitivity level from the Control Panel webpage (Sensor Setting page).

Step 2. When DCSV-29-BUS receives the programming command from the Panel, the LED will first turn off, and then turn brighter and turn dark. Material & Sensitivity level setting are now complete.

* _**Identification**_

The “**Identify**” function is used to localize a specific BUS device in the BUS wired system. This function is helpful in distinguishing which device is which especially in a large installation where numerous devices are included.

To locate DCSV-29-BUS in the BUS system:

**Step 1.** On Hybrid Panel’s webpage, click “Identify” under the device list after the DCSV-29-BUS’s device column entry.

**Step 2.** If the Wired Door Contact / Shock Sensor receives the signal from the Hybrid Panel, the webpage will display a success message and Wired Door Contact / Shock Sensor’s LED indicator will flash 10 times to indicate where it is to the user.

_\<NOTE>_

*
  *
    * If a timeout message is displayed on the webpage, it means the Wired Door Contact / Shock Sensor did not receive the signal from the Panel.

Please check whether DCSV-29-BUS is connected properly to the Panel within appropriate wiring distance.

* _**Walk Test**_
  * To make sure the Wired Door Contact / Shock Sensor is able to communicate with the Panel after it is learned-in, place the Control Panel in Walk Test mode and press the Test button on DCSV-29-BUS to transmit a test signal to the Control Panel.
  * When the Panel receives the test signal, it will beep once and display the Wired Door Contact / Shock Sensor’s information accordingly on the top of the device list.

_\<NOTE>_

* If there is no response from the Panel after the press of test button, it means the Panel did not receive the test signal from the device.

Please check whether DCSV-29-BUS is connected properly to the Panel within appropriate wiring distance.

**Installation**

* _**Mounting the Wired Door Contact / Shock Sensor**_

**Mounting as a Door Contact:**

* The Door Contact should be installed with the rib-marked side facing the magnet.
* The distance between the Door Contact and the magnet should be no more than 15 mm when the door is closed.
* Mount the device as high as possible.

4

**Mounting as a Shock Sensor:**

Refer to the table below for information about installation location and the thickness of different materials:

|                           |               |                      | Glass Window | Wood/Metal Door | Concrete Wall |   |
| ------------------------- | ------------- | -------------------- | ------------ | --------------- | ------------- | - |
|                           |               |                      |              |                 |               |   |
|                           | **Thickness** | >5mm                 | <40mm        | -               |               |   |
|                           |               |                      |              |                 |               |   |
| **Installation Location** | Window Frame  | Door                 | Wall         |                 |               |   |
|                           |               |                      |              |                 |               |   |
|                           |               | **Low Sensitivity**  | 0.5M         | 0.5M            | 0.25M         |   |
| **Shock Detection**       |               |                      |              |                 |               |   |
| **Medium Sensitivity**    | 1M            | 1M                   | 0.5M         |                 |               |   |
| **Radius**                |               |                      |              |                 |               |   |
|                           |               |                      |              |                 |               |   |
|                           |               | **High Sensitivity** | 1.5M         | 2M              | 1M            |   |
|                           |               |                      |              |                 |               |   |

* _**Mounting Procedure**_
  1. Use the 2 mounting holes on back cover as a template and drill holes into the surface to be mounted.
  2. Insert the provided wall plugs when the device is to be mounted on window frames / concrete wall.
  3. Screw the Wired Door Contact / Shock Sensor onto the wall plugs. (Drilling is recommended when mounting on steel, or you can also use the provided sticker in the package).
  4. Fit the magnet on the door using small piece of double sided adhesive tape or with provided screws.
  5. To mount the magnet, use the 2 magnet screw holes as a template for hole positioning and drilling. _\<NOTE>_
     * The magnet must align with the rib-mark side of the Door Contact. If required, apply the magnet spacer to the back of the magnet to better align the magnet to the rib marks.
  6. Screw the magnet and insert the two white caps into the magnet screw holes for aesthetic integrity.
  7. Installation is now complete.

5
