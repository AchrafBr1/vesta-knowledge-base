# VESTA-220

**GDC-3**

## **Z-Wave Garage Door Control**

<figure><img src=".gitbook/assets/image (128).png" alt=""><figcaption><p><a href="https://bydemes.com/es/productos/intrusion/alarma-vesta/dispositivos-z-wave/VESTA-220">VESTA-220</a></p></figcaption></figure>

## **Introduction**

VESTA-220 is a Z-Wave Garage Door Control that connects to the garage door opener. After joining a Z-Wave network, GDC-3 can receive commands through the Z-Wave network to activate the connected garage door opener, providing convenient operation for remotely opening or closing the garage door.

GDC-3 also includes a Garage Door Tilt Sensor (Tilt-GDC3) that can be installed on a tilt-up garage door, or a Garage Door Contact (DC-16SL-GDC3 / DC-32-EX-GDC3) that can be used on a horizontally opening garage door to report the status of the garage door when the garage door is “open” or “closed.”

Before the activated garage door begins to move, the warning LEDs on GDC-3 will flash and the built-in siren will emit alarm beeps.

Z-Wave is a wireless communication protocol that uses low-power RF radio. The Z-Wave Garage Door Control allows access to the “S2 Unauthenticated” class and supports Z-Wave SmartStart inclusion as well as classic inclusion.

## **Parts Identification**

**GDC-3 (Garage Door Control)**

![](<.gitbook/assets/0 (99).jpeg>)

1. **Green LED indicator**
   * **On**: Connected to power supply.
   * **Flashes with Red LED for 5 seconds:** Before the garage door moves.
2. **Red LED indicator**
   * **Flashes once every second:** In Learning Mode for Tilt-GDC3.
   * **Flashes once every 5 seconds:** Tilt-GDC3 low in battery
   * **Flashes with Green LED for 5 seconds:** Before the garage door moves.
3. **Function Button**
   * Press the button 3 times within 1 second to include or exclude the device in/from the Z-Wave network.
   * Press and hold the button for 10 seconds to factory reset.
   * Press the button once to open/close the garage door.
4. **Connection Terminals**

Connect to the pushbutton wall console terminals on the garage door opener.

5. **DC Jack (with locking feature)**

Plug in a DC 9V1A power adpator and rotate it 90 degrees clockwise to the lock position. To remove the adaptror, rotate it 90 degrees counterclockwise to the original open position and remove it.

6. **Learn Button**

Use a pointy tool to press the learn button once to enter learning mode for Tilt-GDC3.

7. **Mounting Holes**
8. **Mounting Bracket**

**Tilt-GDC3 (Garage Door Tilt Sensor)**

![](<.gitbook/assets/1 (88).jpeg>)

**Test Button / LED Indicator**

1. **Test Button:**

* Press the Test button to transmit a learning code to GDC-3.
* Press the Test button to report garage door position and enter test mode for 3 minutes. Under Test Mode, the LED will light up whenever the Garage Door Tilt Sensor is activated.

**LED Indicator:**

* The LED will flash for 3 times when it is transmitting a learning code.
* The LED will light up whenever the device is triggered under Test Mode.
* The LED will light up whenever the tamper switch is activated.
* (Door opened) When experiencing device fault or under Test Mode, the LED will flash for 6 times.
* (Door closed) When experiencing device fault or under Test Mode, the LED will flash for 6 times. After 10 seconds, the LED will flash for 3 times.
* When the battery is exhausted, the Garage Door Tilt Sensor will stop all function, the LED will flash every 4 seconds.

2. **Mounting Holes**

Used to fix and screw the Garage Door Tilt Sensor directly on the top portion of the garage door.

**3. Tamper Switch**

When the Garage Door Tilt Sensor is mounted, the Tamper Switch will be fully depressed against the garage door.

When the device cover is opened or when it is removed from the mounting surface, the Tamper Switch will be activated.

The LED will flash for 6 times and send a tamper open signal to notify user(s) of this condition.

4. **Battery Insulator**
5. **Battery Compartment**

The Garage Door Tilt Sensor is powered by one CR123 3V Lithium battery. When the battery voltage is low, a low battery signal will be sent to the Control Panel to notify user(s) of this condition.

**DC-16SL-GDC3 (Garage Door Contact)**

![](<.gitbook/assets/2 (76).jpeg>)

**1. LED Indicator**

In Normal operation mode, the LED indicator remains off except in the following situations:

\- When the Door Contact’s tamper switch is triggered.

* Every time when the Door Contact is activated due to Tamper triggering or low-battery condition.
* Every time when the Door Contact is activated and transmitting the signal under the Test mode.

1. **Test Button**
   * Press the Test button to transmit a learning code to GDC-3.
   * Press the Test button to report the garage door position and enter test mode for 3 minutes. Under Test Mode, the LED will light up whenever the Door Contact is activated.
2. **Battery Compartment**

The Door Contact is powered by one **3V CR2 Lithium battery**. When the battery voltage is low, a low battery signal will be sent to the Control Panel to notify user(s) of this condition.

4. **Cover Securing Screw Hole**
5. **Knockouts**
6. **Tamper Switch**

It is designed to protect against unauthorized removal from the mounting location, cover opening or unsteady installation. When the tamper is triggered, a tamper signal will be reported to the Control Panel through GDC-3, and the LED will also light up.

7. **Battery Insulator hole**
8. **Rib Marks**
9. **Magnet**

Mount the magnet on the side of the Door Contact where it has 2 rib marks to indicate the position of the internal magnet switch. The Door Contact should be installed either upright or inverted to ensure that the rib-marked side faces the magnet.

11. **Magnet Screw hole**
12. **Magnet Spacer**

**DC-32-EX-GDC3 (Outdoor Garage Door Contact)**

![](<.gitbook/assets/3 (73).jpeg>)

1. **Protective Cover**
2. **Battery Cover**
3. **Front Tamper Switch**
   * When the battery cover is removed, the front tamper switch will be activated.
4. **LED Indicator**
5. **Learn / Test Button**
   *   Use a pointy tool to press the button to transmit learning code or enter test mode for 3 minutes.

       Press the Test button to report the garage door position and enter test mode for 3 minutes.&#x20;
   * Under Test Mode, the LED will light up whenever the Door Contact is activated.
6. **Battery Compartment**
   * The Door Contact uses two AA L91 Lithium batteries as its power source.
7. &#x20;**Back Tamper Switch**
   * Whenever the Door Contact is removed from the mounting surface, the back tamper switch will be activated.
8. **Hooks**
9. **Latch Holes**
10. **Knockouts**
11. **Breakaway Area**

## **Getting Started**

### _**Learn Tilt-GDC3 / DC-16SL-GDC3 / DC-32-EX-GDC3 into GDC-3**_

Power on tilt-GDC3 / DC-16SL-GDC3 / DC-32-EX-GDC3 and connect GDC-3 to power supply.

* Use a pointy tool to press the learn button of GDC-3 once to enter learning mode. GDC-3 will emit one beep, and the red LED will begin to flash.
* Press the Test Button of Tilt-GDC3 / DC-16SL-GDC3 / DC-32-EX-GDC3 to send a learning code to GDC3, the LED will flash for 3 times.
* If learning is successful, GDC-3 will emit 2 beeps to indicate. If Tilt-GDC3 / DC-16SL-GDC3 / DC-32-EX-GDC3 has already been added into GDC-3, GDC-3 will emit a Di-Do sound to alert the user.
* Use a pointy tool to press the learn button of GDC-3 once again to return to normal mode, the red LED will turn off. Alternatively, GDC-3 will exit learning mode automatically with 5 beeps after 1 minute of inactivity.

{% hint style="warning" %}
Note:

The Garage Door Control supports only one sensor. If a second sensor (either tilt sensor or door contact) is learnt into GDC-3, the old sensor will be replaced by the newly learned sensor.
{% endhint %}

### _**Adding GDC-3 into the System (Inclusion)**_

The device supports both classic inclusion process and SmartStart inclusion process.

#### **Classic Inclusion**

* Connect GDC-3 to power supply
* Put the Z-wave gateway or control panel into **Inclusion mode** (please refer to the user manual of the Z-wave gateway or control panel).
* Within 1 second, press the Function Button 3 times.
* Refer to the user manual of the Z-wave gateway or control panel to complete the adding process.
* If the Garage Door Control has already been added to/included in another Z-wave Gateway/Control Panel, or if it is unable to be added to the current Z-wave Gateway/Control Panel, try removing it first (see _**Removing Device**_).

#### **SmartStart Inclusion**

SmartStart enabled products can be added to a Z-Wave network by scanning the Z-Wave QR Code present on the product with a controller providing SmartStart inclusion. No further action is required and the SmartStart product will be added automatically within 10 minutes of being powered on in the network vicinity. Z-Wave SmartStart utilizes the DSK information of the device to enhance and simplify the inclusion process. **DSK** stands for Device Specific Key used for authentication and encrypted communication. The DSK information is stored in the QR code format that is printed on a label and adhered to the front side of the device, as the example shown on the right.

![](<.gitbook/assets/7 (54).jpeg>)

* Scan the QR Code on the back of GDC-3 to obtain the **DSK** information and transfer to the Z-Wave gateway.
* Connect GDC-3 to power supply, a SmartStart inclusion request will be automatically sent to the gateway.
* The gateway will automatically include the device upon recognition of the device by matching the inclusion request with the DSK obtained.

{% hint style="warning" %}
Note:

The DSK of the device is used only during inclusion.

The DSK can be read without the GDC-3 powering ON, so it is possible to prepare the gateway to include the device prior to installing and powering up the Garage Door Control.

If GDC-3 has already been **included** (learnt) in another Z-Wave Gateway/Control Panel, please exclude it first (see _**Exclusion**_) before attempting to **include** it into the current Z-Wave Gateway/Control Panel. GDC-3 will not send a SmartStart inclusion request if it’s already in a Z-Wave Gateway/Control Panel.
{% endhint %}

### _**Removing GDC-3 from the System (Exclusion)**_

The Garage Door Control must be removed from the existing Z-wave network before being added into another one.&#x20;

#### **Exclusion Mode**

* Put the Z-wave gateway or control panel into **Exclusion mode** (please refer to the user manual of the Z-wave gateway or control panel).
* Within 1 second, press the Function Button 3 times, and the device will be removed from the Z-wave network.

#### **Factory Reset**

_(Only use factory reset when network Control Panel/Gateway is missing or inoperable)._

Factory resetting the device will restore it to factory default settings (i.e., not included in any Z-wave network).

* Press and hold the Function Button of the device for 10 seconds to perform factory reset.

{% hint style="warning" %}
Note:

Before you remove or factory reset GDC-3, please ensure that the device’s DSK information has been removed or does not exist in the gateway. If you remove or factory reset the device, but its DSK information still exists in the gateway, the gateway will automatically include the device again.
{% endhint %}

### _**Range Test**_

To test whether the Garage Door Control is able to communicate with the Z-Wave gateway or control panel:

* Put the gateway / panel into range test mode (Walk Test).
* Press the Function Button on the device.
* The gateway / control panel should display if the device is within the operation range (please refer to the user manual of the gateway / control panel).

## **Installation**

### **Mounting the Garage Door Tilt Sensor (Tilt-GDC3)**

* The Garage Door Tilt Sensor is designed to be mounted on tilt-up or overhead garage door, not to be used on roll up garage door. It is used to report the status of when the garage door is “open”, “closed”, or moving.
* The device shall be mounted vertically to the ground (It should not be tilted greater than +-5 degrees when mounted).
* Mount the device on a dry and clean surface. Ensure the device is mounted with the LED indicator on top.
* The Garage Door Tilt Sensor should be mounted on the very top panel of the garage door, as shown below.

![](<.gitbook/assets/13 (32).jpeg>)

* There are two ways to mount the Garage Door Tilt Sensor. Screw Mounting:
  1. Find a suitable location to install the Garage Door Tilt Sensor. The mounting surface should be clean and dry. Clean the mounting surface thoroughly if needed.
  2. Use the two mounting holes as a template to mark and drill mounting holes.
  3. Use the provided wall plugs for plaster/brick installation. Screw the Garage Door Tilt Sensor into the provided wall plugs. Ensure the wall plugs are flush with the mounting surface.5

{% hint style="warning" %}
Note:

Only use this type of mounting method when the garage doors are thicker than the length of the screws.
{% endhint %}

#### Adhesive Mounting:

1. Find a suitable location to install the Garage Door Tilt Sensor. The mounting surface should be clean and dry. Clean the mounting surface thoroughly if needed.
2. Remove the one side of liners on the double-sided adhesive pad. Apply it to the back of the Garage Door Tilt Sensor and press firmly for 30 seconds to ensure good contact.
3. Remove the remaining liner on the adhesive pad and firmly press the Garage Door Tilt Sensor onto a desired location for another 30 seconds. Please avoid applying the adhesive pad on uneven surface or re-applying it.

### **Mounting the Garage Door Contact (DC-16SL-GDC3)**

* The Door Contact is designed to be used on horizontally opening garage door to report the status of the garage door when the garage door is “open” or “closed.”
* Please install the Door Contact on the more stationary object (such as the door frame) and mount the magnet on the more mobile object (such as the garage door).

<figure><img src=".gitbook/assets/1 (127).png" alt=""><figcaption></figcaption></figure>

* Mount the magnet using the screws provided. Align the magnet according the rib mark on the Door Contact.
* Where required, use the Magnet Spacer to better align the magnet to the rib marks.

{% hint style="warning" %}
Note:

The magnet should be no more than 15mm from the Door Contact when the door is closed.
{% endhint %}

* The two white caps provided can be inserted into the magnet screw holes for aesthetic integrity.
* There are two ways to mount the Door Contact: self-adhesive mounting or screw mounting.

#### &#x20;Self-adhesive Mounting:

1. The mounting surface should be clean, dry, and smooth. Clean the mounting surface with a suitable degreaser if needed.
2. Remove the one side of liners on the double-sided adhesive pad. Apply the adhesive pad to the back of the device and press firmly for 30 seconds to ensure good contact.
3. Remove the remaining liner on the adhesive pad and firmly press the Door Contact onto the desired location for 30 seconds.

{% hint style="warning" %}
Note:

Do not use the adhesive pad method of installation on a surface with peeling or cracked paint, or on a rough surface.

Please do not re-apply the 3M adhesive pad. It cannot be reused
{% endhint %}

#### Screw Mounting:

The Base has two knockouts, where the plastic is thinner, for mounting purpose.

To mount the Door Contact:

1. Remove the cover by unscrewing the Cover Securing Screw with a Phillips screwdriver.
2. Break through the knockouts on the base.
3. Use the holes as a template and drill two holes.
4. Insert wall plugs if fixing into plaster or brick.
5. Screw the base into the wall plug with a Phillips screwdriver.
6. Attach the cover to the base and tighten the Cover Securing Screw.

### **Mounting the Outdoor Garage Door Contact (DC-32-EX-GDC3)**

* The waterproof door contact is designed to be used on horizontally opening garage door to report the status of the  garage door when the garage door is “open” or “closed”.

<figure><img src=".gitbook/assets/2 (135).png" alt=""><figcaption></figcaption></figure>

* It is recommended that the Door Contact be placed on the fixed frame of the garage door, and the magnet on the garage door.
* The rib marks on the magnet and Door Contact must align (**FIG. 1**).
* The magnet should not be more than 3 cm from the marked side of the Door Contact when the door is closed.
* The door contact has a back tamper switch on its back cover. Ensure the device is positioned within the bracket so that the tamper switch spring is pressed against the breakaway area that is loosely connected to the bracket.

If the door contact is forcibly removed from the wall, the breakaway area will break off from the bracket and remain attached to the mounting surface, activating the tamper switch.

<figure><img src=".gitbook/assets/3 (121).png" alt=""><figcaption></figcaption></figure>

*   To mount the Door Contact:

    1. The provided mounting bracket has 3 knockouts where the plastic is thinner and can be broken for mounting purpose. (**FIG. 2**)



    <figure><img src=".gitbook/assets/4 (124).png" alt=""><figcaption></figcaption></figure>





2. Use the mounting bracket as a template to drill holes on the wall for plugs. (**FIG. 3**)
3. Push in the plugs and fix the mounting bracket on the wall with the screws.
4. Mount the Door Contact with the hooks on the back cover of the Door Contact latched on the latch holes of the mounting bracket, and then push downwards to lock the hook. (**FIG. 4**)

{% hint style="warning" %}
Note:

Make sure the back tamper switch of the Door Contact is pressed against the breakaway area on the mounting bracket.

Secure the bottom fixing screws.
{% endhint %}

&#x20;5\. Re-place the protective cover.



* There are two ways to mount the magnet – adhesive mounting and screw mounting.

&#x20;Screw mounting:

1. Screw the mounting bracket with the two supplied screws to the door.
2. Attach the magnet to the mounting bracket.

{% hint style="warning" %}
Note:

The magnet spacer provided can be used, by having the side with black words touch the mounting bracket, between the magnet and the door to facilitate alignment and installation.
{% endhint %}

Adhesive mounting:

1. Alternatively, use the double sided tape provided to directly attach the magnet to the door.

{% hint style="warning" %}
Ensure that the mounting surface should be clean, dry, and smooth before attaching the magnet taped with the double sided tape to the door and that the magnet should be firmly pressed against the door for 30 seconds.
{% endhint %}

2. The installation is now complete.

<figure><img src=".gitbook/assets/1 (128).png" alt=""><figcaption></figcaption></figure>

### **Mounting the Garage Door Control (GDC-3)**

* The Garage Door Control is usually mounted on the ceiling near the garage door opener and the power outlet.

<figure><img src=".gitbook/assets/2 (136).png" alt=""><figcaption></figcaption></figure>

<figure><img src=".gitbook/assets/1 (129).png" alt=""><figcaption></figcaption></figure>

{% hint style="danger" %}
Before installation, ensure to disconnet power supply from the garage door opener.

The GDC-3 Garage Door Control must be installed in sight of the garage door, where both visual and audiable alerts can be clearly seen and heard.
{% endhint %}

1. Use the mounting bracket as template, mark the two mounting holes, drill holes in mounting location and insert wall plugs if needed.
2. Screw the mounting bracket into marked location with the two hooks facing outward.
3. Hook the Garage Door Control onto the Wall Mounting Bracket (with the Mounting Holes of the Garage Door Control).
4. Push the Garage Door Control (in the direction as indicated in picture below) to lock it into the mounting bracket.

<figure><img src=".gitbook/assets/2 (137).png" alt=""><figcaption></figcaption></figure>

5. Connect the GDC-3 terminals to the pushbutton wall console terminals on the garage door opener. Either wire can be connected to either terminal. (The wall console terminals may be named “PWC”, “WC”, “PB”, “PUSHBUTTON” or “RED” and “WHITE”. Terminal names and locations vary by model.)
6. Plug in the DC 9V 1A output Power Adapter and connect to power supply.
7. Restore power to your garage door opener.

<figure><img src=".gitbook/assets/1 (130).png" alt=""><figcaption></figcaption></figure>

## **Operation**

### _**Operation of Garage Door**_

* After GDC-3 has been included in the Z-Wave network, the Z-Wave gateway can remotely open or close the garage door with Z-Wave

command \[COMMAND\_CLASS\_BARRIER\_OPERATOR] and \[BARRIER\_OPERATOR\_SET], using parameters below:

* Open : Target Value = 0xFF
* Close : Target Value = 0x00
* Users can also press the function button once to open/close the garage door.

<figure><img src=".gitbook/assets/2 (138).png" alt=""><figcaption></figcaption></figure>

* Before the activated garage door begins to move, the warning LED indicators (Green and Red) will flash and alarm beeps will sound for 5 seconds. As the garage door starts moving, the garage door’s position will be reported to the Z-Wave gateway.

<figure><img src=".gitbook/assets/1 (131).png" alt=""><figcaption></figcaption></figure>

* Once GDC-3 starts the movement of the garage door, you will need to wait for 35 seconds for the garage door to completely open or close before you can send a second open/close command or press the function button to open/close. If a second command is sent or the function button is pressed within 35 seconds, GDC-3 will send a busy signal to the Z-Wave gateway.

<figure><img src=".gitbook/assets/3 (122).png" alt=""><figcaption></figcaption></figure>

\[COMMAND\_CLASS\_APPLICATION\_STATUS] \[APPLICATION\_BUSY]

* Status : 0x00
* Wait Time : 0x00
* When the garage door is in open state, GDC-3 will bypass any open command from the Z-Wave gateway. When the garage door is in closed state, GDC-3 will bypass any close command from the Z-Wave gateway.

### _**Alarm Sound Volume**_

* Before the activated garage door begins to move, the warning LED indicators will flash and alarm beeps will sound for 5 seconds. Users can adjust the alarm sound volume by sending command from the Z-Wave gateway with Configuration CC command, using parameters below:
* S : Size
* D : Default

<figure><img src=".gitbook/assets/1 (132).png" alt=""><figcaption></figcaption></figure>

### _**Features of Garage Door Tilt Sensor (Tilt-GDC3) / Door Contact (DC-16SL-GDC3) / Outdoor Door Contact (DC-32-EX-GDC3)**_

* Garage Door Position Detection

Whenever the position of the garage door changes, Tilt-GDC3 / DC-16SL-GDC3 / DC-32-EX-GDC3 will report the door’s position to GDC-3, and GDC-3 will report to the Z-Wave gateway with Z-Wave command

<figure><img src=".gitbook/assets/1 (133).png" alt=""><figcaption></figcaption></figure>

* Tamper Protection

Tilt-GDC3 / DC-16SL-GDC3 / DC-32-EX-GDC3 is protected by a tamper switch. When the device is removed from the mounting surface or when the device cover is opened, its tamper switch will be activated. The device will then send a tamper open signal to GDC-3, and GDC-3 will report to the Z-Wave gateway with Z-Wave command \[COMMAND\_CLASS\_NOTIFICATION] \[NOTIFICATION\_REPORT].

* Open: 00 00 00 FF 07 03 00 00
* Close: 00 00 00 FF 07 00 01 03
* Supervisory Signal

The Tilt-GDC3 / DC-16SL-GDC3 / DC-32-EX-GDC3 will transmit Supervisory Signal along with the garage door’s position to GDC-3 every 15-20 minutes. GDC-3 will report to the Z-Wave gateway using \[BARRIER\_OPERATOR\_REPORT].

If the Z-Wave gateway fails to receive any supervisory signals from the Tilt-GDC3 / DC-16SL-GDC / DC-32-EX-GDC over a preset period of time, an “Out-Of-Order” fault message will be generated.

* Supervision error: 00 00 00 FF 06 49 00
* Restore: 00 00 00 FF 06 00 00 (Both the battery status and supervisory signal need to be back to normal)
* Low Battery

The Tilt-GDC3 / DC-16SL-GDC3 / DC-32-EX-GDC3 features the function of Low Battery Detection. When the battery voltage is low, the Tilt Sensor / Door Contact will transmit a low-battery signal to GDC-3, and GDC-3 will report to the Z-Wave gateway with Z-Wave command \[COMMAND\_CLASS\_NOTIFICATION] \[NOTIFICATION\_REPORT].

* Low Battery: 00 00 00 FF 06 4A 00
* Restore: 00 00 00 FF 06 00 00 (Both the battery status and supervisory signal need to be back to normal)

## **Z-Wave Information**

**Device Type:** GENERIC\_TYPE\_ENTRY\_CONTROL

**Specific Type:** SPECIFIC\_TYPE\_SECURE\_BARRIER\_ADDON

**Icon Type:** ICON\_TYPE\_GENERIC\_BARRIER

**Role Type:** Always On Slave (AOS)

**Security:** S2\_UNAUTHENTICATED

**Manufacturer ID:** 0x018E

**Product Type ID:** 0x0004

**Product ID:** 0x0127

* _**Supported Command Class**_

<figure><img src=".gitbook/assets/1 (134).png" alt=""><figcaption></figcaption></figure>
