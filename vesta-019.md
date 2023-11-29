# VESTA 019

Door Contact (DC-23 / DC-23-R3) User Manual

The Door Contact monitors the opening/closing of specified devices (e.g. door or window). The Door Contact is fixed to the monitored device frame with an actuating magnet fixed to the device. When the door or window opens, the magnet moves away from the Door Contact, activating an internal magnetic switch causing the Door Contact to transmit alarm signal to the Central Panel. The device also has the capabilities of communicating signal problems along with low battery situations.

The Door Contact design consists of a cover and base. The cover contains all electronics and the base provides a means for fixing the device. An enclosed PCB tamper switch provides tamper protection against unauthorized device opening and/or removal.

DC-23 Series Door Contact includes following models:

DC-23: Door Contact cover is secured by a bottom fixing screw.

DC-23-R3: Door Contact cover is secured by two latches at top and bottom

![](<.gitbook/assets/0 (3).jpeg>)

Parts Identification

1. **LED indicator / Test button**

Press the Test button to transmit learning code or enter test mode for 3 min.

1. **Mounting Holes**

Used to fixed and screw the Door Contact directly onto the Door Frame or Wall.

1. **Tamper Switch**

When Door Contact is mounted, the Tamper switch will be activated when the cover is opened or when the Door Contact is removed from mounted surface.

1. **Battery Insulator**
2. **Supervision Jumper Switch (JP2)**

**(**_**868WF model only**_**)**

**Jumper Off**

if the jumper link is removed or “**parked**” on one pin.

**Jumper On**

The jumper link is inserted, connecting the two pins

![jumper close](<.gitbook/assets/1 (10).png>) ![jumper open](<.gitbook/assets/2 (11).png>)

* Jumper ON: Supervision disabled
* Jumper OFF: Supervision enabled. **(Factory Default)**

1. **Reed Switch Jumper Switch (JP3)**

![jumper close](<.gitbook/assets/3 (10).png>) ![jumper open](<.gitbook/assets/4 (10).png>)

**Jumper On**

The jumper link is inserted, connecting the two pins

**Jumper Off**

if the jumper link is removed or “**parked**” on one pin.

* Jumper ON: Reed Switch disabled. Only the device connected to Extension Terminal will activate the Door Contact
* Jumper OFF: Reed Switch enabled. **(Factory Default for all models)**

1. **Extension Terminal**

In addition to the built-in magnet switch, an additional 2-pin dry contact terminal is provided for an extension magnet switch or any device with N.C. (Normally Closed) functionality.

1. ![](<.gitbook/assets/5 (7).png>)**Battery Compartment**
2. **Magnet**
3. **Magnet Screw hole**
4. **Magnet Spacer**

Features

* _**LED Indicator**_
* In Normal Operation Mode, the LED will not light when the Door Contact is activated.
* When the Door Contact battery voltage is low, every time the Door Contact is activated (device opened/ closed), the LED will light on for 2 sec.
* When the cover is opened or the tamper switch is triggered, the LED will light on for 2 seconds. When a tamper condition persists, the LED will light on for 2 seconds whenever the Door Contact Is activated.
* When the Door Contact is in Test mode, the LED will light up every time it is activated.
* When the battery is exhausted, the Door Contact will stop all function, the LED will flash every 4 seconds.
* _**Extension Terminal**_

The Door Contact has an extension terminal to provide enhanced flexibility. The extension terminal forms a closed loop with the device connected to it. When the device is triggered the loop is opened, the Door Contact will also be triggered.

The extension terminal and the internal magnetic switch can function together to trigger the Door Contact when either of them is activated, you can also choose to disable the internal magnetic switch through JP3 Jumper setting.

To connect the device to extension terminal:

![](<.gitbook/assets/6 (4).jpeg>)**For DC-23 model:**

1. Open the Door Contact’s cover by using a screwdriver to loosen the cover fixing screw at the bottom of the Door Contact’s cover. (See picture below picture from upper view angle).
2. The upper end of the front case has a thinner plastic knockout. Break through the knockout to create a hole for the wiring connection to the extension terminal.
3. Connect the device to the extension terminal

**For DC-23-R3 model:**

1. ![](<.gitbook/assets/7 (3).jpeg>)Use your thumb to press on the Latch, while pressing it, pull out the cover from the base of the Door Contact (see below picture from upper view angle).
2. The upper end of the front case has a thinner plastic knockout. Break through the knockout to create a hole for the wiring connection to the extension terminal.
3. Connect the device to the extension terminal

The Extension terminal may be useful for the following situation.

* If the Door Contact cannot be mounted on the door frame, you can connect an additional extension magnet switch to the extension terminal to mount the Door Contact remotely.
* Any dry contact device with N.C. (Normal Close) loop can be connected to the Extension Terminal making the Door Contact serve as an Universal Transmitter.
* Multiple dry contact device can be wired together with Door Contact, as show in diagram below.

![](<.gitbook/assets/8 (2).png>)

* The extension terminal and internal magnetic switch can function together to trigger the Door Contact when either of them is activated, you can also choose to disable the internal magnetic switch through JP3 Jumper setting. If both extension terminal and internal magnetic switch is in use and any of them is triggered (opened). The Door Contact will only send Door Contact close (restore) signal when both of them are closed.
* _**Battery**_
* The Door Contact is powered by one CR123 3V Lithium battery. Please note: **ALWAYS** replace battery with the correct size and voltage.
* The Door Contact can detect low battery condition. When the battery voltage is low, a low battery signal will be sent to the Control Panel to notify the condition. The LED will light up when the Door Contact is activated under low battery status. When the battery is exhausted, the Door Contact will stop all function, the LED will flash every 4 seconds.
* When changing battery, after removing the old batteries, press the Tamper Switch twice to fully discharge before inserting new battery.
* _**Tamper Protection**_
* The Door Contact is protected by a tamper switch which is compressed against the mounting surface when the Door Contact is mounted. Whenever the Door Contact cover is opened, or removed from mounted surface, the tamper switch will be activated and the Door Contact will send a tamper open signal to remind the user of the condition.
* _**Supervisory Signal**_
* Supervision function for 868WF model is controlled by JP2 jumper setting. For non-868WF model, supervision function is always enabled.
* When enabled, the Door Contact will automatically transmit Supervisory Signals periodically to the Control Panel at random intervals of 30-50 minutes.
* If the Control Panel has not received the signal from the Door Contact for a preset period time, the Control Panel will indicate the particular Door Contact is experiencing an out-of-signal problem.
* _**Test Mode**_
* Under Normal Mode, press the Test Button to transmit a test signal and learning code to the Control Panel. The Door Contact will also enter the Test Mode for 3 minutes.
* Under Test Mode, the LED will light up whenever the Door Contact is activated.
* Each additional Test Button press will reset Test Mode time to 3 minutes.
* _**Getting Started**_
* Open the cover of the Door Contact and insert the battery.
* Put the Control Panel into Learning Mode (please refer to panel operation manual).
* Press the Door Contact test button.
* Refer to your Control Panel operation manual to complete the learn-in process.
* After the Door Contact is learned-in, place the Control Panel into (**Walk Test)** mode, hold the Door Contact in the desired location, and press the Test button to transmit test signal to Control Panel. If the Control Panel is within Door Contact signal range, the panel will display door contact information accordingly.
* Proceed with mounting and installation once you are satisfied that the Door Contact location functions properly.

Installation

* _Installation Guideline_
* The Door Contact should be installed on the door/window frame, and the magnet on the door/window
* The distance between the Door Contact and the magnet should be no more than 15mm when the door is closed.
* Avoid mounting the Door Contact on metallic surface. If mounting on metallic surface, make sure to test whether the Door Contact can be triggered when the door is opened.
* Mount the Door Contact as high as possible.
* _**Mounting the Door Contact**_

1. Find a suitable location close to your door/window to install the Door Contact.
2. The Door Contact has 2 rib-marks on one side (refer to figure), marking the internal magnet switch location. The door contact should be installed either upright or inverted to ensure that the rib-marked side faces the magnet.
3. To mount the Door Contact:
4. Use the 2 Door Contact mounting holes as a template for appropriate hole positioning.
5. Use the provided wall plugs for plaster/brick installation.
6. Screw the Door Contact into the provided wall plugs.
7. To mount the Magnet:
8. Use the 2 Magnet Screw holes as a template for appropriate hole positioning.

< Note >

* The magnet should not be more than 15 mm from the Door Contact when the door is closed.
* The magnet must align with the rib-mark side of the Door Contact. If required, apply the magnet spacer to the back of the magnet to better align the magnet to the rib marks.

1. Screw the magnet onto the door.
2. Insert the two white caps into the magnet screw holes for aesthetic integrity.
3. Installation is now complete.

![](<.gitbook/assets/9 (4).png>)

FCC Statement

This device complies with Part 15 of the FCC Rules. Operation is subject to the following two conditions:

(1) This device may not cause harmful interference, and

(2) This device must accept any interference received, including interference that may cause undesired operation.

FCC Caution:

To assure continued compliance, any changes or modifications not expressly approved by the party responsible for compliance may void the user's authority to operate this equipment. (Example - use only shielded interface cables when connecting to computer or peripheral devices).
