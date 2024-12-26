# VESTA 019N



## JUMPER CONFIGURATION



<figure><img src=".gitbook/assets/image (2) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1).png" alt=""><figcaption><p>Jumper config</p></figcaption></figure>

{% hint style="success" %}
**JP6: Door Contact or External Input Mode**

* JP OFF: Door contact mode
* JP ON: External input mode

**JP5: NO/NC Mode**

* JP OFF: NO (Normally Open)
* JP ON: NC (Normally Closed)
{% endhint %}



**Door Contact (DC-23 / DC-23-R3) User Manual**

The Door Contact monitors the opening/closing of specified devices (e.g., doors or windows). The Door Contact is fixed to the monitored device frame with an actuating magnet fixed to the device. When the door or window opens, the magnet moves away from the Door Contact, activating an internal magnetic switch causing the Door Contact to transmit alarm signals to the Control Panel. The device also has the capabilities of communicating signal problems along with low battery situations.

The Door Contact’s design consists of a cover and a base. The cover contains all electronics and the base provides a means for fixing the door contact. An enclosed PCB tamper switch provides tamper protection against unauthorized device opening and/or removal.

DC-23 Series Door Contact includes the following models:

DC-23: Door Contact’s cover is secured by a bottom fixing screw.

DC-23-R3: Door Contact’s cover is secured by two latches at top and the bottom.

![](<.gitbook/assets/0 (39).png>)

**Parts Identification**

1. **LED indicator / Test button**

Press the Test button to transmit a learning code or enter test mode for 3 min.

1. **Mounting Holes**

Used to fix and screw the Door Contact directly onto the door frame or the wall.

1. **Tamper Switch**

When the Door Contact is mounted, the Tamper switch will be activated when the cover is opened or when the Door Contact is removed from the mounting surface.

1. **Battery Insulator**

6- The jumper link is removed or “**parked**” on one pin.

* Jumper ON: Reed Switch disabled. Only the device connected to Extension Terminal will activate the Door Contact
* Jumper OFF: Reed Switch enabled **(Factory Default for all models)**.

1. **Extension Terminal**

In addition to the built-in magnet switch, an additional 2-pin dry contact terminal is provided for an extension magnet switch or any device with N.C. (Normally Closed) functionality.

1. **Battery Compartment**
2. **Magnet**
3. **Magnet Screw hole**
4. **Magnet Spacer**

![](<.gitbook/assets/7 (25).jpeg>)

1

**Features**

![](<.gitbook/assets/8 (19).jpeg>)

* _**LED Indicator**_
  * In Normal Operation Mode, the LED will not light up when the Door Contact is activated.
  * When the Door Contact’s battery voltage is low, every time the Door Contact is activated (device opened/ closed), the LED will light up for 2 sec.
  * When the cover is opened or the tamper switch is triggered, the LED will light up for 2 seconds. When the tamper condition continues, the LED will light up for 2 seconds whenever the Door Contact Is activated.
  * When the Door Contact is in test mode, the LED will light up every time it is activated.
  * When the battery is exhausted, the Door Contact will stop all functions, and the LED will flash every 4 seconds.
* _**Extension Terminal**_

![](<.gitbook/assets/9 (10).jpeg>)

The Door Contact has an extension terminal to provide enhanced flexibility. The extension terminal forms a closed loop with the device connected to it. When the device is triggered with the loop opened, the Door Contact will also be triggered. The extension terminal and the internal magnetic switch can function together to trigger the Door Contact when either of them is activated, you can also choose to disable the internal magnetic switch through JP3 Jumper setting.

To connect the device to extension terminal:

**For DC-23 model:**

![](<.gitbook/assets/10 (10).jpeg>)

1. Open the Door Contact’s cover with a screwdriver to loosen the cover fixing screw at the bottom of the Door Contact’s cover (see the top-view picture on the right).
2. The upper end of the front case has a thinner plastic knockout. Break through the knockout to create a hole for the wiring connection to the extension terminal.
3. Connect the device to the extension terminal

**For DC-23-R3 model:**

1. Use your thumb to press on the Latch, while pressing it, pull out the cover from the base of the Door Contact (see the top-view picture on the right).
2. The upper end of the front case has a thinner plastic knockout. Break through the knockout to create a hole for the wiring connection to the extension terminal.
3. Connect the device to the extension terminal

![](<.gitbook/assets/11 (13).jpeg>)

The extension terminal may be useful for the following situation.

* If the Door Contact cannot be mounted on the door frame, you can connect an

additional extension magnet switch to the extension terminal to mount the Door Contact remotely.

* Any dry contact devices with an N.C. (Normal Close) loop can be connected to the extension terminal making the Door Contact serve as a Universal Transmitter.
* Multiple dry contact devices can be wired together with Door Contact, as shown in the picture below.

![](<.gitbook/assets/12 (9).jpeg>)

*
  *
    * The extension terminal and internal magnetic switch can function together to trigger the Door Contact when either of them is activated; you can also choose to disable the internal magnetic switch through JP3 Jumper setting. If both the extension terminal and internal magnetic switch are in use and any of them is triggered (opened), a trigger signal will be sent to the Control Panel. The Door Contact will only send a Door Contact close (restore) signal when both of them are closed.
* _**Battery**_
  * The Door Contact is powered by one CR123 3V Lithium battery. Please note: **ALWAYS** replace the battery with the correct size and voltage.
  * The Door Contact can detect low battery conditions. When the battery voltage is low, a low battery signal will be sent to the Control Panel to indicate the condition. The LED will light up when the Door Contact is activated under the low battery status. When the battery is exhausted, the Door Contact will stop all functions, and the LED will flash every 4 seconds.

![](<.gitbook/assets/13 (7).jpeg>)

2

*
  * When changing the battery, after removing the used battery, press the Tamper Switch twice to fully discharge before inserting a new battery.
* _**Tamper Protection**_
  * The Door Contact is protected by a tamper switch which is depressed against the mounting surface when the Door Contact is mounted in place. Whenever the Door Contact cover is opened or removed from the mounting surface, the tamper switch will be activated and the Door Contact will send a tamper open signal to remind the user of the condition.
* _**Supervisory Signal**_
  * Supervision function for 868WF model is controlled by JP2 jumper setting. For non-868WF model, supervision function is always enabled.
  * When enabled, the Door Contact will automatically transmit supervisory signals periodically to the Control Panel at random intervals of 30-50 minutes.
  * If the Control Panel has not received the signal from the Door Contact for a preset period time, the Control Panel will indicate the particular Door Contact is experiencing an out-of-signal problem.
* _**Test Mode**_
  * Under Normal Mode, press the test button to transmit a test signal and a learning code to the Control Panel. The Door Contact will also enter the Test Mode for 3 minutes.
  * Under Test Mode, the LED will light up whenever the Door Contact is activated.
  * Each additional test button press will reset Test Mode period to 3 minutes.
* _**Getting Started**_
  * Open the cover of the Door Contact and insert the battery.
  * Put the Control Panel in Learning Mode (please refer to the panel’s user manual).
  * Press the Door Contact’s test button.
  * Refer to your Control Panel’s user manual to complete the learn-in process.
  * After the Door Contact is learned-in, place the Control Panel in (**Walk Test)** mode, hold the Door Contact at a desired location, and press the test button to transmit a test signal to the Control Panel. If the Control Panel is within the Door Contact signal range, the panel will display the door contact information accordingly.
  * Proceed with mounting and installation once you are satisfied that the Door Contact functions properly at the desired location.

![](<.gitbook/assets/14 (10).jpeg>) ![](<.gitbook/assets/15 (7).jpeg>) ![](<.gitbook/assets/16 (7).jpeg>) ![](<.gitbook/assets/17 (7).jpeg>)

**Installation**

![](<.gitbook/assets/18 (7).jpeg>)

* _**Installation Guideline**_
  * The Door Contact should be installed on the door/window frame, and the magnet on the door/window
  * The distance between the Door Contact and the magnet should be no more than 15mm when the door is closed.
  * Avoid mounting the Door Contact on metallic surfaces. If mounting on metallic surface is required, make sure to test whether the Door Contact can be triggered when the door is opened.
  * Mount the Door Contact as high as possible.
* _**Mounting the Door Contact**_

![](<.gitbook/assets/19 (3).jpeg>)

1. Find a suitable location close to your door/window to install the Door Contact.
2. The Door Contact has 2 rib-marks on one side (refer to the picture below), marking the internal magnet switch location. The door contact should be installed either upright or inverted to ensure that the rib-marked side faces the magnet.
3. To mount the Door Contact:
   1. Use the 2 Door Contact mounting holes as a template for appropriate hole positioning.
   2. Use the provided wall plugs for plaster/brick installation.
   3. Screw the Door Contact into the provided wall plugs.
4. To mount the Magnet:
5. Use the 2 magnet screw holes as a template for appropriate hole positioning.

_< NOTE >_

*
  *
    * The magnet should not be more than 15 mm from the Door Contact when the door is closed.
    * The magnet must align with the rib-mark side of the Door Contact. If required, apply the magnet spacer to the back of the magnet to better align the magnet to the rib marks.
  * Screw the magnet onto the door.
  * Insert the two white caps into the magnet screw holes for aesthetic integrity.

![](<.gitbook/assets/20 (15).png>)

3

5\. Installation is now complete.

FCC Statement

This device complies with Part 15 of the FCC Rules. Operation is subject to the following two conditions:

1. This device may not cause harmful interference, and
2. This device must accept any interference received, including interference that may cause undesired operation.

FCC Caution:

To assure continued compliance, any changes or modifications not expressly approved by the party responsible for compliance may void the user's authority to operate this equipment. (Example - use only shielded interface cables when connecting to computer or peripheral devices).

4
