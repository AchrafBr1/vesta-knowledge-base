# VESTA 393

![](<.gitbook/assets/0 (63).png>)**Wired Tag Reader (TG-15N-BUS)**

* _**Introduction**_

TG-15N-BUS is a tag reader that is able to communicate with and powered by the Hybrid Panel through BUS connection.

The Wired Tag Reader is integrated with NFC labels for you to quickly arm or disarm your alarm system with just one simple swipe.

The device consists of a two-part design made up of a cover and a base. The cover contains all the electronics and the base provides a mean of fixing. The tamper switch protects the enclosure from being opened or being removed from the mounting surface.

![](<.gitbook/assets/1 (81).png>)

* _**Identifying the Parts**_

1. **Green LED Red LED Orange LED Arm Button**
2. **Sensor Zone (for tags)**
3. **BUS Terminal**
4. **Terminal Resistor Jumper Switch**

When the Wired Tag Reader is connected as the furthest BUS device on a BUS line, please set the Reader's terminal resistor jumper and the first BUS device’s (usually the Hybrid Panel’s) Jumper Switch to ON to serve as terminating resistors. The connected BUS line’s communication ability will be enhanced.

![](<.gitbook/assets/2 (77).jpeg>) ![](<.gitbook/assets/3 (86).png>)

**Jumper On**

![](<.gitbook/assets/4 (63).jpeg>)

The jumper link is inserted, connecting the two pins.

**Jumper Off**

The jumper link is removed or “**parked**” on one pin.

*
  * If the jumper is OFF, the communication ability is in normal level.
  * If the jumper is ON, the communication ability is enhanced.

1. **Learn Button**
2. **Tamper**
3. **Fixing Screw**
4. **Knockouts for Mounting Screws**
5. **BUS Wiring Hole**

![](<.gitbook/assets/5 (44).jpeg>)

1

* ![](<.gitbook/assets/6 (73).png>)_**LED Indicator:**_
  * **Green LED:**
    * Light on for 3 seconds: when Control Panel is under Disarm Mode
    * Flashes for 5 seconds: when the Arm Button is pressed (_Put the tag near the Sensor Zone to Arm the system during this 5 seconds_)
    * Flashes 10 times: when “identify” is clicked on the Panel’s webpage.
  * **Red LED:**
    * Light on for 3 seconds: when the Control Panel is under Arm Mode
    * Flashes for 3 seconds: when system is disarmed after alarming
  * **Orange LED:**
    * Light on for 3 seconds: when TG-15N-BUS senses a tag as it loses connection with the Control Panel
* _**Power:**_

![](<.gitbook/assets/7 (52).jpeg>) ![](<.gitbook/assets/8 (46).jpeg>) ![](<.gitbook/assets/9 (59).png>)

When TG-15N-BUS is hardwired to a Hybrid Panel, 13.5V power supply can be provided by the Hybrid Panel.

![](<.gitbook/assets/10 (60).png>)

* _**Tamper Protection:**_
  * The Wired Tag Reader is protected against any attempt to open the lid or to detach the Reader from its mounting surface (see **Mounting Tag Reader** for details).
  * When the Reader’s tamper is triggered, a tamper signal will be sent to the Control Panel for the Control Panel to display the status. Once the signal is sent, the Reader returns to idle mode.
* _**Supervision**_
  * After installation, the Wired Tag Reader will automatically transmit Supervisory signals periodically to the Control Panel at random intervals of 20-30 seconds.
* _**Caution**_
  * Wiring of the Wired Tag Reader should only be performed by certified technicians with proper knowledge and training in electric equipment.
  * Before installation or any maintenance work, make sure the power supply has been disconnected.
* _**Tag Reader Wiring:**_
  * Before connecting the Wired Tag Reader to the system bus, please switch the power off.
  * To assist cable connection, the terminal blocks on each BUS system module are color-coded.

![](<.gitbook/assets/11 (49).png>) ![](<.gitbook/assets/12 (50).png>) ![](<.gitbook/assets/13 (39).png>) ![](<.gitbook/assets/14 (27).jpeg>)

| **Red**    | VDD  |
| ---------- | ---- |
|            |      |
| **Black**  | GND  |
|            |      |
| **Yellow** | 485A |
|            |      |
| **Green**  | 485B |
|            |      |

* Multiple BUS devices can be connected in series to the Hybrid Panel. For optimal communication of the connected BUS line devices, ensure the terminal resistor jumper switches of the first (usually the Hybrid Panel) and the furthest BUS devices on a BUS line are set to ON to serve as terminating resistors. Be sure to only enable the aforementioned 2 jumper switches, and do not set the jumper switches to ON for any other BUS devices in between.

![](<.gitbook/assets/15 (39).png>)

_\<NOTE>_

* The pluggable design of BUS terminal blocks improves installation efficiency. Before wiring, you can remove the terminal blocks from the PCB board for ease of use, and plug in again after wiring.
* After unplugging the terminal, when re-installing the terminal back to the board, make sure to install the terminal in the same direction to avoid potential hazards.

2

* Incorrect connections will result in failure or malfunction. Inspect wiring and ensure proper connections before applying power.

![](<.gitbook/assets/16 (41).png>)

* _**Getting Started – Learning Wired Tag Reader into the Control Panel**_

Please follow the steps below to learn the device into the Hybrid Panel.

**Step 1.** Connect the device to the Panel. Then, power the Panel on.

**Step 2.** On the Panel’s webpage, click “**Learning**” to enter learn page.

**Step 3.** Click “**Start**” to enter learning mode; the Wired Tag Reader will be shown right after the Panel enters learning mode.

**Step 4.** Click “**Add**” to include the device into the Panel.

**Step 5.** If the device is successfully learnt into the Panel, it will be displayed in the “Learned Device” section.

![](<.gitbook/assets/17 (33).png>)

* _**Identification**_

The “Identify” function is used to localize a specific BUS device in the BUS wired system. This function is helpful in distinguishing which device is which especially in a large installation where numerous BUS devices are included.

To locate the Wired Tag Reader in the BUS system:

**Step 1.** On Hybrid Panel’s webpage, click “Identify” under the device list after the Tag Reader’s device column entry.

**Step 2.** If TG-15N-BUS receives the signal from the Hybrid Panel, the webpage will display a success message and TG-15N-BUS’s Green LED will flash 10 times to indicate where it is to the user.

![](<.gitbook/assets/18 (40).png>)

_\<NOTE>_

*
  * If a timeout message is displayed on the webpage, it means TG-15N-BUS did not receive the signal from the Panel.

Please check whether TG-15N-BUS is connected properly to the Panel within appropriate wiring distance.

* _**Walk Test**_

![](<.gitbook/assets/19 (40).png>)

* To make sure the Wired Tag Reader is able to communicate with the Panel after it is learned-in, place the Control Panel in Walk Test mode and press the learn button on TG-15N-BUS to transmit a test signal to the Control Panel.

3

* When the Panel receives the test signal, it will beep once and display the Reader’s information accordingly on the top of the device list.

![](<.gitbook/assets/20 (29).png>)

_\<NOTE>_

*
  * If there is no response from the Panel after the press of learn button, it means the Panel did not receive the test signal from the device.

Please check whether TG-15N-BUS is connected properly to the Panel within appropriate wiring distance.

* _**Mounting Wired Tag Reader:**_

The base has three knockouts for mounting purpose. To mount the Wired Tag Reader:

*
  *
    1. Unscrew the fixing screw.
    2. Remove the cover from the Reader.
    3. Fit the BUS Terminal onto the PCB; pass the wires through the BUS Wiring Hole as shown in the figure.
    4. Break through the knockouts on the base.
  * Use the knockouts as a template and drill holes into the surface to be mounted.
    1. Insert the wall plugs if the device is to be fixed onto plaster or bricks.
    2. Screw the base onto the wall plugs.
  * Fit the cover back to the base and screw the fixing screw.

_**\<NOTE>**_

*
  * If the mounted Reader is forcedly removed, the Breakaway Area will be left on the wall separated from the Reader, and the tamper will then be triggered.
* _**Tag Learning/Removing**_
  *
    * Before learning a tag into the Control Panel, make sure the Wired Tag Reader has been learned into the Control Panel.
    * After first power on the Wired Tag Reader, please wait for 10 seconds for the Reader to enable tag sensor function.
* To _**Learn**_ the tag into the Control Panel: **Step 1.** Disarm the system.

**Step 2.** Go to the Local webpage > **PIN Code**. Select **Area**. Place the tag near the Sensor Zone, and the Reader will send the tag’s ID number to the Control Panel. The Reader will sound 4 beeps. Click **Load** button on the webpage.

_**\<NOTE>**_

*
  * If the tag has been learned into the system, when you place the tag near the Sensor Zone, it will emit 2 beeps and green LED will turn on for 3 seconds to enter Disarm mode.

**Step 3.** When the tag’s ID number is shown on the webpage, enter a 4-digit User Code and assign a user name to the tag.

4

**Step 4.** Click **OK** button on the webpage to save the settings.

**Step 5.** Tag learning is complete.

* To _**Remove**_ the tag from the Control Panel: **Step 1.** Disarm the system.

**Step 2.** Go to the Local webpage > **PIN Code**. Select **Area**. Place the tag near the Sensor Zone and the Reader will send the tag’s ID number to the Control Panel. The Tag Reader will emit 2 beeps and green LED will turn on for 3 seconds. Find a blank tag number column and click **Load** to check the tag’s ID number to be deleted.

_**\<NOTE>**_

* If the tag has not been learned into the system, when you place the tag near the Wired Tag Reader, it will emit 4 beeps to notify the users of the fault.

**Step 3.** According to the tag’s ID number, find the same tag’s ID number on the list and tick **Delete**.

* **Example:** As shown in the pictures, No. 1 and No. 2 on the list are the existing learned tags. After you place the tag near the Reader and click **Load** in the blank No.3 column, the tag’s ID number shown in No. 3 is the same as that in No. 2, so No. 2 is the tag to be removed. Tick **Delete** in columns No. 2 and No. 3 to remove the tag.

**Step 4.** Click **OK** on the webpage to save the change.

**Step 5.** The removal of tag is complete.

* _**Operation:**_

After you complete learning the tag into the Wired Tag Reader, you can now switch the system to Arm or Disarm Mode:

1. **Disarm Mode Control:** Apply the tag near the Sensor Zone in armed mode; the Reader will emit 2 beeps when the Panel receives the disarm signal and successfully switches to Disarm Mode.
2. **Arm Mode Control:** Press the Arm Button once, and the Green LED will quickly flash for 5 seconds; then apply the tag near the Sensor Zone during this 5 seconds, the Tag Reader will emit 1 long beep to indicate the Panel has received arming request successfully.
3. **LED flash:** If the system is armed, the Red LED will light on for 3 seconds. When disarmed, the Green LED will light on for 3 seconds.
4. **Tamper:** When Tamper is triggered, the Wired Tag Reader will transmit a tamper alarm signal to the Control Panel immediately and return to idle mode.

5
