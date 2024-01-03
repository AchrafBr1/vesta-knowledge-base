# VESTA 358

**Wired PIR Motion Sensor (IR-35-BUS)**

**Introduction**

The PIR detects infrared signature to pick up movements within an assigned area and signals the Control Panel over BUS to activate the alarm if an intruder crosses its’ path of detection.

The PIR is designed to give a typical detection range of 12 meters when mounted at 2.5 meters above ground. The PIR sensor also supports pet immunity feature and will not detect pets of up to 25 kg to minimize false alarm situation.

The PIR consists of a two-part design made up of a cover and a base. The cover contains all the electronics and optics and the base provides a means of fixing.

**Parts Identification**

![](<.gitbook/assets/0 (113).jpeg>)

1. **Test Button / LED Indicator**
   * Press the test button once to enter test mode for 3 minutes.
   * The LED indicator is used to indicate the status of system.
2. **IR Sensor**
3. **Terminal Resistor Jumper Switch**

When the PIR motion sensor is connected as the furthest BUS device on a BUS line, please set the PIR motion sensor's terminal resistor jumper and the first BUS device’s (usually the Hybrid Panel’s) Jumper Switch to ON to serve as terminating resistors. The connected BUS line’s communication ability will be enhanced.

*
  *
    * If the jumper is OFF (the jumper link is removed or “parked” on one pin), the communication ability is in normal level.
      * If the jumper is ON, the the communication ability will be enhanced.

1. **BUS Terminal**
2. **Pet Immunity Enable/Disable Jumper Switch (JP3)**
   * When set as ON, Pet Immunity is disabled (Factory default).
   * When set as OFF, Pet Immunity is enabled.

![](<.gitbook/assets/1 (83).png>)

**Jumper On**

![](<.gitbook/assets/2 (80).jpeg>)

The jumper link is inserted, connecting the two pins.

**Jumper Off**

![](<.gitbook/assets/3 (75).jpeg>)

The jumper link is removed or “**parked**” on one pin.

**6. Sensitivity Increaser Jumper Switch (JP4)**

*
  * When set as ON, the PIR’s detection sensitivity is high.
  * When set as OFF, the PIR’s detection sensitivity is in normal level. (Factory default)

1. **Tamper Switch**
2. **Bottom Fixing Screw**

1

**Features**

![](<.gitbook/assets/4 (66).jpeg>)

* _**LED Indicator**_

In Normal operation mode, the LED Indicator will flash 3 times in the following situations:

* When the cover is opened and the tamper switch is triggered.
* When movement is detected if the Tamper condition persists.
* When movement is detected under Test mode
* When the Test Button is pressed under tamper condition

The LED will not flash if the PIR tamper is normal and PIR is not under test mode.

![](<.gitbook/assets/5 (45).jpeg>)

* _**Tamper Protection**_

The PIR is protected by a tamper switch which is compressed when the PIR is properly installed. When the PIR is removed from mounted surface or mounting bracket, or its cover opened, the tamper switch will be activated and the PIR will send a tamper open signal to the system control panel to remind the user of the condition. If movement is detected when the tamper switch is open, the LED will flash 3 times.

![](<.gitbook/assets/6 (51).jpeg>)

* _**Supervision Function**_

After installation, the PIR will automatically transmit Supervisory signals periodically to the Control Panel at random intervals of 20-30 seconds.

![](<.gitbook/assets/7 (66).png>)

* _**Test Mode**_

The PIR can be put into Test mode by pressing the Test Button. Every time the Test Button is pressed, the PIR will transmit a test signal to the Control Panel for radio range test and enter the test mode for 3 minutes. Test Mode will time out after 3 minutes.

![](<.gitbook/assets/8 (66).png>)

* _**Pet Immunity Function**_
  * The PIR sensor supports pet immunity feature and will not detect pets of up to 25 kg to minimize false alarm situation.
  * The Pet Immunity function can be enabled/disabled by setting the Jumper Switch (JP3) position. When the Jumper Switch (JP3) is set to ON, Pet Immunity is disabled (factory default). When the Jumper Switch (JP3) is set to OFF, Pet Immunity is enabled.
  * The Pet Immunity function can also be adjusted by remote setting, please refer the _**Remote Setting**_ section below.
* _**Sensitivity Increaser Function**_
  * You can use the sensitivity increaser function to increase the PIR’s detection sensitivity.
  * To increase detection sensitivity, set the Jumper Switch (JP4) to ON. To maintain normal detection sensitivity, set the Jumper Switch (JP4) to OFF (Factory default).
  * The Sensitivity function can also be adjusted by remote setting, please refer the _**Remote Setting**_ section below.
* _**Remote Setting**_
  * The PIR motion sensor supports remote setting of pet Immunity and sensitivity.
  * When the PIR is powered on, its pet immunity function and sensitivity are determined by the JP3 and JP4 settings. Users can either adjust jumper settings or remotely change the pet immunity and sensitivity settings from the Control Panel. Remote setting will overwrite jumper settings.

**Control Panel Webpage**:

*
  *
    1. On the Panel local webpage, go to the Edit Device page.
    2. Input the PIR motion sensor configuration in the Sensor Setting section. Click OK to confirm.
    3. Please refer to the table below for configuration details. For example, if you want to enable Pet Immunity and set Sensitivity level to high, you can input 03.

![](<.gitbook/assets/9 (63).png>) ![](<.gitbook/assets/10 (64).png>)

| **IR Configuration** | **Pet Immunity** | **Sensitivity** |
| -------------------- | ---------------- | --------------- |
| 00                   | Disable          | Normal          |
| 01                   | Disable          | High            |
| 02                   | Enable           | Normal          |
| 03                   | Enable           | High            |

**Home Portal Server**:

*
  *
    *
      1. On Home Portal Server, go to the Device setting page, click the IR-35 device row and select “IR Configuration.”
      2. Select the Pet Immunity function (Enable/Disable) and Sensitivity (High/Normal) from the drop-down lists, click “Submit” to confirm setting.
* _**Power Supply**_
  *
    * When IR-35-BUS is hardwired to a Hybrid Panel, 13.5V power supply can be provided by the Hybrid Panel.
* _**Caution**_
  * Wiring of the PIR motion sensor should only be performed by certified technician with proper knowledge and training in electric equipment.
  * Before installation or any maintenance work, make sure the power supply has been disconnected.

![](<.gitbook/assets/11 (34).jpeg>) ![](<.gitbook/assets/12 (31).jpeg>) ![](<.gitbook/assets/13 (43).png>)

2

* ![](<.gitbook/assets/14 (43).png>)_**PIR Motion Sensor Wiring**_
  * Before connecting the PIR motion sensor to the system bus, please switch the power off.
  * To assist with cable connections, the terminal blocks on each BUS system module are color-coded.

![](<.gitbook/assets/15 (27).jpeg>)

| **Red**    | VDD  |
| ---------- | ---- |
| **Black**  | GND  |
| **Yellow** | 485A |
| **Green**  | 485B |

* Multiple BUS devices can be connected in series to the Hybrid Panel. For optimal communication of the the connected BUS line devices, ensure the terminal resistor jumper switches of the first (usually the Hybrid Panel) and the furthest BUS devices on a BUS line are set to ON to serve as terminating resistors. Be sure to only enable the aforementioned 2 jumper switches, and

do not set the jumper switches to ON for any other BUS devices in between.

_\<NOTE>_

*
  * The pluggable design of BUS terminal blocks improves upon installation efficiency. Before wiring, you can remove the terminal blocks from the PCB board for ease of use, and plug in again after wiring.
  * After unplugging the terminal, when re-installing the terminal back to the board, make sure to install the terminal in the same direction to avoid potential hazards.
* Incorrect connections will result in failure or improper operation. Inspect wiring and ensure proper connections before applying power.

![](<.gitbook/assets/16 (45).png>)

* _**Getting Started – Learning the PIR Motion Sensor into the Control Panel**_

Please follow the steps below to learn the device into the Hybrid Panel.

Step 1. Connect the device to the Panel. Then, power the Panel on.

Step 2. On the Panel’s webpage, click “**Learning**” to enter learn page.

Step 3. Click “**Start**” to enter learning mode.

Step 4. Click “**Add**” to include the device into the Panel.

Step 5. If the device is successfully learnt into the Panel, it will be displayed in the “Learned Device” section.

![](<.gitbook/assets/17 (24).jpeg>)

* _**Identification**_

The “**Identify**” function is used to localize a specific BUS device in the BUS wired system. This function is helpful in distinguishing which device is which especially in a large installation where numerous BUS devices are included.

To locate the PIR motion sensor in the BUS system:

**Step 1.** On Hybrid Panel’s webpage, click “Identify” under the device list after the IR Camera’s device column entry.

**Step 2.** If the PIR motion sensor receives the signal from the Hybrid Panel, the webpage will display a success message and PIR motion sensor’s LED indicator will flash 10 times to indicate where it is to the user.

![](<.gitbook/assets/18 (44).png>)

_\<NOTE>_

* If a timeout message is displayed on the webpage, it means the PIR motion sensor did not receive the signal from the Panel.

Please check whether the wired connection between the Panel and PIR motion sensor is connected properly.

3

* ![](<.gitbook/assets/19 (11).jpeg>)_**Walk Test**_
  * To make sure the PIR motion sensor is able to communicate with the Panel after it is learned-in, place the Control Panel in Walk Test mode and press the Test button on IR-35-BUS to transmit a test signal to the Control Panel.
  * When the Panel receives the test signal, it will beep once and display the PIR motion sensor’s information accordingly on the top of the device list.

![](<.gitbook/assets/20 (32).png>)

_\<NOTE>_

*
  * If there is no response from the Panel after the press of test button, it means the Panel did not receive the test signal from the device.

Please check whether IR-35-BUS is connected properly to the Panel within appropriate wiring distance.

* _**Factory Reset**_

The PIR motion sensor can be factory reset to default pet Immunity and sensitivity based on JP3 and JP4 settings. Follow the steps below to proceed.

Step 1. Disconnect the power supply from the PIR motion sensor.

Step 2. Press and hold the Test Button of the PIR motion sensor, and then power on the device, Continue to hold the Test Button for 5 seconds. Release the Test Button after the LED flashes 5 times. Factory Reset is complete.

**Installation**

* _**Installation Guideline**_
  * The PIR is designed to be mounted on either a flat surface or in a corner.
  * The detection range is up to 12 meters if the PIR is mounted 2.3-2.5 meters above the&#x20;
  * When Pet-Immunity function is enabled, the PIR will not detect pets up to 25kg when mounted at 2.3-2.5 meters above the ground. If required, you can adjust the height of the PIR according to the size of your pet for optimal pet immunity performance. Higher installation location will provide larger pet-immune space, but will increase the blind spot under the PIR.
  * When the PIR is mounted with the rotating bracket, it will not have the regular detection area (as in the diagram below), or the typical pet immune range.
  * After the installation site is selected, press the Test Button to enter Test Mode. Walk around the protected area noting when the LED lights up and check that the detection coverage is adequate.
  * When detection coverage is found to be satisfying, follow the steps described in _**Mounting Method**_ section below to mount the PIR.

**IR-35-BUS Detection Range**

4

* _**Mounting Method**_
  * The PIR is designed to be mounted either on a flat surface or in a corner.
  * The base has two knockouts, where the plastic is thinner and can be broken for surface mounting.
  * A mounting bracket includes two central screw holes for fixing the PIR onto a surface and four side screw holes for fixing the PIR onto a corner.
  * For surface mounting, an optional rotating bracket is provided for users to adjust the range of detection. With the rotating bracket, the IR-35-BUS can be rotated 80 degrees horizontally and 70 degrees vertically to provide the optimal coverage.
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

5

* For surface mounting, an optional rotating bracket is provided for users to adjust the range of detection. With the rotating bracket, the IR-35-BUS can be rotated 80 degrees horizontally and 70 degrees vertically to provide the optimal coverage.
* The rotating bracket can be mounted on the wall with the provided screws.
  1. Screw the rotating bracket into the wall.
  2. Fit the 3 hooks of the rotating bracket into the 3 holes of the base accordingly.
  3. Rotate the bracket for the proper range of detection and tighten the fixing screw.

**Installation Recommendations**

* **It is recommended to install the PIR in the following locations:**
  * At a height of 2.3M-2.5M for best performance:
  * At locations where animals cannot come to the detection area by climbing on furniture or other objects.
  * Don’t aim the sensor at stairways where animals can climb on.
  * At a position such that an intruder would normally move across the PIR’s field of view from side to side.
  * In a corner to give the widest view.
  * At a position where its field of view will not be obstructed by e.g., curtains, ornaments etc.
* **Limitations**

|  | Do not install outdoors.                   |  | Avoid large obstacles in the detection area. |
| - | ------------------------------------------ | - | -------------------------------------------- |
|   |                                            |   |                                              |
|  | Do not expose the PIR completely to direct |  | Avoid vapor or high humidity that can cause  |
|   | sunlight.                                  |   | condensation.                                |
|   |                                            |   |                                              |
|   |                                            | 6 |                                              |

|  | Avoid moving objects, e.g., curtains, wall   |  | Avoid reflected light from bright surfaces, e.g., |
| - | -------------------------------------------- | - | ------------------------------------------------- |
|   | hangings, etc., in the detection area.       |   | mirrors, windows, etc.                            |
|   |                                              |   |                                                   |
|  | Avoid installing the PIR in areas where      |  | Avoid reflecting surface in the detection area.   |
|   | machines such as air conditioners or heaters |   | Reflected infrared signatures may lead to false   |
|   | may cause rapid change in temperature in the |   | alarm.                                            |
|   | detection area.                              |   |                                                   |
|   |                                              |   |                                                   |

7
