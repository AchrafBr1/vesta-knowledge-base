# VESTA 082

**WADC-1** **Wandering Prevention Door Contact**

WADC-1 is a door contact that combines PIR sensors to monitor openings of the door and detect the movements around it. Designed especially for those who are suffering from dementia and prone to wander, WADC-1 will transmit signals to the control panel to notify the caregiver when the user opens the door, moving from inside of the room to the outside.

WADC-1 has two adjustable sensitivity levels that further offer convenience for usages. When mounted at a height of 2.1\~2.3 meters above the ground, the PIR sensors each has the coverage pattern of 3 x 1 meters at ground level.

![](<.gitbook/assets/0 (37).png>)

* _**Identifying the Parts**_

**1. LED indicator (Red)**

The LED indicator is used to indicate the status of PIR Zone 2 sensor (door opening area) and the door contact.

**2. LED indicator (Green)**

The LED indicator is used to indicate the status of PIR Zone 1 sensor and the door contact.

**3. Test Button**

Press the Test button to transmit learning code or enter test mode for 3 minutes.

**4. Sensitivity Increaser Jumper Switch (JP3)**

![](<.gitbook/assets/1 (38).jpeg>)

**Jumper On**

![](<.gitbook/assets/2 (51).png>)

The jumper link is inserted, connecting the two pins.

**Jumper Off**

![](<.gitbook/assets/3 (30).jpeg>)

The jumper link is removed or “**parked**” on one pin.

*
  * If the jumper is OFF, the PIRs’ detection sensitivity is in normal level. (**Factory default**)
  * If the jumper is ON, the PIRs’ detection sensitivity is set to high.

1. **Single / Multiple-Sensor Setting Jumper Switch (JP4)**

![](<.gitbook/assets/4 (33).jpeg>)

**Jumper On**

![](<.gitbook/assets/5 (42).png>)

The jumper link is inserted, connecting the two pins.

**Jumper Off**

![](<.gitbook/assets/6 (29).jpeg>)

The jumper link is removed or “**parked**” on one pin.

*
  * If the jumper is OFF, WADC-1 will be recognized as 3 sensors (PIR Zone 1 Sensor, PIR Zone 2 Sensor, and the Door Contact).
  * If the jumper is ON, WADC-1 will be recognized as 1 sensor (WADC). (**Factory default**)

1. **Door Open Direction Jumper Switch (JP5)**

![](<.gitbook/assets/7 (23).png>)

**Jumper On**

The jumper link is inserted, connecting the two pins.

Ensure JP5 is set to ON for the setting to be effective.

**Jumper Off**

![](<.gitbook/assets/8 (27).png>)

The jumper link is removed or “**parked**” on one pin.

*
  * Set the jumper to OFF if the door where the magnet is installed is designed to be opened outward. (**Factory default**)
  * Set the jumper to ON if the door where the magnet is installed is designed to be opened inward.

1. **Battery Compartment**
2. **Tamper Switch**

When WADC-1 is mounted in place, the tamper switch will be activated when the cover is opened or when the device is removed from mounting surface.

1

*
  1. **Magnet**
* _**Supervision Function**_
  *
    * PIR Zone 1 sensor, PIR Zone 2 sensor, and the Door Contact will transmit their supervisory signal separately to the Control Panel every 30 to 50 minutes.
    * If the Control Panel fails to receive the supervisory signals transmitted from a certain device for a preset time, an “Out-Of-Order” fault message will be generated.
* _**Sensitivity Increaser Function (JP3)**_

![](<.gitbook/assets/9 (13).jpeg>) ![](<.gitbook/assets/10 (14).jpeg>)

You can use the sensitivity increaser function to increase the PIR sensors’ detection sensitivity. To increase detection sensitivity, connect the Jumper Switch (JP3) to set to the **ON** position. To maintain normal detection sensitivity, disconnect the Jumper Switch (JP3) to set to the **OFF** position (Factory default).

![](<.gitbook/assets/11 (17).jpeg>)

* _**Single / Multiple-Sensor Setting Function (JP4)**_

You can use the Jumper Switch (JP4) to decide whether to recognize the device as a single sensor or multiple sensors after the device is learned into the Control Panel. If the Jumper Switch (JP4) is set to ON, WADC-1 will be recognized as 1 sensor. Whenever a movement is detected, the LED will flash. If the Jumper Switch is set to OFF, WADC-1 will be recognized as 3 separate sensors (PIR Zone 1 Sensor, PIR Zone 2 Sensor, and the Door Contact).

![](<.gitbook/assets/12 (23).png>)

_\<NOTE>_

*
  * Everytime before chaning the setting of JP4, ensure to remove the battery first. Press the Test Button for several times, change to desired jumper setting, and insert the battery back. The changes will be effective after battery power is provided to the device.
* _**Door Open Direction Detection (JP5)**_

![](<.gitbook/assets/13 (16).jpeg>)

You can use the jumper switch to set the open direction of your door. For the setting to be effective, ensure to set JP4 to ON first. If the door where the magnet is installed is designed to be opened outward, set the Jumper Switch (JP5) to OFF.

If the door is designed to be opened inward, set the Jumper Switch (JP5) to ON.

![](<.gitbook/assets/14 (17).jpeg>)

* _**Test Mode**_
  * Under Normal Mode, pressing the Test Button will transmit a test signal to the Control Panel for radio range test, and WADC-1 will enter Test Mode for 3 minutes. It will exit Test Mode automatically after 3 minutes and return to normal mode.
  * In Test mode, the Green or Red LED indicator will flash every time a movement is detected in PIR Zone 1 or PIR Zone 2 (door opening area); both the Blue LED and the Red LED will flash when the door contact is activated.
  * You can check the PIR Zone 1 and Zone 2 sensors’ detection range by triggering the sensors.
* _**LED Indicator**_

![](<.gitbook/assets/15 (14).jpeg>)

In Normal operation mode, the LED Indicators will flash in the following situations:

*
  * When movement is detected in PIR Zone 1 or PIR Zone 2 (door opening area) under fault conditions (low battery, tamper open), or in test mode, the Green LED or the Red LED will flash.
  * When the door contact is activated under fault conditions (low battery, tamper open), or in test mode, both the Green LED and the Red LED will flash.
  * When the cover is opened and the tamper switch is triggered, both the Green LED and the Red LED will flash.
  * When the Test Button is pressed under fault conditions (low battery, tamper open), both the Green LED and the Red LED will flash.
  * When the battery is exhausted, WADC-1 will stop all function, both the Green LED and the Red LED will flash every 4 seconds.
* _**Battery**_
  * WADC-1 uses one 3V CR123 Lithium battery as its power source:
  * WADC-1 features low battery detection function. If low battery voltage is detected, a low-battery signal will be sent to the Control Panel along with regular signal transmissions for the Control Panel to display the status accordingly.
  * When changing the battery, after removing the old battery, press the Tamper Switch twice to fully discharge before inserting a new battery.
* _**Getting Started**_
  * Pull out the battery insulator to activate battery.
  * Put the Control Panel into learning mode, refer to Control Panel manual for details.
  * Press the test button on the side to send a learn code to the Control Panel.
  * When JP4 is set to ON, WADC-1 will be recognized as **1 sensor** (WADC) and occupy 1 zone in the Control Panel after it is learned into the Control Panel.
  * When JP4 is set to OFF, WADC-1 will be recognized as **3 separate sensors** (PIR Zone 1 sensor, PIR Zone 2 sensor, and the Door Contact) and occupy **3 zones** in the Control Panel after it is learned into the Control Panel.
  * Refer to Control Panel manual to complete the learn-in process.
* _**Walk Test**_
  * After WADC-1 is learnt-in, put the Control Panel into “**Walk Test**” mode, hold WADC-1 at the desired location, and press the Test button to confirm whether this location is within signal range of the Control Panel, refer to Control

![](<.gitbook/assets/16 (12).jpeg>) ![](<.gitbook/assets/17 (11).jpeg>) ![](<.gitbook/assets/18 (9).jpeg>)

2

Panel manual to complete Walk Test.

*
  * When you are satisfied that WADC-1 works at the chosen location, you can proceed to mounting.
* _**Installation Guideline**_
  * WADC-1 should be installed on the door frame right above the door to look downward and monitor movements around the door.
  * The magnet should be installed on the door on the opposite side of the internal magnet switch location of door contact.
  * The WADC-1 has 2 rib-marks on one side (refer to figure), marking the internal magnet switch location. The magnet must align with the rib-mark side of the WADC-1 as shown in figure below.

![](<.gitbook/assets/19 (6).jpeg>) ![](<.gitbook/assets/20 (8).jpeg>)

* If the door where the magnet is installed is designed to be opened outward, please set **JP5 to OFF** (**Ensure JP4 is set to ON for the setting to be effective**). The distance between the WADC-1 and the magnet should be no more than 5 mm when the door is closed.
* If the door where the magnet is installed is designed to be opened inward, please set **JP5 to ON** (**Ensure JP4 is set to ON for the setting to be effective**). The distance between the WADC-1 and the magnet should be no more than 5 mm when the door is closed.

3

1. The mounting surface should be clean, dry, and smooth. Clean the mounting surface with a suitable degreaser if

needed.

1. Remove the liner from one side of the double-sided adhesive tape. Apply the adhesive tape to the back of the device and press firmly for 30 seconds to ensure good adhesion.
   1. Remove the other liner and firmly press the Door Contact onto the desired location for 30 seconds.

_\<NOTE>_

*
  *
    * Do not use the adhesive tape installation on a surface with peeling or cracked paint, or on a rough surface.
    * Please do not re-apply the 3M adhesive tape. It cannot be reused
* **Screw Mounting**

The Base has two knockouts, where the plastic is thinner, for mounting purpose. (refer to figure on the right)

To mount the Door Contact:

*
  1. Remove the cover by unscrewing the Cover Securing Screw using a Philips screwdriver.

1. Break through the knockouts on the base.
2. Using the holes as a template, drill both holes.

IV. Insert wall plugs if fixing into plaster or brick.

1. Screw the base into the wall plug using a Philips screwdriver.

VI. Attach the cover to the base and tighten the Cover Securing Screw.

*
  * Fit the magnet on the door using the small piece of double-sided adhesive tape. The magnet must align with the rib-mark side of the Door Contact. Installation is now complete.
* _**Installation Recommendations**_
  * WADC-1 should be installed on the door frame part that is right above the door to look downward and monitor movements.
  * When mounted at a height of 2.1\~2.3 meters and facing down, the PIR sensors (PIR Zone 1 & Zone 2) each has the coverage pattern of 3 x 1 meters at ground level.

4
