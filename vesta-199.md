# VESTA-199

**D**_**C-16SL**_

## **Door Contact**

<figure><img src=".gitbook/assets/image (406).png" alt=""><figcaption></figcaption></figure>

The Door Contact monitors the opening/closing of specified devices (e.g. door or window). The Door Contact is fixed to the monitored device frame with an actuating magnet fixed to the device. When the door or window opens, the magnet moves away from the Door Contact, activating an internal magnetic switch causing the Door Contact to transmit alarm signal to the Control Panel. The device also has the capabilities of communicating signal problems along with low battery situations.

The Door Contact design is consisted of a cover and base. The cover contains all electronics and the base provides a means for fixing the device. An enclosed PCB tamper switch provides tamper protection against unauthorized device opening and/or removal.

**The Door Contact includes the following frequency models:**

**433AM**

**433FM F1**

**868WF**

**868FM**

**868FM F1**

**869FM**

**869F1**

## _**Identifying the parts**_

![](<.gitbook/assets/1 (71).png>)

1. **LED Indicator**
2. **Learn / Test Button**

&#x20;      \- Press the Test button to transmit a learn code.

&#x20;      \- Press the Test button once to enter Test Mode for 3 minutes.

3. **Supervision Jumper Switch (JP2)**

**Jumper On:** The jumper link is inserted&#x20;

![](<.gitbook/assets/2 (70).jpeg>)

**Jumper Off:** the jumper link is removed or “**parked**” on one pin

![](<.gitbook/assets/3 (66).jpeg>)

~~-~~ When the jumper is set as ON, the Supervision is disabled. **(Factory default for 433AM)**

\- When the jumper is set as OFF, the Supervision is enabled.**(Factory default for 868WF, 868FM, 869FM, models)**

_**433FM-F1, 868FM-F1 and 869-F1 models do not have this Jumper installed and Supervision is alwas enabled**_

4. **Battery**
5. **Cover Securing Screw Hole**
6. **Knockouts**
7. **Tamper Switch**
8. **Battery Insulator hole**
9. **Rib Marks**
10. **Magnet**

&#x20;     \- Mount the magnet on the side of the Door Contact where it has 2 rib-marks to indicate the position of the internal magnet switch. The Door Contact should be installed either upright or inverted to ensure that the rib-marked side faces the magnet.

11. **Magnet Screw hole**
12. **Magnet Spacer**

### _**Accessories Included**_

1. 1 Magnet
2. 2 Screws
3. 1 double-sided adhesive pad
4. 2 Wall Plugs
5. 2 Magnet mounting screws
6. 1 Magnet Spacer
7. 2 White Caps

### _**LED Indicator**_

In Normal operation mode, the LED indicator remains off except in the following situations:

* When the Door Contact’s tamper switch is triggered.
* Every time when the Door Contact is activated with either Tamper or Low battery condition.
* Every time when the Door Contact is activated and transmitting the signal under the Test mode.

### _**Supervision**_

* If enabled, the Door Contact will automatically transmit Supervisory signals periodically to the Control Panel at random intervals of 30 to 50 minutes in Normal Operation Mode.
* If the Control Panel has not received the signal from the Door Contact for a preset period time, the Control Panel will indicate that particular Door Contact is experiencing an out-of-signal problem.

### _**Tamper Switch**_

* It is designed to protect against unauthorized removal from mounted location, cover opening or unsteady installation. When the tamper is triggered, Door Contact will emit a signal to the Control Panel for reporting, the LED will also light up.

### _**Battery**_

The Door Contact uses one **3V CR2 Lithium battery** as its power source, it is also capable of detecting low battery. When the battery is low, a low battery signal will be sent to the Control Panel along with regular transmission. The LED will light up when the Door Contact is activated under low battery status. When battery is exhausted, the Door Contact will stop all function and the LED will flash every 4 seconds.

### **Changing Battery:**

After the battery has been removed, press the Learn / Test button 5-6 times to fully discharge before inserting the new battery.

{% hint style="warning" %}
Note:

Due to the battery characteristic, after inserting a new battery in the Door Contact, it will self-check whether this battery is working properly or not within 16 minutes after the insertion.
{% endhint %}

### _**Test Mode**_

The Door Contact can be put into Test mode for 3 minutes by pressing the Test Button on the front cover once. During Test mode, the LED indicator will turn on upon triggering. Each press on the Test Button, the Door Contact will transmit a test signal to the Control Panel for radio range test and resets the test mode back to the 3-minute duration. It will exit Test Mode automatically after the 3 minutes and returns to Normal Operation mode.

## _**Getting Started**_

Step 1: Pull out the battery Insulator steadily

Step 2: Put the Control Panel into learning mode, refer to Control Panel manual for detail.

Step 3: Press the Test Button on Door Contact to send signal to the Control Panel.

Step 4: If the Control Panel successfully receives the signal, the Control Panel should respond (e.g. emitting beeps). Refer to your Control Panel manual to complete the learning process.

Step 5: After the Door Contact is learnt-in, put the Control Panel into “**Walk Test**” mode, hold the Door Contact at the desired location, and press the Test button to confirm if this location is within signal range of the Control Panel.

Step 6: When you are satisfied with the Door Contact at the chosen location, proceed to installation.

### _**Installation**_

Step 1: Mount the Door Contact using one of the methods below.

Step 2: Mount the magnet on the more mobile object (such as door) using the screws provided.

Align the magnet according the rib mark on Door Contact.

Where required, use the Magnet Spacer to better align the magnet to the rib marks.

{% hint style="warning" %}
Note:

The magnet should be no more than **15mm** from the detector when the door is closed.

The two white caps provided can be inserted into the magnet screw holes for aesthetic integrity.
{% endhint %}

### _**Mounting Methods**_

There are two ways to mount the Door Contact: Self-adhesive mounting or Screw mounting.

![](<.gitbook/assets/15 (19).jpeg>)

* **Self-adhesive Mounting**

1. The mounting surface should be clean, dry, and smooth. Clean the mounting surface with a suitable degreaser if needed.
2. Remove the protective covering from one side of the double-sided adhesive pad. Apply to the back of the device and press firmly for 30 seconds to ensure good contact.
3. Remove the other cover and firmly press the Door Contact onto the desired location for 30 seconds.

{% hint style="warning" %}
Note:

Do not use the adhesive pad method of installation on a surface with peeling or cracked paint, or on a rough surface.

Please do not re-apply the 3M adhesive tape. It cannot be reused

Please install the Door Contact on the more stationary object (such as door frame or window frame) and mount the magnet on the more mobile object (such as door or window).
{% endhint %}

* **Screw Mounting**

The Base has two knockouts, where the plastic is thinner, for mounting purpose. To mount the Door Contact:

1. Remove the cover by unscrewing the Cover Securing Screw using a Philips screwdriver.

![](<.gitbook/assets/17 (18).jpeg>)

2. Break through the knockout on the base.
3. Using the holes as a template, drill both holes.
4. Insert wall plugs if fixing into plaster or brick.
5. Screw the base into the wall plug using a Philips screwdriver.
6. Attach the cover to the base and tighten the Cover Securing Screw.
