# VESTA-200

**DC-15SL-2W-F1**

## **Door Contact**&#x20;

The Door Contact monitors the opening/closing of specified devices (e.g. door or window). The Door Contact is fixed to the monitored device frame with an actuating magnet fixed to the device. When the door or window opens, the magnet moves away from the Door Contact, activating an internal magnetic switch causing the Door Contact to transmit alarm signal to the Central Panel. The device also has the capabilities of communicating signal problems along with low battery situations.

The Door Contact design consists of a cover and base. The cover contains all electronics and the base provides a means for fixing the device. An enclosed PCB tamper switch provides tamper protection against unauthorized device opening and/or removal.

The Door Contact is a two-way radio signal transmission device. When Door Contact is triggered but did not receive acknowledgement from the Control Panel, the Door Contact will resend signal to ensure the panel successfully receive notification.

## _**Parts Identification**_

1. **LED indicator / Test button**

&#x20;      Press the Test button to transmit learning code or enter test mode for 3 min.

2. **Mounting Holes**

<figure><img src=".gitbook/assets/1 (124).png" alt=""><figcaption></figcaption></figure>

Used to fixed and screw the Door Contact directly onto the Door Frame or Wall.

3. **Battery Insulator**
4. **Tamper Switch**

Provides tamper protection against unauthorized device opening and/or removal from mounting surface.

<figure><img src=".gitbook/assets/2 (134).png" alt=""><figcaption></figcaption></figure>

_**Internal Switch and Terminal**_

Loosen the bottom fixing screw and remove the cover to reveal terminal as shown.

5. **Extension Terminal**

In addition to the built-in magnet switch, an additional 2-pin dry contact terminal is provided for an extension magnet switch or any device with N.C. (Normally Closed) functionality.

**Jumper On** : The jumper link is inserted&#x20;

**Jumper Off: T**he jumper link is removed or “**parked**” on one pin.

![](<.gitbook/assets/1 (82).jpeg>) ![](<.gitbook/assets/2 (71).jpeg>)

6. **Internal Magnetic Switch Jumper Switch (JP3)**

* When the jumper is set as ON, the Internal Magnetic Switch is disabled. Only the device connected to Extension Terminal will activate the Door Contact
* When the jumper is set as OFF, the Internal Magnetic Switch is enabled.

**(Factory Default for all models)**

<figure><img src=".gitbook/assets/3 (120).png" alt=""><figcaption></figcaption></figure>

7. **Magnet**

* Mount the magnet on the side of the Door Contact where it has 2 rib-marks to indicate the position of the internal magnet switch. The Door Contact should be installed either upright or inverted to ensure that the rib-marked side faces the magnet.

8. **Magnet Screw hole**
9. **Magnet Spacer**

### _**Accessories Included**_

![](<.gitbook/assets/3 (67).jpeg>)

1. 1 Magnet and Magnet Spacer
2. White Caps
3. Screws
4. 2 Wall Plugs

### _**LED Indicator**_

* In Normal Operation Mode, the LED will not light when the Door Contact is activated.
* When the Door Contact battery voltage is low, every time the Door Contact is activated (device opened/ closed), the LED will light on for 2 sec.
* When the cover is opened or the tamper switch is triggered, the LED will light on for 2 seconds. When a tamper condition persists, the LED will light on for 2 seconds whenever the Door Contact Is activated.
* When the Door Contact is in Test mode, the LED will light up every time it is activated.
* When the battery is exhausted, the Door Contact will stop all function, the LED will flash every 4 seconds.

### _**Battery**_

* The Door Contact uses one **CR2, 3V Lithium battery** as its power source. Please note: **ALWAYS** replace battery with the correct size and voltage.
* The Door Contact can detect low battery condition. When the battery voltage is low, a low battery signal will be sent to the Control Panel to notify the condition. The LED will light up when the Door Contact is activated under low battery status. When the battery is exhausted, the Door Contact will stop all function, the LED will flash every 4 seconds.
* When changing batteries, after removing the old batteries, press the Tamper Switch twice to fully discharge before inserting new batteries.

### _**Supervisory Signal**_

* The Door Contact will automatically transmit Supervisory Signals periodically to the Control Panel at random intervals of 90-110 minutes.
* If the Control Panel has not received the signal from the Door Contact for a preset period time, the Control Panel will indicate the particular Door Contact is experiencing an out-of-signal problem.

### _**Test Mode**_

* Under Normal Mode, press the Test Button to transmit a test signal and learning code to the Control Panel. The Door Contact will also enter the Test Mode for 3 minutes.
* Under Test Mode, the LED will light up whenever the Door Contact is activated.
* Each additional Test Button press will reset Test Mode time to 3 minutes.

## _**Getting Started**_

* Pull out the battery insulator to activate battery.
* Put the Control Panel into Learning Mode (please refer to panel operation manual).
* Press the Door Contact test button.
* Refer to your Control Panel operation manual to complete the learn-in process.
* After the Door Contact is learned-in, place the Control Panel into (**Walk Test)** mode, hold the Door Contact in the desired location, and press the Test button to transmit test signal to Control Panel. If the Control Panel is within Door Contact signal range, the panel will display door contact information accordingly.
* Proceed with mounting and installation once you are satisfied that the Door Contact location functions properly.

### _**Mounting Methods and Installation**_

It is recommended that the Door Contact should be placed on the door/window frame and the magnet on the door/window.

Step 1: Find a suitable location close to your door/window to install the Door Contact. Conduct a Walk Test to check whether the position is in signal range of the Control Panel.

Step 2: The Door Contact has 2 rib-marks on one side (refer to figure), marking the internal magnet switch location. The door contact should be installed either upright or inverted, to ensure that the rib-marked side face the magnet.

Step 3: To mount the Door Contact:

1. Remove the white caps covering the two mounting holes.
2. Use the 2 mounting holes as a template for appropriate hole positioning.
3. Use the provided wall plugs for plaster/brick installation.
4. Screw the Door Contact into the provided wall plugs using a Philips screwdriver.
5. Replace the white caps to cover the two mounting holes.

{% hint style="warning" %}
Note:

Ensure the tamper switch spring is positioned so that it makes contact with the mounting surface through the tamper switch aperture.
{% endhint %}

![](<.gitbook/assets/4 (58).jpeg>)

Step 4: To mount the Magnet:

1. Use the 2 Magnet Screw holes as a template for appropriate hole positioning.

{% hint style="warning" %}
Note:

The magnet should not be more than 15 mm from the Door Contact when the door is closed.

The magnet must align with the rib-mark side of the Door Contact. If required, apply the magnet spacer to the back of the magnet to better align the magnet to the rib marks.
{% endhint %}

![](<.gitbook/assets/5 (44).jpeg>)

2. Screw the magnet onto the door.
3. Insert the two white caps into the magnet screw holes for aesthetic integrity.&#x20;

Step 5: Installation is now complete.

## _**Using the Extension Terminal**_

The Door Contact has an extension terminal to provide enhanced flexibility. The extension terminal forms a closed loop with the device connected to it. When the device is triggered, the loop will be opened; the Door Contact will also be triggered.

![](<.gitbook/assets/6 (55).jpeg>)

The extension terminal and the internal magnetic switch can function together to trigger the Door Contact when either of them is activated, you can also choose to disable the internal magnetic switch through JP3 Jumper setting.

To connect the device to extension terminal:

1. Open the Door Contact by loosening the fixing screw using a Philips screwdriver.
2. The upper end of the front case has a thinner plastic knockout. Break through the knockout to create a hole for the wiring connection to the extension terminal.
3. Connect the device to the extension terminal

The Extension terminal may be useful for the following situation.

* If the Door Contact cannot be mounted on the door frame, you can connect an additional extension switch to the extension terminal to mount the Door Contact remotely.
* Any dry contact device with N.C. (Normal Close) loop can be connected to the Extension Terminal making the Door Contact serve as an Universal Transmitter.
* Multiple dry contact device can be wired together with Door Contact, as show in diagram below.

![](<.gitbook/assets/7 (52).jpeg>) ![](<.gitbook/assets/8 (46).jpeg>)

{% hint style="warning" %}
Note:

**If both the Internal Magnet Switch and Extension Terminal operate together, then:**

When the protected door is opened/closed **or** the external device is triggered, the Door Contact activates and transmits a signal immediately .

However, the Door contact will only transmit a **Door Closed** or **Restored** signal after both the door **and** the external device are restored for 3 sec.
{% endhint %}
