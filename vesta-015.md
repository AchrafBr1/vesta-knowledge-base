# VESTA-015

**IRD-23 / IRD-23SL**

## **Dome PIR Motion Sensor**

The Dome PIR Motion Sensor is designed to be mounted on the ceiling to provide a 360 ∘detection coverage without blind spots to pick up movements within an assigned area and signal the Control Panel to activate the alarm if an intruder crosses its path of detection.

The PIR consists of a two-part design made up of a PIR main body and a back cover for wall mounting. The main body contains all the electronics and optics, and the base provides a means of installation.

The PIR main body has an anti-sabotage tamper switch, which will be activated when the main body is removed from the back cover to prevent unauthorized access and removal from the mounting surface. The PIR can also alert you to signal communication problems and low battery situations.

The Dome PIR includes 2 models:

IRD-23: Powered by 2 AA alkaline 1.5V batteries

IRD-23SL: Powered by 1 CR123A lithium 3V battery

## _**Identifying the parts.**_

**1. Test Button aka LED indicator**

The test button also doubles as the LED indicator. The test button is used for testing the radio performance and for learning purposes. The LED indicator is used to indicate the status of the system.

2. **IR Sensor**

<figure><img src=".gitbook/assets/1 (115).png" alt=""><figcaption></figcaption></figure>

3. **Sensitivity Increaser Jumper Switch (JP3)**

It is a 2-pin jumper switch:

* If the jumper is OFF (if the jumper link is removed or “**parked”** on one pin),

&#x20;            the PIR’s detection sensitivity is at a normal level. (**Factory default**)

* If the jumper is ON, the PIR’s detection sensitivity is high.



<figure><img src=".gitbook/assets/2 (124).png" alt=""><figcaption></figcaption></figure>

4. **Tamper Switch**

The Tamper switch protects the PIR from removal from the mounted location.

**5. Battery Compartment**

IRD-23: 2 AA alkaline 1.5V batteries.

IRD-23SL: 1 CR123A lithium 3V battery

6. **Mounting Holes**
7. **Hooks**
8. **Ceiling Mounting Knockouts (Inside)**

![](<.gitbook/assets/3 (23).jpeg>)

## _**LED Indicator**_

In Normal operation mode, the LED Indicator will not light except in the following situations:

* When the PIR is in low battery condition, every time it transmits a detected movement, the LED will light up for about 2 seconds.
* When the cover is opened and the tamper switch is violated, the LED will light up for 2 sec. to indicate it is transmitting the “**Tamper**” signal.
* When the Tamper condition persists, every time it transmits a detected movement, the LED will light up.
* When if the PIR is in Test mode, the LED will light up every time a movement is detected.

## _**Sleep Timer**_

The PIR has a “**sleep time**” of approximately 1 minute to conserve power. After transmitting a detected movement, the PIR will not retransmit for 1 minute; any further movement detected during this sleep period will extend the sleep time by another minute. In this way, continuous movement in front of a PIR will not unduly exhaust the battery.

## _**Supervision Function**_

The PIR transmits a supervisory signal once every 30 to 50 minutes. If the Control Panel fails to receive the Supervisory signals transmitted from a certain PIR for a preset time, an “**Out-Of-Orde**r” fault message will be generated.

## _**Sensitivity Increaser Function**_

You can use the sensitivity increaser function to increase the IR’s detection sensitivity. To increase detection sensitivity, please set JP3 Jumper to **ON** position. To maintain the normal detection sensitivity, set the JP3 Jumper to **OFF** position (factory default).

## _**Test mode**_

The PIR can be put into Test mode by pressing the Test Button, aka LED on the front cover. In Test mode, it will disable the sleep timer and will enable the LED indicator to flash every time a movement is detected. Each time the Test Button is pressed, the PIR will transmit a test signal to the Control Panel for a radio range test and enter the test mode for 3 mins. It will exit Test Mode automatically after 3 mins and return to normal mode.

## _**Battery**_

The PIR uses different batteries depending on the PIR Model:

IRD-23: 2 AA alkaline 1.5V batteries

IRD-23SL: 1 CR123A lithium 3V battery

The batteries are included in the package. The PIR feature a low battery detection function. A low battery signal will be sent to the Control Panel along with regular signal transmissions for the Control Panel to display the status accordingly.

{% hint style="warning" %}
Note:

When changing batteries, after removing the old batteries, press the Tamper Switch twice to fully discharge before inserting new batteries.
{% endhint %}

## _**Tamper Switch**_

The PIR has a tamper switch located on the back of the PIR main body. When the PIR is properly installed on the back cover, the tamper switch will be compressed. When the PIR is removed from the back cover, the tamper switch will be activated and trigger the PIR to send a tamper open signal to the Control Panel.

## _**Getting Started**_

* Insert the battery into the battery compartment.
* The LED indicator steadily flashes for 30 seconds. (The PIR is warming up). During the warming period, the PIR will not be activated. It is recommended that you stay away from the detection area during this time. After the warming period is over, the light will turn off, and the PIR will be ready for operation.
* Put the Control Panel into learning mode; refer to the Control Panel manual for details.
* Press the learn/test button on the front cover.
* If the Control Panel receives a PIR signal, it will display the information accordingly. refer to the Control Panel manual to complete the learning process.
* After the PIR is learnt-in, put the Control Panel into “**Walk Test**” mode, hold the PIR in the desired location, and press the Test button to confirm this location is within signal range of the Control Panel.
* When you are satisfied that the PIR work in the chosen location, you can proceed with installation.

## _**Installation Guideline**_

* The PIR is designed to be mounted on the ceiling
* When mounted at 2.7 meter height, the PIR provides detection coverage of a 360° circle wth approximately **6** meter diameter.
* When mounted at 4 meter height, the PIR provides detection coverage of a 360° circle wth an approximately **8** meter diameter.
* For optimal performance, rotate the PIR so that the intruder would move across its detection area from side to side.

{% hint style="warning" %}
Note:

To find out the “sides” of the PIR. Hold the PIR with the LED indicator pointing upward, and the left and right sides of the PIR are considered the PIR’s sides. The PIR sensor is most sensitive when the intruder is moving from one side to the other
{% endhint %}

* Refer to the diagrams below for more information.

![](<.gitbook/assets/4 (43).png>)

* **It is recommended to install the PIR in the following locations.**
  * In a ceiling area with full view of its detection coverage, unobstructed by appliances and furniture.
  * Near the entrance of a room or house to monitor entry activity.
* **Limitations**
  * If a door is already protected by a Door Contact, do not install the PIR too close to the Door. If the Door contact and the PIR is triggered and transmit a signal at the same time, the signals may collide and cancel each other.
  * Do not install the PIR exposed to direct sunlight.
  * Avoid installing the PIR in areas where devices may cause rapid changes of temperature in the detection area, i.e. air conditioners, heaters, etc.
  * Avoid large obstacles in the detection area.
  * Do not point directly at sources of heat e.g. Fires or boilers, and do not point directly at radiators.
  * Avoid moving objects in the detection area i.e. curtains, wall hanging etc.
* After the installation site is selected, follow the steps below to mount the PIR.
* Press the Test Button to enter Test Mode. Walk around the protected area, noting when the LED lights up, and check that the detection coverage is adequate.
* When detection coverage is found to be satisfying, installation is now completed.

## _**Mounting Method**_

* The PIR is designed to be mounted on the ceiling
* The back cover has 4 knockouts where the plastic is thinner for ceiling mounting.
* After finishing PIR learning and the walk test, proceed to mount the PIR according to the instructions below.

1. Break through the 4 knockouts on the inside of the back cover
2. Use the knockout holes as a template, drill holes in the ceiling, and insert wall plug if required.
3. Screw the back cover onto the ceiling according to drilled holes.
4. The back cover has numbers on the insides to mark the mounting hole number, which corresponds to the mounting hook number on the back of the main body. Align the mounting hole with the mounting hook when installing. Refer to the figure below for mounting hook and hole location.

![PIR Main Body Rear View                                                                                              Back Cover Inside View](<.gitbook/assets/5 (20).jpeg>)

5. Install the PIR main body onto the back cover. Fit the hooks on the back cover to the mounting holes on the PIR main body
6. &#x20;Rotate the PIR main body clockwise to lock the hooks into the mounting hole. Refer to the figure below.
7. PIR mounting is now complete.

![](<.gitbook/assets/6 (25).jpeg>)
