# VESTA-051

IRC-29

## Curtain PIR Motion Sensor&#x20;

<figure><img src=".gitbook/assets/image (48).png" alt=""><figcaption></figcaption></figure>

The PIR detects infrared signature to pick up movements within an assigned area and signals the Control Panel to activate the alarm if an intruder crosses its’ path of detection.

The PIR consists of a two-part design made up of a cover and a base. The PIR contains all the electronics and optics and the base provides a means of fixing. The base has knockouts to allow mounting on a flat surface or on the ceiling.

The PIR has a tamper switch which will be activated when the cover is opened, or when it is removed from the mounted surface. It can also alert you to signal communication problems and low battery situations.

## Identifying the Parts

<div align="left"><figure><img src=".gitbook/assets/image (84).png" alt=""><figcaption></figcaption></figure></div>

1. &#x20;**PIR Lens**
2. **Learn / Test Button**

The test button is used for testing the radio performance and for learning purpose.

3. **LED Indicator**

The LED indicator is inside the front cover and only visible when activated.

4. **Battery Compartment**

The PIR uses 1 x CR123A (3V) Battery as power source.

5. **Tamper Switch**

The Tamper switch protects the PIR from unauthorized cover opening or mounting surface removal.

6. **Supervision Enable/Disable Jumper Switch (JP2)**

![jumper close](<.gitbook/assets/1 (29).png>) ![jumper open](<.gitbook/assets/2 (32).png>)

**Jumper Off**

if the jumper link is removed or “**parked**” on one pin.

**Jumper On**

The jumper link is inserted connecting the two pins

\- When the jumper is set as ON, Supervision is disabled. **(Factory default for 433AM model)**

\- When the jumper is set as OFF, Supervision is enabled. **(Factory default for 868WF model)**

_(**868FM** & **869FM** & **F1** models **DO NOT** have JP2, supervision is always enabled)._

7. **Sensitivity Increaser Jumper Switch (JP3)**

![jumper open](<.gitbook/assets/3 (30).png>)

\- If the jumper is OFF (if the jumper link is removed or “parked” on one pin), the PIR’s detection sensitivity is in normal level. **(Factory default)**

![jumper close](<.gitbook/assets/4 (30).png>)

\- If the jumper is ON, the PIRs detection sensitivity is high.

8. **Battery Insulator**

## _**Sleep Timer**_

The PIR has a “**sleep time**” of approximately 1 minute to conserve power. After transmitting a detected movement, the PIR will not retransmit for 1 minute; any further movement detected during this sleep period will extend the sleep time by another minute. In this way continuous movement in front of a PIR will not unduly exhaust the battery.

## _**Supervision Function**_

If enabled, the PIR it will conduct a Self-test Periodically by transmitting a supervisory signal once every 30 to 50 minutes.

If the Control Panel fails to receive the Supervisory signals transmitted from a certain PIR for a preset time, an “**Out-Of-Orde**r” fault message will be generated.

## _**Sensitivity Adjustment**_

You can use the sensitivity increaser function to increase the PIR’s detection sensitivity. To increase detection sensitivity, connect the Jumper Switch (JP3), or the **ON** position (Factory default. To maintain normal detection sensitivity, disconnect the Jumper Switch (JP3), or the **OFF** position.

## _**Test Mode**_

The PIR can be put into Test mode by pressing the Test Button. In Test mode, it will disable the sleep timer and will enable the LED indicator to flash every time a movement is detected. Every time the Test Button is pressed, the PIR will transmit a test signal to the Control Panel for radio range test and enter the test mode for 3 mins. It will exit Test Mode automatically after 3 minutes and return to normal mode.

## _LED Indicator_

In Normal operation mode, the LED Indicator light up in the following situations (For F1 models, the LED flashes instead):

* When movement is detected under low battery condition.
* When the cover is opened / removed from mounting surface and the tamper switch is triggered.
* When movement is detected if the Tamper condition persists.
* When movement is detected under Test mode.
* When the Test Button is pressed under tamper condition or if PIR is under low battery.

## _Battery_

* The PIR uses one 3V CR123A battery as power source.
* The PIR features low battery detection function. If low battery voltage is detected, a low battery signal will be sent to the Control Panel along with regular signal transmissions for the Control Panel to display the status accordingly.
* For each installation, the battery is installed in by the factory before shipment with an Insulator inserted. Remove insulator to activate battery.
* When changing batteries, removing the old batteries and press the Tamper Switch twice to discharge before inserting new batteries.

## _Getting Started_

* Pull out the battery insulator to activate battery.
* The LED indicator will flash for 30 seconds. (The PIR is warming up). During the warm up period, the PIR will not be activated. It is recommended that you stay away from the detection area during this time. After the warm up period is over, the LED will turn off and the PIR will be ready for operation.
* Put the Control Panel into learning mode, refer to Control Panel manual for detail.
* Press the test button.
* Refer to Control Panel manual to complete the learn-in process.
* After the PIR is learnt-in, put the Control Panel into “**Walk Test**” mode, hold the PIR in the desired location, and press the Test button to confirm this location is within signal range of the Control Panel, refer to Control Panel manual to complete Walk Test.
* When you are satisfied that the PIR work in the chosen location, you can proceed to mounting.

## _PIR Detection Coverage_

* When mounted vertically, the PIR has a horizontal detection coverage of 10° and vertical detection coverage of 110° to the front.
* The PIR will only be activated by movements across the 10° horizontal coverage.
* The PIR can be mounted vertically, horizontally on the wall surface or on the ceiling. Different mounting methods provide different PIR detection coverage and range (Please refer to **Mounting Methods** below for details).

## _Mounting Methods_

* The PIR is designed to be mounted on either a flat surface on a wall or on a ceiling with fixing screws and plugs provided.
* If the mounted PIR is forcedly removed, the Tamper Breakaway Area will be left on the wall separated from the PIR, the tamper will then be triggered.
* The base has two knockouts, where the plastic is thinner and can be broken for mounting purpose.

<div align="left"><figure><img src=".gitbook/assets/image (85).png" alt=""><figcaption></figcaption></figure></div>

1. Remove the fixing screw and cover assembly.
2. Break through the knockouts on the inside of base.
3. Using the holes as a template, drill holes in the surface.
4. Insert the wall plugs if fixing it into plaster or brick.
5. Screw the base into the wall plugs.
6. Screw the cover onto the base.

* There are different mounting methods including vertical/horizontal and ceiling mountings, and each of them has different application. Please refer to the below mounting methods.

### **Vertical Wall Mount:**

* When mounted vertically, the PIR has a detection range of 10 meters against horizontally movement only.
* It is suggested to mount the PIR at 1.4 meters to 1.6 meters above the ground vertically.
* Avoid mounting over 1.7 meters, otherwise the PIR detection range maybe affected.

### **Horizontal Wall Mount:**

* When mounted horizontally, the PIR has a detection range of 5 meters against vertically movement only. This practice is usually used to protect intruder from sky light or roof hatch.
* Avoid mounting below 2.2 meters, which may affect detection performance.

&#x20;                                  **Vertical**                                                                                  **Horizontal**

![](<.gitbook/assets/6 (19).png>) ![](<.gitbook/assets/7 (16).png>)

### **Ceiling Mount:**

* Mount the PIR on ceiling to look downward over a door or window.
* When mounted on the ceiling, the PIR can only detect vertical movement against the PIR within the detection range.
* When mounted at 2.4\~3 meter height and looking down, the PIR has coverage of about **5** meters at ground level.
* Avoid mounting over 4 meters, which may affect detection performance.

![](<.gitbook/assets/8 (16).png>)

## _Installation_

* Decide on the location of the PIR if it is to be horizontal / vertical or ceiling mounted.
* After the installation site is selected, follow the steps described above to mount the PIR.
* Press the Test Button to enter Test Mode. Walk around the protected area noting when the LED lights up and check that the detection coverage is adequate.
* When detection coverage is found to be satisfying, installation is now completed.

### _Installation Recommendations_

\<Important NOTE>

* When deciding on the height of the PIR mounting site, remember to take the possible blind spot into consideration. The blind spot underneath the PIR enlarges proportionally to the height of the PIR mounting site.
* Please note that performance is affected by external factors, such as height of detected object, desired detection range, installation area…etc. The suggested mounting height could be adjusted according to actual installation environment factors.
* In a position such that an intruder would normally move across the PIR’s field of view from side to side.
* Where its field of view will not be obstructed e.g. by curtains, ornaments etc.

### **Limitations**

* Do not position a PIR to look directly at a door protected by a Door Contact, this could cause the Door Contact and PIR radio signals to be transmitted at the same instant when entering, canceling each other out.
* Do not install the PIR completely exposed to direct sunlight.
* Avoid installing the PIR in areas where devices may cause rapid change of temperature in the detection area, i.e. air conditioner, heaters, etc.
* Avoid large obstacles in the detection area.
* Not pointing directly at sources of heat e.g. fires or boilers, and not above radiators.
* Avoid moving objects in the detection area i.e. curtain, wall hanging etc.
