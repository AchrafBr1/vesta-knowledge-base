# VESTA-082

**WADC-1**

## **Wandering Prevention Door Contact**

<figure><img src=".gitbook/assets/image (57).png" alt=""><figcaption></figcaption></figure>

WADC-1 is a door contact that combines PIR sensors to monitor openings of the door and detect the movements around it. Designed especially for those who are suffering from dementia and prone to wander, WADC-1 will transmit signals to the control panel to notify the caregiver when the user opens the door, moving from inside of the room to the outside.

WADC-1 has two adjustable sensitivity levels that further offer convenience for usages. <mark style="background-color:yellow;">When mounted at a height of 2.1\~2.3 meters above the ground, the PIR sensors each has the coverage pattern of 3 x 1 meters at ground level.</mark>

## **Identifying the Parts**

<figure><img src=".gitbook/assets/image (97).png" alt=""><figcaption></figcaption></figure>

**1. LED indicator (Red)**

The LED indicator is used to indicate the status of PIR Zone 2 sensor (door opening area) and the door contact.

**2. LED indicator (Green)**

The LED indicator is used to indicate the status of PIR Zone 1 sensor and the door contact.

**3. Test Button**

Press the Test button to transmit learning code or enter test mode for 3 minutes.

**4.Supervision Enable/Disable Jumper Switch (JP2) (Currently Reserved)**

**Jumper On**

<div align="left"><figure><img src=".gitbook/assets/image (2) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1).png" alt=""><figcaption></figcaption></figure></div>

The jumper link is inserted connecting the two pins

**Jumper Off**

<div align="left"><figure><img src=".gitbook/assets/image (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1).png" alt=""><figcaption></figcaption></figure></div>

The jumper link is removed or **“parked”** on one pin.

* When the jumper is set as ON, the Supervision is disabled.
* When the jumper is set as OFF, the Supervision is enabled. **(Factory default)**

**JP2 Jumper Switch is currently not supported. Supervision is always enabled** .

**5.Sensitivity Increaser Jumper Switch (JP3)**

**Jumper On**

<div align="left"><figure><img src=".gitbook/assets/image (3) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1).png" alt=""><figcaption></figcaption></figure></div>

The jumper link is inserted connecting the two pins

**Jumper Off**

<div align="left"><figure><img src=".gitbook/assets/image (4) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1).png" alt=""><figcaption></figcaption></figure></div>

The jumper link is removed or **“parked”** on one pin.

* If the jumper is OFF, the PIRs’ detection sensitivity is in normal level. **(Factory default)**
* If the jumper is ON, the PIRs’ detection sensitivity is set to high.

**6.**<mark style="background-color:blue;">**Single / Multiple-Sensor Setting Jumper Switch (JP4)**</mark>

**Jumper On**

<div align="left"><figure><img src=".gitbook/assets/image (5) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1).png" alt=""><figcaption></figcaption></figure></div>

The jumper link is inserted, connecting the two pins.

**Jumper Off**

<div align="left"><figure><img src=".gitbook/assets/image (7) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1).png" alt=""><figcaption></figcaption></figure></div>

The jumper link is removed or “**parked**” on one pin.

* <mark style="background-color:blue;">Jumper OFF, Reserved.</mark>
* <mark style="background-color:blue;">The jumper is set to ON, WADC-1 is recognized as 1 sensor (WADC).</mark> <mark style="background-color:blue;"></mark><mark style="background-color:blue;">**(Factory default)**</mark>

**7.Door Open Direction Jumper Switch (JP5)**

<div align="left"><figure><img src=".gitbook/assets/image (8) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1).png" alt=""><figcaption></figcaption></figure></div>

**Jumper On**

The jumper link is inserted, connecting the two pins.

**Jumper Off**

<div align="left"><figure><img src=".gitbook/assets/image (9) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1).png" alt=""><figcaption></figcaption></figure></div>

The jumper link is removed or “**parked**” on one pin.

Ensure JP5 is set to ON for the setting to be effective.

* Set the jumper to OFF if the door where the magnet is installed is designed to be opened outward. (**Factory default**)
* Set the jumper to ON if the door where the magnet is installed is designed to be opened inward.

8. **Battery Compartment**
9. **Tamper Switch**

When WADC-1 is mounted, the Tamper switch will be activated when the cover is opened or when the device is removed from mounted surface.

8. **Magnet**

## _**Supervision Function**_

* PIR Zone 1 sensor, PIR Zone 2 sensor, and the Door Contact will transmit their supervisory signal separately to the Control Panel every 30 to 50 minutes.
* If the Control Panel fails to receive the supervisory signals transmitted from a certain device for a preset time, an “Out-Of-Order” fault message will be generated.

## _**Sensitivity Increaser Function (JP3)**_

You can use the sensitivity increaser function to increase the PIR sensors’ detection sensitivity. To increase detection sensitivity, connect the Jumper Switch (JP3) to set to the **ON** position. To maintain normal detection sensitivity, disconnect the Jumper Switch (JP3) to set to the **OFF** position (Factory default).

## _**Single / Multiple-Sensor Setting Function (JP4)****&#x20;**<mark style="background-color:blue;">**(JP4 Reserved)**</mark>_

You can use the Jumper Switch (JP4) to decide whether to recognize the device as a single sensor or multiple sensors after the device is learned into the Control Panel. If the Jumper Switch (JP4) is set to ON, WADC-1 will be recognized as 1 sensor. Whenever a movement is detected, the LED will flash. If the Jumper Switch is set to OFF, WADC-1 will be recognized as 3 separate sensors (PIR Zone 1 Sensor, PIR Zone 2 Sensor, and the Door Contact).&#x20;

{% hint style="warning" %}
Note:

Everytime before chaning the setting of JP4, ensure to remove the battery first. Press the Test Button for several times, change to desired jumper setting, and insert the battery back. The changes will be effective after battery power is provided to the device.
{% endhint %}



## _**Door Open Direction Detection (JP5)**_

You can use the jumper switch to set the open direction of your door. For the setting to be effective, ensure to set JP4 to ON first. If the door where the magnet is installed is designed to be opened outward, set the Jumper Switch (JP5) to OFF.

If the door is designed to be opened inward, set the Jumper Switch (JP5) to ON.

## _**Test Mode**_

* Under Normal Mode, pressing the Test Button will transmit a test signal to the Control Panel for radio range test, and WADC-1 will enter Test Mode for 3 minutes. It will exit Test Mode automatically after 3 minutes and return to normal mode.
* In Test mode, the Green or Red LED indicator will flash every time a movement is detected in PIR Zone 1 or PIR Zone 2 (door opening area); both the Blue LED and the Red LED will flash when the door contact is activated.
* You can check the PIR Zone 1 and Zone 2 sensors’ detection range by triggering the sensors.

## _**LED Indicator**_

In Normal operation mode, the LED Indicators will flash in the following situations:

* When movement is detected in PIR Zone 1 or PIR Zone 2 (door opening area) under fault conditions (low battery, tamper open), or in test mode, the Green LED or the Red LED will flash.
* When the door contact is activated under fault conditions (low battery, tamper open), or in test mode, both the Green LED and the Red LED will flash.
* When the cover is opened and the tamper switch is triggered, both the Green LED and the Red LED will flash.
* When the Test Button is pressed under fault conditions (low battery, tamper open), both the Green LED and the Red LED will flash.
* When the battery is exhausted, WADC-1 will stop all function, both the Green LED and the Red LED will flash every 4 seconds.

## _**Battery**_

* WADC-1 uses one 3V CR123 Lithium battery as its power source:
* WADC-1 features low battery detection function. If low battery voltage is detected, a low-battery signal will be sent to the Control Panel along with regular signal transmissions for the Control Panel to display the status accordingly.
* When changing the battery, after removing the old battery, press the Tamper Switch twice to fully discharge before inserting a new battery.

## _**Getting Started**_

* Pull out the battery insulator to activate battery.
* Put the Control Panel into learning mode, refer to Control Panel manual for details.
* Press the test button on the side to send a learn code to the Control Panel.
* When JP4 is set to ON, WADC-1 will be recognized as **1 sensor** (WADC) and occupy 1 zone in the Control Panel after it is learned into the Control Panel.
* When JP4 is set to OFF, WADC-1 will be recognized as **3 separate sensors** (PIR Zone 1 sensor, PIR Zone 2 sensor, and the Door Contact) and occupy **3 zones** in the Control Panel after it is learned into the Control Panel.
* Refer to Control Panel manual to complete the learn-in process.

## _**Walk Test**_

* After WADC-1 is learnt-in, put the Control Panel into “**Walk Test**” mode, hold WADC-1 at the desired location, and press the Test button to confirm whether this location is within signal range of the Control Panel, refer to Control Panel manual to complete Walk Test.
* When you are satisfied that WADC-1 works at the chosen location, you can proceed to mounting.

## _**Installation Guideline**_

* WADC-1 should be installed on the door frame right above the door to look downward and monitor movements around the door.&#x20;
* The magnet should be installed on the door on the opposite side of the internal magnet switch location of door contact.&#x20;
* The WADC-1 has 2 rib-marks on one side (refer to figure), marking the internal magnet switch location. The magnet must align with the rib-mark side of the WADC-1 as shown in figure below.

<figure><img src=".gitbook/assets/image (10) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1).png" alt=""><figcaption></figcaption></figure>

* <mark style="background-color:green;">If the door where the magnet is installed is designed to be opened outward, please set</mark> <mark style="background-color:green;"></mark><mark style="background-color:green;">**JP5 to OFF**</mark> <mark style="background-color:green;"></mark><mark style="background-color:green;">(</mark><mark style="background-color:green;">**Ensure JP4 is set to ON for the setting to be effective**</mark><mark style="background-color:green;">). The distance between the WADC-1 and the magnet should be no more than 5</mark> <mark style="background-color:green;">mm when the door is closed.</mark>

<figure><img src=".gitbook/assets/image (11) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1).png" alt=""><figcaption></figcaption></figure>

* <mark style="background-color:green;">If the door where the magnet is installed is designed to be opened inward, please set JP5 to ON (Ensure JP4 is set to ON for the setting to be effective). The distance between the WADC-1 and the magnet should be no more than 5 mm when the door is closed.</mark>

<figure><img src=".gitbook/assets/image (98).png" alt=""><figcaption></figcaption></figure>

* Avoid mounting WADC-1 on metallic surface. If mounting on metallic surface, make sure to test whether the Door Contact can be triggered when the door is opened.

## Mounting Method

* There are two ways to mount the WADC-1: Self-adhesive mounting or Screw mounting.&#x20;

### Self-adhesive Mounting

1. The mounting surface should be clean, dry, and smooth. Clean the mounting surface with a suitable degreaser if needed.
2. Remove the liner from one side of the double-sided adhesive tape. Apply the adhesive tape to the back of the device and press firmly for 30 seconds to ensure good adhesion.
3. Remove the other liner and firmly press the Door Contact onto the desired location for 30 seconds.

{% hint style="warning" %}
Note:

Do not use the adhesive tape installation on a surface with peeling or cracked paint, or on a rough surface.

Please do not re-apply the 3M adhesive tape. It cannot be reused
{% endhint %}

### **Screw Mounting**

The Base has two knockouts, where the plastic is thinner, for mounting purpose. (refer to figure on the right)

To mount the Door Contact:

1. Remove the cover by unscrewing the Cover Securing Screw using a Philips screwdriver.
2. Break through the knockouts on the base.
3. Using the holes as a template, drill both holes.
4. Insert wall plugs if fixing into plaster or brick.
5. Screw the base into the wall plug using a Philips screwdriver.
6. Attach the cover to the base and tighten the Cover Securing Screw.

* Fit the magnet on the door using the small piece of double-sided adhesive tape. The magnet must align with the rib-mark side of the Door Contact. Installation is now complete.

## _**Installation Recommendations**_

* WADC-1 should be installed on the door frame part that is right above the door to look downward and monitor movements.
* When mounted at a height of 2.1\~2.3 meters and facing down, the PIR sensors (PIR Zone 1 & Zone 2) each has the coverage pattern of 3 x 1 meters at ground level.

<figure><img src=".gitbook/assets/image (99).png" alt=""><figcaption></figcaption></figure>
