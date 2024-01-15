# VESTA 359

**Wired Door Contact (DC-23-BUS) User Manual**

DC-23-BUS is a Wired Door Contact that monitors the opening/closing of specified devices (e.g., door or window). The Wired Door Contact is fixed to the monitored device frame with an actuating magnet fixed to the device. When the door or window opens, the magnet moves away from the Wired Door Contact, activating an internal magnetic switch causing the Wired Door Contact to transmit alarm signals over BUS to the Control Panel.

With a built-in extension terminal, DC-23-BUS can also be connected to a wired device to double as a universal transmitter.

The Wired Door Contact design consists of a cover and base. The cover contains all electronics and the base provides a means for fixing the device. An enclosed PCB tamper switch provides tamper protection against unauthorized device opening and/or removal.

**Parts Identification**

![](<.gitbook/assets/0 (2).jpeg>)

1. **LED indicator / Test button**

Press the Test button to enter test mode for 3 minutes.

1. **Cover Fixing Screw**
2. **Input Jumper Switch (JP2)**

![](<.gitbook/assets/1 (3).png>)

**Jumper On** **Jumper Off**

![](<.gitbook/assets/2 (3).jpeg>) ![](<.gitbook/assets/3 (1) (1).jpeg>)

The jumper link is inserted, connecting the two The jumper link is removed or “**parked**” on one

pins. pin.

*
  * Jumper ON: Normally Closed (N.C.) is set.
  * Jumper OFF: Normally Open (N.O.) is set **(Factory Default)**.

1. **Terminal Resistor Jumper Switch**

When the Door Contact is connected as the furthest BUS device on a BUS line, please set the Door Contact 's terminal resistor jumper and the first BUS device’s (usually Hybrid Panel’s) Jumper Switch to ON to serve as terminating resistors. The connected BUS line’s communication ability will be enhanced.

![](<.gitbook/assets/4 (2).png>)

**Jumper On**

The jumper link is inserted, connecting the two pins.

**Jumper Off**

The jumper link is removed or “**parked**” on one pin.

*
  * If the jumper is ON, the communication ability will be enhanced.
  * If the jumper is OFF, the communication ability is in normal level.

1. **Bus Terminal**
2. **Extension Terminal**

In addition to the built-in magnet switch, an additional 2-pin dry contact terminal is provided for an extension magnet switch or any devices with the N.C. (Normally Closed) or N.O. (Normally Open) functionality.

1. **Tamper Switch**

When the Wired Door Contact is mounted, the Tamper switch will be activated when the cover is opened or when the Wired Door Contact is removed from the mounting surface.

1. **Mounting Holes**

Used to fix and screw the Door Contact directly onto the door frame or the wall.

1

1. **Breakaway Area for Wiring Holes (for Bus Terminal)**
2. **Magnet**
3. **Magnet Screw Hole**
4. **Magnet Spacer**

**Features**

![](<.gitbook/assets/5 (4).png>)

* _**LED Indicator**_
  * In Normal Operation Mode, the LED will not light up when the Wired Door Contact is activated.
  * When the Wired Door Contact’s cover is opened or the tamper switch is triggered, the LED will flash 3 times. When the tamper condition continues, the LED will flash 3 times whenever the Wired Door Contact Is activated.
  * When the Wired Door Contact is in test mode, the LED will flash 3 times every time it is activated.
* _**Extension Terminal**_

![](<.gitbook/assets/6 (2).png>)

DC-23-BUS has an extension terminal to provide enhanced flexibility. According to the setting of JP2, the extension terminal forms a closed (Normally Closed (N.C.)) or open (Normally Open (N.O.)) loop with the device connected to it. When the device connected to the extension terminal is triggered, the Wired Door Contact will be triggered.

| To connect the device to the extension terminal: | _**Top View of DC-23-BUS**_ |   |
| ------------------------------------------------ | --------------------------- | - |
|                                                  |                             |   |

![](<.gitbook/assets/7 (1).jpeg>)

1. Open the Wired Door Contact’s cover with a screwdriver by loosening the cover fixing screw at the bottom of the device.
2. The upper end of the front case has a thinner plastic knockout. Break through the knockout to create a hole for the wiring connection to the extension terminal.
3. Connect the device to the extension terminal.

![](<.gitbook/assets/8 (1).jpeg>)

The extension terminal may be useful for the following situations:

* If the Wired Door Contact cannot be mounted on the door frame, you can connect an additional extension magnet switch to the extension terminal to mount the Door Contact remotely.
* Any dry contact devices with an N.C. (Normal Closed) or N.O. (Normally Open) loop can be connected to the extension terminal making the Wired Door Contact serve as a Universal Transmitter.
* Multiple dry contact devices can be wired together with the Wired Door Contact, as shown in the picture below.

![](<.gitbook/assets/9 (5).png>)

* _**Power Supply**_
  * When DC-23-BUS is hardwired to a Hybrid Panel, 13.5V power supply can be provided by the Hybrid Panel.
* _**Tamper Protection**_
  * The Wired Door Contact is protected by a tamper switch which is compressed against the mounting surface when the Wired Door Contact is mounted in place. Whenever the Wired Door Contact cover is opened or removed from the mounting surface, the tamper switch will be activated and the Wired Door Contact will send a tamper open signal to remind the user of the condition.
* _**Supervisory Signal**_
  * The Wired Door Contact will automatically transmit Supervisory Signals periodically to the Control Panel at random intervals of 20-30 seconds.
  * If the Control Panel has not received the signal from the Wired Door Contact for a preset period time, the Control Panel will indicate that the particular Door Contact is experiencing an out-of-signal problem.
* _**Test Mode**_
  * Under Normal Mode, press the Test Button to transmit a test signal to the Control Panel. The Wired Door Contact will enter the Test Mode for 3 minutes.
  * Under Test Mode, the LED will flash 3 times whenever the Wired Door Contact is activated.
  * Each additional Test Button press will reset the Test Mode period to 3 minutes.

![](<.gitbook/assets/10 (5).png>) ![](<.gitbook/assets/11 (3).png>) ![](<.gitbook/assets/12 (4).png>)

2

* ![](<.gitbook/assets/13 (5).png>)_**Caution**_
  * Wiring of the Door Contact should only be performed by certified technicians with proper knowledge and training in electric equipment.
  * Before installation or any maintenance work, make sure the power supply has been disconnected.
* _**Door Contact Wiring**_
  *
    * Before connecting the Wired Door Contact to the system BUS, please switch the power off.
    * To assist with cable connections, the terminal blocks on each BUS system module are color-coded.

![](<.gitbook/assets/14 (4).png>) ![](<.gitbook/assets/15 (2).jpeg>)

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
* Incorrect connections will result in failure or malfunction. Inspect wiring and ensure proper connections before applying power.

![](<.gitbook/assets/16 (5).png>)

* _**Learning**_

Please follow the steps below to learn the device into the Hybrid Panel.

Step 1: Connect the device to the Panel. Then, power the Panel on.

Step 2: On the Panel’s webpage, click “**Learning**” to enter learn page.

Step 3: Click “**Start**” to enter learning mode.

Step 4: Click “**Add**” to include the device into the Panel.

Step 5: If the device is successfully learnt into the Panel, it will be displayed in the “Learned Device” section.

* When learnt into the Panel, DC-23-BUS will be recognized as 2 separate devices and will occupy 2 zones in the Panel.

![](<.gitbook/assets/17 (3).png>)

3

![](<.gitbook/assets/18 (5).png>)

* To differentiate the 2 separate devices, it is advised to rename the device name by

clicking “Edit” under the device list after the device column entry.

As shown on the Device Edit page, the ID with the last two digits of “**00**” represents the internal magnetic switch.

![](<.gitbook/assets/19 (4).png>)

The ID with the last two digits of “**02**” represents the extension terminal.

![](<.gitbook/assets/20 (4).png>)

* _**Identification**_

The “Identify” function is used to localize a specific BUS device in the BUS wired system. This function is helpful in distinguishing which device is which especially in a large installation where numerous BUS devices are included.

To locate the Wired Door Contact in the BUS system:

**Step 1.** On Hybrid Panel’s webpage, click “Identify” under the device list after the DC-23-BUS’s device column entry.

**Step 2.** If the Wired Door Contact receives the signal from the Hybrid Panel, the webpage will display a success message and the Wired Door Contact’s LED indicator will flash 10 times to indicate where it is to the user.

_\<NOTE>_

*
  *
    * If a timeout message is displayed on the webpage, it means the Wired Door Contact did not receive the signal from the Panel.

Please check whether DC-23-BUS is connected properly to the Panel within appropriate wiring distance.

* _**Walk Test**_
  * To make sure the Wired Door Contact is able to communicate with the Panel after it is learned-in, place the Control Panel in Walk Test mode and press the Test button on DC-23-BUS to transmit a test signal to the Control Panel.
  * When the Panel receives the test signal, it will beep once and display the Wired Door Contact’s information accordingly on the top of the device list.

_\<NOTE>_

* If there is no response from the Panel after the press of test button, it means the Panel did not receive the test signal from the device.

Please check whether DC-23-BUS is connected properly to the Panel within appropriate wiring distance.

**Installation**

* _**Installation Guideline**_
  * The Wired Door Contact should be installed on the door/window frame, and the magnet on the door/window
  * The distance between the Wired Door Contact and the magnet should be no more than 15mm when the door is closed.
  * Avoid mounting the Wired Door Contact on metallic surfaces. If mounted on metallic surfaces, make sure to test whether the Wired Door Contact can be triggered when the door is opened.
  * Mount the Wired Door Contact as high as possible.
* _**Mounting the Wired Door Contact**_

1. Find a suitable location close to your door/window to install the Wired Door Contact.
2. The Wired Door Contact has 2 rib-marks on one side (refer to figure), marking the internal magnet switch location. The Wired Door Contact should be installed either upright or inverted to ensure that the rib-marked side faces the magnet.
3. To mount the Wired Door Contact:
   *
     1. Use the 2 mounting holes as a template and drill holes into the frame to be mounted.
     2. Use the provided wall plugs for plaster/brick installation.
     3. Screw the Door Contact into the provided wall plugs.
4. To mount the Magnet:
   1. Use the 2 magnet screw holes as a template and drill holes into the door/window to be mounted.

* _NOTE >_
  * The magnet should not be more than 15 mm from the Wired Door Contact when the door is closed.
  * The magnet must align with the rib-mark side of the Wired Door Contact. If required, apply the magnet spacer to the back of the magnet to better align the magnet to the rib marks.
  * Screw the magnet onto the door/window.
  * Insert the two white caps into the magnet screw holes for aesthetic integrity.

1. Installation is now complete.

4
