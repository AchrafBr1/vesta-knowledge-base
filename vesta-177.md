# VESTA 177

**PIR Motion Sensor IR-35-2W / VESTA-177 Series**

**Introduction**

The PIR detects infrared signature to pick up movements within an assigned area and signals the Control Panel to activate the alarm if an intruder crosses its’ path of detection.

The PIR is designed to give a typical detection range of 12 meters when mounted at 2.5 meters above the ground. The PIR sensor also supports pet immunity feature and will not detect pets of up to 25 kg to minimize false alarm situation.

The PIR consists of a two-part design made up of a cover and a base. The cover contains all the electronics and optics and the base provides a means of fixing.

**The IR-35-2W Series PIR Sensor includes the following models:**

**IR-35-2W** – PIR Motion Sensor powered by two alkaline batteries

**IR-35SL-2W** – PIR Motion Sensor powered by one CR123 battery

**Parts Identification**

![](.gitbook/assets/0.jpeg)

1. **Test Button / LED Indicator**
   * The test button is used for testing the radio performance and for learning purpose.
   * The LED indicator is used to indicate the status of system.
2. **IR Sensor**

![](.gitbook/assets/1.jpeg)

**3. Battery Compartment**

**4. Pet Immunity Enable/Disable Jumper Switch (JP3)**

![](.gitbook/assets/2.jpeg)

**Jumper On**

![The jumper link is inserted, connecting the two pins.](.gitbook/assets/3.jpeg)



**Jumper Off**

![If the jumper link is removed or “parked” on one pin.](<.gitbook/assets/4 (1).png>)



* When set as ON, Pet Immunity is disabled (Factory default).
* When set as OFF, Pet Immunity is enabled.

1. **Sensitivity Increaser Jumper Switch (JP4)**
   *
     * When set as ON, the PIR’s detection sensitivity is high.
     * When set as OFF, the PIR’s detection sensitivity is in normal level. (Factory default)
2. **Tamper Switch**
3. **Bottom Fixing Screw**
   1. **IR-35-2W Battery Insulator Hole**

**9. IR-35SL-2W Battery Insulator Hole**

**Features**

* _**LED Indicator**_

In Normal operation mode, the LED Indicator will light up in the following situations:

*
  * When movement is detected under low battery condition
  * When the cover is opened and the tamper switch is triggered
  * When movement is detected if the tamper condition continues
  * When movement is detected under Test mode
  * When the Test Button is pressed under the tamper condition or if PIR is under low battery The LED will not flash if the PIR tamper and battery are normal and PIR is not under test mode.

If the LED flashes to indicate signal transmission, it will flash twice rapidly upon receiving acknowledgement from the Control Panel.

* _**Battery and Low Battery Detection**_

IR-35-2W Series PIR Motion sensor uses Alkaline or Lithium batteries as its power source:

* The IR-35-2W model uses two alkaline AA 1.5 V batteries as its power source.
* The IR-35SL-2W model uses one CR123 3V Lithium battery as its power source.

The PIR features low-battery detection function. If low battery voltage is detected, a low battery signal will be sent to the Control Panel along with the regular signal transmissions for the Control Panel to display the status accordingly.

For each installation, the batteries are installed in by the factory before shipment with an Insulator inserted.

* When changing the batteries, after removing the old batteries, press the Tamper Switch twice to fully discharge before inserting new batteries.
* _**Tamper Protection**_

The PIR is protected by a tamper switch which is compressed when the PIR is properly installed. When the PIR is removed from the mounted surface or the mounting bracket, or when its cover is opened, the tamper switch will be activated and the PIR will send a tamper open signal to the system control panel to remind the user of the condition. If any movement is detected when the tamper switch is open, the LED will light up.

* _**Supervision Function**_

When the PIR is in normal operation mode, it will conduct a self-test periodically by transmitting a supervisory signal once every 90 to 110 minutes.

If the Control Panel fails to receive the supervisory signals transmitted from a certain PIR for a preset time, an “**Out-Of-Orde**r” fault message will be generated.

* _**Test Mode**_

The PIR can be put into test mode by pressing the Test Button. In test mode, it will disable the sleep timer and will enable the LED indicator to light up every time a movement is detected. Every time the Test Button is pressed, the PIR will transmit a test signal to the Control Panel for radio range test and enter the test mode for 3 mins. Test Mode will time out after 3 minutes.

* _**Sleep Timer**_
  * The PIR has a “**sleep time**” of approximately **1 minute** to conserve power.
  * Depending on the Sleep Mode setting (Normal or Optimized), the PIR will enter **sleep time** for **1 minute** after transmitting a detected movement or 3 detected movements within 1 minute.
  * During the **1 minute sleep time**, the PIR will not retransmit any signals; any further movement detected during this sleep period will extend the sleep time by another minute. In this way, continuous movement in front of the PIR will not unduly exhaust the battery.
* The sleep mode setting is remotely configurable. When sleep mode is set to Normal, the PIR will enter sleep time for 1 minute after transmitting a detected movement. When sleep mode is set to Optimized, the PIR will enter sleep time for 1 minute after transmitting 3 detected movements within 1 minute. Please refer to _**Remote Setting**_ section below for details.
* _**Pet Immunity Function**_
  * The PIR sensor supports pet immunity feature and will not detect pets of up to 25 kg to minimize false alarm situation.
  * The Pet Immunity function can be enabled / disabled by setting the Jumper Switch (JP3) position. When the Jumper Switch (JP3) is set to ON, Pet Immunity is disabled (factory default). When the Jumper Switch (JP3) is set to OFF, Pet Immunity is enabled.
  * Pet Immunity function can also be remotely configured. Please refer to _**Remote Setting**_ section below for details.
* _**Sensitivity Increaser Function**_
  * You can use the sensitivity increaser function to increase the PIR’s detection sensitivity.
  * To increase detection sensitivity, set the Jumper Switch (JP4) to ON. To maintain normal detection sensitivity, set the Jumper Switch (JP4) to OFF (Factory default).
  * The PIR’s detection sensitivity can also be remotely configured. Please refer to _**Remote Setting**_ section below for details.
* _**Remote Setting**_
  * The PIR motion sensor supports remote setting of pet immunity, sensitivity, and sleep mode.
  * When the PIR is powered on, its pet immunity function and sensitivity are determined by the JP3 and JP4 settings. Users can either adjust jumper settings or remotely change the pet immunity and sensitivity settings from the Control Panel. Remote setting will overwrite the jumper settings.

**Control Panel Webpage**

1. On the Panel local webpage, go to the Edit Device page, and input the PIR motion sensor configuration in the Sensor Setting section. Click OK to confirm.

Please refer to the table below for configuration details. For example, if you want to enable Pet Immunity and set Sensitivity level and sleep mode to normal, you can input 02.

| **IR Configuration** | **Pet Immunity** | **Sensitivity** | **Sleep Mode**           |
| -------------------- | ---------------- | --------------- | ------------------------ |
| 00                   | No               | Normal          | Normal (1 detection)     |
| 01                   | No               | High            | Normal (1 detection)     |
| 02                   | Yes              | Normal          | Normal (1 detection)     |
| 03                   | Yes              | High            | Normal (1 detection)     |
| 04                   | No               | Normal          | Optimized (3 detections) |
| 05                   | No               | High            | Optimized (3 detections) |
| 06                   | Yes              | Normal          | Optimized (3 detections) |
| 07                   | Yes              | High            | Optimized (3 detections) |

1. Press the Test button once on the PIR motion sensor to send a signal to the Control Panel, and the new settings will be applied immediately. If the button is not pressed, the new settings will be applied upon next signal transmission, i.e., transmission of the supervisory signal or IR trigger signal.



**Home Portal Server**





1. On Home Portal Server, go to the Device setting page, click the IR-35-2W device row and select “IR Configuration.”
2. Select the Pet Immunity function (Enable/Disable), Sensitivity (High/Normal), and Sleep Mode Optimized function (Normal/Optimized) from the drop-down lists, click “Submit” to confirm the setting.
3. Press the Test button once on the PIR motion sensor to send a signal to the Control Panel, and the new settings will be applied immediately. If the button is not pressed, the new settings will be applied upon next signal transmission, i.e., transmission of the supervisory signal or IR trigger signal.

* _**Getting Started**_
  * Pull out the battery insulator to activate the batteries.
  * The LED indicator will flash for 30 seconds (the PIR is warming up). During the warm-up period, the PIR will not be activated. After the warm-up period is over, the LED will turn off and the PIR will be ready for operation.
  * Put the Control Panel into learning mode (refer to Control Panel manual for details).
  * Press the test button.
  * Refer to Control Panel manual to complete the learn-in process.
  * After the PIR is learnt-in, put the Control Panel into “**Walk Test**” mode; hold the PIR in the desired location, and press the Test button to confirm that this location is within the signal range of the Control Panel (refer to Control Panel manual to complete the Walk Test).
  * When you are satisfied that the PIR works well at the chosen location, you can proceed with mounting.

**Installation**

_**Installation Guideline**_

![](<.gitbook/assets/20 (1).png>)

**IR-35-2W Detection Range**

3

* ![](.gitbook/assets/21.png)_**Mounting Method**_
* The PIR is designed to be mounted either on a flat surface or in a corner.
* The base has two knockouts, where the plastic is thinner and can be broken for surface mounting.
* A mounting bracket includes two central screw holes for fixing the PIR onto a surface and four side screw holes

![for fixing the PIR onto a corner.](.gitbook/assets/22.jpeg)



* For surface mounting, an optional rotating bracket is provided for users to adjust the range of detection. With the rotating bracket, the IR-35-2W can be rotated 80 degrees horizontally and 70 degrees vertically to provide the optimal coverage.
  * **Surface Mounting without the mounting bracket:**
    1. Remove the bottom fixing screw and cover assembly.
    2. Break through the two knockouts from the inside of the base
    3. Use the holes as a template and drill holes into the surface to be mounted.
    4. Insert the wall plugs if the PIR is to be fixed onto plaster or bricks.
    5. Screw the base onto the wall plugs.
    6. Screw the cover onto the base.
* **Surface Mounting with the mounting bracket:**
  1. Use the two central screw holes on the bracket as a template and drill holes into the surface to be mounted.
  2. Insert the wall plugs if the PIR is to be fixed onto plaster or bricks.
  3. Screw the mounting bracket onto the wall plugs with the two pointing sticks on top and facing you.
  4. Fit the PIR onto the hooks of the mounting bracket.



* **Surface mounting with the rotating bracket (optional item, sold separately):**
  * For surface mounting, an optional rotating bracket is provided for users to adjust the range of detection. With the rotating bracket, the IR-35-2W can be rotated 80 degrees horizontally and 70 degrees vertically to provide the optimal coverage.
  * The rotating bracket can be mounted on the wall with the provided screws.
    1. Screw the rotating bracket into the wall.
    2. Fit the 3 hooks of the rotating bracket into the 3 holes of the base accordingly.
    3. Rotate the bracket for the proper range of detection and tighten the fixing screw.
*   _**Installation Recommendations**_

    * **It is recommended to install the PIR in the following locations:**
      * At a height of 2.3-2.5 meters for best performance:
      * At locations where animals cannot come to the detection area by climbing on furniture or other objects.
      * Don’t aim the sensor at stairways where animals can climb on.
      * At a position such that an intruder would normally move across the PIR’s field of view from side to side.
      * In a corner to give the widest view.
      * At a position where its field of view will not be obstructed by e.g., curtains, ornaments etc.
    * **Limitations**



<figure><img src=".gitbook/assets/image (1).png" alt=""><figcaption><p>Do not install outdoors. / Avoid large obstacles in the detection area.</p></figcaption></figure>



<figure><img src=".gitbook/assets/image (2).png" alt=""><figcaption><p>Do not install the PIR completely exposed to direct sunlight. / Avoid vapor or high humidity that can cause condensation.</p></figcaption></figure>
