# VESTA-009

PIR Motion Sensor&#x20;

IR(P)-29 Series

The PIR detects infrared signature to pick up movements within an assigned area and signals the Control Panel to activate the alarm if an intruder crosses its’ path of detection.

The PIR consists of a two-part design made up of a cover and a base. The cover contains all the electronics and optics and the base provides a means of fixing. The base has knockouts to allow mounting on either a flat surface or in a corner situation

The PIR has a tamper switch which will be activated when the cover is opened. It can also alert you to signal communication problems and low battery situations.

The PIR is designed to give a typical detection range of 12 meters when mounted at 2 meters above ground.

The Pet-Immune models of IR-29 series PIR sensor further support the pet immunity feature and will not detect pets of up to 27 kg within the 7-meter range to minimize false alarm situations.



**The IR-29 Series PIR Sensor includes the following models**:

IR-29 / IR-29 F1 – PIR sensor with alkaline batteries

IRP-29 / IRP-29 F1 – Pet Immune PIR sensor with alkaline batteries

IR-29SL / IR-29SL-F1 – PIR sensor with lithium battery.

IRP-29SL / IRP-29SL-F1 – Pet Immune PIR sensor with lithium battery

## _**Identifying the Parts**_

<figure><img src=".gitbook/assets/1 (113).png" alt=""><figcaption></figcaption></figure>

**1. Test Button/LED indicator**

&#x20;   The test button is used for testing the radio performance and for learning purpose.

&#x20;   The LED indicator is used to indicate the status of the system.

**2. Battery Insulator**

**3. Supervision Enable/Disable Jumper Switch (JP2)**

![jumper open](<.gitbook/assets/1 (16).png>) ![jumper close](<.gitbook/assets/2 (16).png>)

**Jumper Off** if the jumper link is removed or “**parked**” on one pin.

**Jumper On t**he jumper link is inserted connecting the two pins

* When set as ON, Supervision is disabled. **(Factory default for 433AM frequency models)**
* When set as OFF, Supervision is enabled. **(Factory default for 868WF frequency models)**

{% hint style="info" %}
**433 FM** and **868FM frequency models** does not support JP2 Jumper Switch, Supervision is enabled and cannot be disabled.
{% endhint %}

**4. Sensitivity Increaser Jumper Switch (JP3)**

* When set as OFF, the PIR’s detection sensitivity is in normal level. **(Factory default for non-Pet-Immune models)**
* When set as ON, the PIRs detection sensitivity is high. (Factory default for Pet-Immune models)

**5. Tamper Switch**

The Tamper switch protects the PIR from unauthorized cover opening.

## _**Sleep Timer**_

The PIR has a “**sleep time**” of approximately 1 minute to conserve power. After transmitting a detected movement, the PIR will not retransmit for 1 minute; any further movement detected during this sleep period will extend the sleep time by another minute. In this way, continuous movement in front of a PIR will not unduly exhaust the battery.

## _**Supervision Function**_

If enabled (see table above), when the PIR is in Normal operation mode it will conduct a Self-test Periodically by transmitting a supervisory signal once every 30 to 50 minutes

If the Control Panel fails to receive the Supervisory signals transmitted from a certain PIR for a preset time, an “**Out-Of-Orde**r” fault message will be generated.

## _**Sensitivity Increaser Function**_

You can use the sensitivity increaser function to increase the PIR’s detection sensitivity. To increase detection sensitivity, connect the Jumper Switch (JP3), or the **ON** position (Factory default for Pet-Immune models). To maintain normal detection sensitivity, disconnect the Jumper Switch (JP3), or the **OFF** position (Factory default for non-Pet-Immune models).

## _**Test Mode**_

The PIR can be put into Test mode by pressing the Test Button on the front cover. In Test mode, it will disable the sleep timer and will enable the LED indicator to flash every time a movement is detected. Every time the Test Button is pressed, the PIR will transmit a test signal to the Control Panel for radio range test and enter the test mode for 3 mins. Test Mode will time out after 3 minutes..

## _LED Indicator_

In Normal operation mode, the LED Indicator lights up in the following situations (For F1 models, the LED flashes instead):

* When movement is detected under low battery condition
* When the cover is opened and the tamper switch is triggered.
* When movement is detected if the Tamper condition persists.
* When movement is detected under Test mode
* When the Test Button is pressed under tamper condition or if PIR is under low battery.

## _Battery_

IR-29 Series PIR Motions sensor uses with alkaline or lithium batteries as a power source:

* The alkaline-powered models use two alkaline AA 1.5 V batteries as its power source.
* The lithium-powered models use one 3V 2/3A (EL123AP) Lithium battery as its power source.

The PIR features a low battery detection function. If low battery voltage is detected, a low battery signal will be sent to the Control Panel along with regular signal transmissions for the Control Panel to display the status accordingly.

For each installation, the battery is installed in by the factory before shipment with an Insulator inserted.

{% hint style="info" %}
Note:

When changing batteries, after removing the old batteries, press the Tamper Switch twice to fully discharge before inserting new batteries.
{% endhint %}

## _Getting Started_

* Pull out the battery insulator to activate the battery.
* The LED indicator will flash for 30 seconds. (The PIR is warming up). During the warm up period, the PIR will not be activated. After the warm up period is over, the LED will turn off and the PIR will be ready for operation.
* Put the Control Panel into learning mode, refer to Control Panel manual for details.
* Press the test button on the front cover.
* Refer to Control Panel manual to complete the learn-in process.
* After the PIR is learnt-in, put the Control Panel into “**Walk Test**” mode, hold the PIR in the desired location, and press the Test button to confirm this location is within signal range of the Control Panel, refer to Control Panel manual to complete the Walk Test.
* When you are satisfied that the PIR work in the chosen location, you can proceed to mounting.

## _Mounting Method_

* The PIR is designed to be mounted on either a flat surface or in a corner situation with fixing screws and plugs provided.
* The base has knockouts, where the plastic is thinner and can be broken for mounting purpose. Two knockouts are for surface fixing and four knockouts are for corner fixing as shown in the picture.
* ![](<.gitbook/assets/3 (15).png>)
* For corner mounting, a triangular bracket is provided to add Back Tamper Protection. The bracket also includes two knockouts to mount on the wall.
* For surface mounting, an optional rotating bracket is provided for users to adjust the range of detection. With the rotating bracket, the IR-29 can be rotated 80 degrees horizontally and 70 degrees vertically to provide optimal coverage.

### **Corner mounting:**

1. Break through the four corner knockouts.
2. Using the four holes as a template, drill holes in the surface of the corner
3. Insert the wall plugs
4. Screw the base into the wall plug.
5. Screw the cover onto the base.

### **Corner mounting with triangular bracket:**

The triangular bracket can be mounted on the wall with provides screws or double-sided adhesive pads.

**Screw Mounting**

<figure><img src=".gitbook/assets/2 (122).png" alt=""><figcaption></figcaption></figure>

1. Break through the two knockouts on the triangular bracket.
2. Using the two holes as a template, drill holes in the surface of the corner. Insert wall plugs.
3. Screw the triangular bracket into the wall plugs with the two pointing sticks on top facing you.
4. Fit the PIR onto the hooks of the triangular bracket.

**Self-adhesive Mounting**

<figure><img src=".gitbook/assets/3 (112).png" alt=""><figcaption></figcaption></figure>

1. The mounting corner should be clean, dry, and smooth. Clean the mounting corner with a suitable degreaser if needed.
2. Two double-sided adhesive pads are attached to the triangular bracket before shipment.
3. Remove the protective covering from the double-sided adhesive pads.
4. Attached is the triangular bracket onto the desired corner with the two pointing sticks on top facing you.
5. Fit the PIR onto the hooks of the triangular bracket.

### **Surface mounting:**

<figure><img src=".gitbook/assets/2 (121).png" alt="" width="242"><figcaption></figcaption></figure>

1. Remove the fixing screw and cover assembly.
2. Break through the knockouts on the inside of the base
3. Using the holes as a template, drill holes in the surface.
4. Insert the wall plugs if fixing it into plaster or brick.
5. Screw the base into the wall plugs.
6. Screw the cover onto the base.

### **Surface mounting with rotating bracket (optional item, sold separately):**

The rotating bracket can be mounted on the wall with provides screws.

1. Screw the rotating bracket into the wall.
2. Fit the 3 hooks of the rotating bracket into the 3 holes of the base accordingly.
3. Rotate the bracket for the proper range of detection and tighten the fixing screw.

## _Installation_

* Decide on the location of the PIR and if it is to be corner or surface mounted.
* After the installation site is selected, follow the steps described above to mount the PIR.
* Press the Test Button to enter Test Mode. Walk around the protected area noting when the LED lights up and check that the detection coverage is adequate.
* When detection coverage is found to be satisfying, installation is now completed.

## _Installation Recommendations_

The PIR is designed to give a typical detection range of 12 meters when mounted at 2 meters above ground.

For Pet-Immune PIR series, it gives a typical PET IMMUNE range of 7 meters when mounted at 1.9-2.0 meters above ground. If mounted higher above ground, it gives a farther PET IMMUNE range.

To take full advantage of PIR, the following guidelines should be considered:

* **It is recommended to install the PIR in the following locations**
* Mount the detector at 1.9M-2.0M height for best performance:

![](<.gitbook/assets/6 (11).png>)

{% hint style="info" %}
Important NOTE



* For the most desirable performance of the Pet-Immune PIR series, remember to adjust the height of PIR mounting site with respect to the height of the tallest animal in the house. Taller-than-average pets may require the PIR to be mounted higher for the Pet Immunity purpose.
* When deciding on the height of the PIR mounting site, remember to take the possible blind spot into consideration. The blind spot underneath the PIR enlarges proportionally to the height of the PIR mounting site.
* Please note that performance is affected by external factors, such as the height of detected object, desired detection range, installation area…etc. The suggested mounting height could be adjusted according to actual installation environment factors.
* When IR-29 is mounted with a rotating bracket, it will not have the regular detection area (as in the above diagram), or the typical pet immune range.
{% endhint %}

* Mount where the animals cannot come to the detection area by climbing on furniture or other objects.
* Don’t aim the detector at stairways the animals can climb on.
* In a position such that an intruder would normally move across the PIR’s field of view from side to side.
* In a corner to give the widest view.
* Where its field of view will not be obstructed e.g. by curtains, ornaments etc.
* **Limitations**
* Do not position a PIR to look directly at a door protected by a Door Contact, this could cause the Door Contact and PIR radio signals to be transmitted at the same instant when entering, cancelling each other out.
* Do not install the PIR completely exposed to direct sunlight.
* Avoid installing the PIR in areas where devices may cause rapid changes of temperature in the detection area, i.e. air conditioner, heaters, etc.
* Avoid large obstacles in the detection area.
* Not pointing directly at sources of heat e.g. fires or boilers, and not above radiators.
* Avoid moving objects in the detection area i.e. curtain, wall hanging etc.

### Limitation

<figure><img src=".gitbook/assets/3 (111).png" alt=""><figcaption></figcaption></figure>
