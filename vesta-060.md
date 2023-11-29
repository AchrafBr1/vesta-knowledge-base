# VESTA 060

Door Contact / Shock Vibration Sensor (DCSV-23)

DCSV-23 is a Door Contact / Shock Sensor is capable of sending a door open signal to the Control Panel upon detection of door/window opening or shock/vibration detection.

![DCSV-23ZBS](<.gitbook/assets/0 (13).jpeg>)The Door Contact / Shock Vibration Sensor design consists of a cover and base. The cover contains all electronics and the base provides a means for fixing the device. An enclosed PCB tamper switch provides tamper protection against unauthorized device opening and/or removal.

Parts Identification

1. **LED Indicator / Test Button**

* Press the button once to send a learn code or enter test mode for 3 minutes.

1. **Cover Fixing Screw**
2. **Mounting Holes**
3. **Tamper Switch**

* Provides tamper protection against unauthorized device opening and/or removal from mounting surface.

1. **Battery Insulator**
2. **Detection Mode Jumper (JP3)**

* Refer to section _**Shock/Vibration Detection Mode**_ for details.

1. **Sensitivity Adjustment Jumper (JP4,JP5)**

* Refer to section _**Sensitivity Adjustment**_ for details.

1. **Reed Switch Jumper (JP1)**

* Refer to section _**Reed Switch**_ for details.

1. **Battery Compartment**
2. **Magnet**
3. **Magnet Screw hole**
4. **Magnet Spacer**

Features

Jumper **ON** (The jumper link is inserted): The Reed Switch is _**disabled.**_

![jumper open](<.gitbook/assets/3 (21).png>)

Jumper **OFF** (The jumper link is removed or parked on one pin): The Reed Switch is _**enabled**_ and device now works as a Door Contact. (_**Default**_)

* The Reed Switch must be disabled if the device is not being used as a Door Contact.
* _**Shock/Vibration Detection Mode**_
* The device’s shock/vibration detection feature may be triggered according to different mode selected.
* **Single Pulse Mode**

The device is triggered by a single pulse detection which exceeds detection threshold.

* **Pulse Count / Accumulated Vibration Mode**

The device is triggered by either of the following condition:

1. When **3** pulse counts are detected within **20** **seconds**.
2. When accumulated minor vibration detected with **2 minutes** exceeds detection threshold.

* The detection modes are selected using jumper switch JP3:

![jumper close](<.gitbook/assets/4 (20).png>)Jumper **ON** (The jumper link is inserted): **Single Pulse Mode**. (_**Default**_)

![jumper open](<.gitbook/assets/5 (13).png>)Jumper **OFF** (The jumper link is removed or parked on one pin): **Pulse Count / Accumulated Vibration Mode**

* _**Sensitivity Adjustment**_
* Use the jumper switch JP4 and JP5 to determine the sensitivity required to activate the Door Contact / Shock Vibration Sensor. Refer to table below to select desired sensitivity.

| JP4 | JP5 | Shock sensitivity      |
| --- | --- | ---------------------- |
| ON  | OFF | Low                    |
| OFF | ON  | Medium (_**default**_) |
| ON  | ON  | High                   |

* _**Battery**_
* The Door Contact / Shock Vibration Sensor uses one CR123 3V Lithium battery as its power source. The battery is installed in the battery compartment with a battery insulator inserted. To activate the battery, simply pull out the battery insulator.
* The Door Contact / Shock Vibration Sensor can detect low battery condition. When the battery voltage is low, a low battery signal will be sent to the Control Panel to notify the condition. The LED will light up when the Door Contact / Shock Vibration Sensor is activated under low battery status. When the battery is exhausted, the Door Contact / Shock Vibration Sensor will stop all function, the LED will flash every 4 seconds.
* When changing batteries, after removing the old batteries, press the Tamper Switch twice to fully discharge before inserting new batteries.
* _**Tamper Protection**_
* The Door Contact / Shock Vibration Sensor is protected by a tamper switch which is compressed against the mounting surface when the Door Contact / Shock Vibration Sensor is mounted. Whenever the Door Contact / Shock Vibration Sensor is removed from mounted surface or cover is opened, the tamper switch will be activated and the device will send a tamper open signal to remind the user of the condition.
* _**Supervision**_
* The Door Contact / Shock Vibration Sensor will automatically transmit Supervisory signal periodically to the Control Panel at random intervals of 30-50 minutes.
* If the Control Panel has not received the signal from the Door Contact / Shock Vibration Sensor for a preset period time, the Control Panel will indicate the particular Door Contact / Shock Vibration Sensor is experiencing an out-of-signal problem.
* _**Test Mode**_
* Under Normal Mode, press the Test Button to transmit a test signal and learning code to the Control Panel. The Door Contact / Shock Vibration Sensor will also enter the Test Mode for 3 minutes.
* Under Test Mode, the LED will light up whenever the Door Contact / Shock Vibration Sensor is activated.
* Each additional Test Button press will reset Test Mode time to 3 minutes.
* _**Getting Started**_
* Remove the battery insulator on the Door Contact / Shock Vibration Sensor to power on.
* Put the Control Panel into Learning Mode (Please refer to panel operation manual)
* Press the Test Button on the Door Contact / Shock Vibration Sensor
* Refer to your Control Panel operation manual to complete the learn-in process.
* After the Door Contact / Shock Vibration Sensor is learned-in, place the Control Panel into (**Walk Test**) mode, hold the Door Contact / Shock Vibration Sensor in the desired location, and press the Test Button to transmit test signal to Control Panel. If the Control Panel is within Door Contact / Shock Vibration Sensor signal range, the panel will display Door Contact / Shock Vibration Sensor information accordingly.
* Proceed with mounting and installation once you are satisfied that the Door Contact / Shock Vibration Sensor location functions properly.

Installation

* _Mounting the Door Contact / Shock Vibration Sensor_

![](<.gitbook/assets/6 (9).png>) **Mounting as Door Contact:**

* The Door Contact / Shock Vibration Sensor should be installed either upright or inverted to ensure the rib-marked side faces the magnet.
* The distance between Door Contact / Shock Vibration Sensor and the magnet should be no more than 15mm when the door is closed.
* Avoid mounting Door Contact / Shock Vibration Sensor on metallic surface. If mounting on metallic surface, ensure to test whether Door Contact / Shock Vibration Sensor can be triggered when door is opened.
* Mount the device as high as possible.

**Mounting as Shock Vibration Sensor:**

* Mount on _**Concrete, safe deposit box, window frames.**_
* When mounted on door/window frame, the device also serves as Door Contact.
* Refer to table below for information on shock/vibration detection range and sensitivity setting according to different surface materials. Use the sensitivity adjustment jumper to select desired sensitivity.

|                                                | Glass Window                             | Door                                  | Concrete Wall | Safety Box               |   |
| ---------------------------------------------- | ---------------------------------------- | ------------------------------------- | ------------- | ------------------------ | - |
| Thickness                                      | >5mm                                     | <40mm                                 | -             | >3mm                     |   |
| Material                                       | <p>Regular/Tempered/</p><p>Laminated</p> | Wood/Steel                            | Concrete      | Steel + Silicon Dioxide  |   |
| Install Location                               | Window Frame                             | Door Frame                            | Wall          | 2cm away from door pivot |   |
| Detection Mode                                 | Single Pulse Mode                        |  Pulse Count / Accumulated Vibration |               |                          |   |
| <p>Shock Sensitivity</p><p>(coverage area)</p> | Low                                      | 2000mm                                | 1000mm        | 500mm                    | - |
| Medium                                         | 3000mm                                   | 2000mm                                | 1500mm        | -                        |   |
| High                                           | 4000mm                                   | 3000mm                                | 2000mm        | 1400mm                   |   |

![](<.gitbook/assets/7 (6).png>)

* _Mounting Procedure_

1. Use the 2 mounting holes on back cover as template for positioning.
2. Use the provided wall plugs for window frames/ concrete wall/safe deposit box installation.
3. Screw the Door Contact / Shock Vibration Sensor into the wall plugs. (Drilling is recommended when mounting on steel such as safe deposit box, or you can also use the provided sticker in the package).
4. Fit magnet on the door using small piece of double sided adhesive tape or with provided screws.
5. To mount the Magnet, use the 2 Magnet Screw holes as a template for appropriate hole positioning.

< Note >

* The magnet must align with the rib-mark side of the Door Contact. If required, apply the magnet spacer to the back of the magnet to better align the magnet to the rib marks.

1. Screw the magnet and insert the two white caps into the magnet screw holes for aesthetic integrity.
2. Installation is now complete.

\<NOTE>

* Don’t mount the device on surface materials where frequent vibration occurs, to prevent false alarming.
* ![](<.gitbook/assets/8 (6).png>)When mounting on safety box, mount the Door Contact / Shock Sensor no more than 2cm away from the door pivot (refer to the below picture).
