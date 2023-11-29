# VESTA 114

* REMOTE KEYPAD (KP-35-COMBO)

KP-35-COMBO is a hardwired Remote Keypad designed to have quick access control of the system control panel. The keypad can send wired and wireless signals to and receive signals from the Control Panel within 500ft (152m) in wire distance. The LCD screen will display any information the system control panel sends back.

The Remote Keypad can either be mounted on a flat surface or wall with screws. It also has a tamper protection switch which will be activated upon any unauthorized attempt to open the back cover.

* Parts Identification

![](<.gitbook/assets/0 (18).png>)

1. **Backlit LCD Display**
2. **Green LED**

* The Green LED is off in stand-by mode.
* The Green LED will light up when any key is pressed.

1. **Yellow LED**

* The Yellow LED will flash once every 3 seconds when any fault situation is detected, and turn to OFF when all fault conditions are restored.

1. **Backlit Numeric Keys**
2. **Backlit Star (＊) Key**
3. **Backlit Pound (＃) Key**
4. **Backlit OK Key**

* For confirming the keyed-in data or confirming the selection.

1. **Backlit Restore (**![](<.gitbook/assets/1 (24).png>)) **Key**

* This key is is used for deleting a digit, canceling the selection, aborting the current screen, and returning to the previous screen etc.

1. **Backlit Arm/▲ Key**

* Use this key to move the cursor and scroll the display upwards
* The key is also used for entering “Away Armed” mode.

1. **Backlit Arm/▼ Key**

* Use this key to move the cursor and scroll the display downwards.
* The key is also used for entering “Home Armed” mode.

1. **Buzzer**
2. **Battery Compartment**
3. **Keypad Terminal**

* Hardwiring the four terminals (V, G, A, B) to the Keypad Terminal on the Control Panel. Up to four KP-35-COMBOs can be connected in series. For keypad wiring, refer to _**Keypad Wiring**_ section on the next page for detail.

1. **Wire Management Hole**

* Prepunched hole used to enhance wiring management flexibility.

1. **Jumper Switch**

![jumper open](<.gitbook/assets/2 (29).png>) ![jumper close](<.gitbook/assets/3 (25).png>)

**Jumper Off**

if the jumper link is removed or “**parked**” on one pin.

**Jumper On**

The jumper link is inserted connecting the two pins.

* Ensure the furthest keypad’s Jumper Switch is set to ON to serve as a terminating resistor.

1. **Tamper Switch**
2. **Mounting Holes x 4**
3. **Cover Fixing Screw x 1**

* Caution
* Wiring of the Remote Keypad should only be performed by certified technician with proper knowledge and

training in electric equipment.

* Before installation or any maintenance work, make sure the power supply of the Control Panel has been disconnected.
* Features
* _**Battery and Low Battery Detection**_
* Two L91 1.5V AA lithium batteries can be installed inside the battery compartment to serve as a backup power source in case of power failure. Prior to inserting batteries, ensure battery polarity is correct to protect your device.
* The Remote Keypad can also monitor battery life. When batteries are low on power, a low battery signal will be sent along with regular signal transmission to the Control Panel to alert users for battery replacement.

\<NOTE>

* Only use specified batteries with the device. When replacing batteries, always replace the whole set, do not mix

.different types of batteries or new and used ones to avoid damaging the device.

* _**Power Saving Feature**_
* When idle, the Remote Keypad is in **stand-by** mode and consumes no power. It will wake up when any key is pressed.
* After entering User Menu, if neither of the **Arm** key/**Home Arm** key is pressed, the Remote Keypad will return to **stand-by** mode within 5 seconds. If either or both of the **Arm** key/**Home Arm** key is/are pressed, the Remote Keypad will return to stand-by mode within **20** seconds.
* After “Enter PIN Code” is displayed on the LCD screen, if no key is pressed, the Remote Keypad will return to **stand-by** mode within 5 seconds.
* After the Mode Change request is submitted, if no signal is received from the Control Panel, the Keypad will return to **stand-by** mode within 15 seconds.
* Upon completion of a command input, the Remote keypad will return to **stand-by** mode.
* _**Keypad Wiring**_
* The keypad terminal can be hardwired to the Control Panel. Up to four KP-35-COMBOs can be connected in series within 500ft (152m) in wire distance. Wire gauge: UTP, minimum 20 AWG, maximum 18 AWG.
* To connect KP-35-COMBO to the Control Panel, open the front cover by using a Phillips screwdriver to loosen the cover fixing screw.
* Loosen KP-35-COMBO’s “V” terminal and the Control Panel’s “VDD” terminal. Connect the “V” terminal to the “VDD” terminal and tighten both terminal screws.
* Loosen KP-35-COMBO’s “G” terminal and the Control Panel’s “GND” terminal. Connect the “G” terminal to the “GND” terminal and tighten both terminal screws.
* Loosen KP-35-COMBO’s “A” terminal and the Control Panel’s “458A” terminal. Connect the “A” terminal to the “458A” terminal and tighten both terminal screws.
* Loosen KP-35-COMBO’s “B” terminal and the Control Panel’s “458B” terminal. Connect the “B” terminal to the “458B” terminal and tighten both terminal screws.
* Ensure the furthest keypad’s Jumper Switch and Control Panel’s J53 Jumper Switch are set to ON to serve as a terminating resistor.

![kp wiring](<.gitbook/assets/4 (24).png>)

The Keypad Terminal can be hardwired to the Control Panel in series within 500ft (152m) in wire distance.

* KP-35-COMBO-A is wired correctly as it is within 500ft (152m) of the Control Panel, in wire distance.
* KP-35-COMBO-B is wired correctly as it is within 500ft (152m) of the Control Panel, in wire distance. Before tightening the cover fixing screw of the keypad, ensure its jumper switch is set to ON to serve as a terminating resistor since it has the furthest distance from the Control Panel.
* KP-35-COMBO-C is NOT wired correctly as it is farther than 500ft (152m) from the Control Panel.

![](<.gitbook/assets/5 (16).png>)

* _**Tamper Protection**_
* The Remote Keypad is protected against any unauthorized attempt to open the back cover with a tamper switch. When the back cover is opened, the tamper switch will be triggered and the Remote Keypad will transmit a tamper open signal to the system control panel.
* After replacing the back cover, the Remote Keypad will transmit a tamper restore signal to the system control panel.
* When the Remote Keypad is properly mounted with back cover screwed onto the wall, removing the Keypad forcefully will break off the back cover from the hollowed section around the screw location and activate tamper switch.
* _**Supervision Signal**_
* After installation, the Remote Keypad will automatically transmit Supervision Signals to the Control Panel at an interval of 30-50 minutes.
* If the Control Panel has not received the signal from the Remote Keypad for a preset period of time, the Control Panel will consider the Remote Keypad out of order and react according to panel setting.
* _**System Status Check**_

The Remote Keypad allows the user to check the status of the system. When the Control Panel is not under alarm

activation or exit delay status, press the OK key and the current status will be displayed on the LCD screen for 3 seconds.

There are three different statuses: Away Armed, Home Armed, and System Disarmed.

* _**System Mode Change**_

Users can use Keypad to change system mode via PIN code.

* After entering the PIN code, press the **Arm/Home Arm/OK** key to enter **Away Armed/Home Armed/System Disarmed** mode.
* After entering user menu with the system disarmed, users can also select **Away Arm** or **Home Arm**, and press OK to change system mode.
* **Quick Arm Function:** Users can enter Setting Menu to activate the Quick Arm Function (Choose **Setting > Quick Arm > Enable**, and then press OK), which will allow users to change mode by pressing the Arm key or the Home Arm key without entering the PIN code. To disarm the system, users still need to enter PIN code.
* _**User Menu**_
* The Keypad will communicate with the system to retrieve information before entering User Menu. The following options will be displayed on LCD screen for selection. Use **▲** and **▼** key to select your option, and then press the **OK** key to confirm.
* The system is always automatically disarmed upon entering Keypad User Menu.
* The Keypad will exit User Menu automatically after 20 seconds of inactivity.

|   | **A** | **w** | **a** | **y** |       | **A** | **r** | **m** |       |       |       |       |       |   |   |
| - | ----- | ----- | ----- | ----- | ----- | ----- | ----- | ----- | ----- | ----- | ----- | ----- | ----- | - | - |
|   | **H** | **o** | **m** | **e** |       | **A** | **r** | **m** |       |       |       |       |       |   |   |
|   | **A** | **l** | **a** | **r** | **m** |       | **M** | **e** | **m** | **o** | **r** | **y** |       |   |   |
|   | **F** | **a** | **u** | **l** | **t** |       | **D** | **i** | **s** | **p** | **l** | **a** | **y** |   |   |
|   | **L** | **o** | **g** |       |       |       |       |       |       |       |       |       |       |   |   |
|   | **S** | **e** | **t** | **t** | **i** | **n** | **g** |       |       |       |       |       |       |   |   |

* **Away Arm:** Select “Away Arm” and press the OK key to change system mode to “Away Armed”.
* **Home Arm:** Select “Home Arm” and press the OK key to change system mode to “Home Armed”
* **Alarm Memory:** This option will become available after an alarm is triggered. Entering the Keypad’s User Menu will be directed to the Alarm Memory option automatically. Press **OK** to confirm selection, and then use **▲** and **▼** key to view the alarm memory.
* **Fault Display:** This option will become available when fault event exists in system. To view fault events, select “Fault Display” and press OK key to confirm selection. Use the ▲ and ▼ keys to view the fault events and press key to return to menu.

\<NOTE>

* If you try to arm the system when fault event exists, the arming will be prohibited and the LCD screen will jump to

.Fault Display. If you want to force arm the system, please go to your Control Panel to check and remove the fault

.condition(s), and then select Away Arm or Home Arm and press OK again. The system will ignore the fault event

.and enter your selected arm mode.

* **Log**: Select “Log” and press OK key to view system log. Use the ▲ and ▼ keys to view the events and press key to return to User Menu.
* **Setting:** Select “Setting” and press OK key enter setting menu. Use the ▲ and ▼ keys to select setting options and press key to return to User Menu.

|   | **B** | **e** | **e** | **p** |       | **C** | **o** | **n** | **t** | **r** | **o** | **l** |       |   |   |
| - | ----- | ----- | ----- | ----- | ----- | ----- | ----- | ----- | ----- | ----- | ----- | ----- | ----- | - | - |
|   | **P** | **a** | **n** | **i** | **c** |       | **A** | **l** | **a** | **r** | **m** |       |       |   |   |
|   | **F** | **i** | **r** | **e** |       | **A** | **l** | **a** | **r** | **m** |       |       |       |   |   |
|   | **M** | **e** | **d** | **i** | **c** | **a** | **l** |       | **A** | **l** | **a** | **r** | **m** |   |   |
|   | **Q** | **u** | **i** | **c** | **k** |       | **A** | **r** | **m** |       |       |       |       |   |   |

* _**Mode Change Result**_
* **Away Armed:** When system changes to “Away Armed” mode, “Away Armed” will be displayed on the LCD screen along with a long beep indicating successful operation.
* **Home Armed:** When system changes to “Home Armed” mode, “Home Armed” will be displayed on the LCD screen along with 3 beeps indicating successful operation.
* **System Disarmed:** When system changes to “System Disarmed” mode, “System Disarmed” will be displayed on the LCD screen along with 2 beeps indicating successful operation.
* **Exit/Entry Delay:** When the Entry/Exit delay timer is enabled in the Control Panel, and the Entry/Exit Beep function is enabled on the Remote Keypad, Remote Keypad will count down with the system when Entry/Exit delay timer begins. "Counting Down” will be displayed on the LCD for 10 seconds. The green LED will also light up for 10 seconds along with 1 beep every second. After 10 seconds, the LCD and the green LED will turn off, but the warnings beeps will continue with the system count down.
* **Operation Error:** “Operation Error” will be displayed on the LCD screen along with 2 beeps indicating unsuccessful operation; for instance, when you submit the mode change request from **Arm** to **Home Arm**.
* **Fault Display**: When the system arms with fault, “Fault Display” will be displayed on the LCD screen along with 3 beeps indicating arming fault.
* **Incorrect PIN Code:** When incorrect password is submitted, “Incorrect PIN Code” will be displayed on the LCD screen along with 4 beeps indicating wrong password.

\<NOTE>

* After the mode change request is submitted, if no signal is received from the Control Panel, the Keypad will return

.to stand-by mode within 15 seconds.

* If there are 5 incorrect PIN Code attempts within 10 minutes, the Remote Keypad will be automatically locked up

.for 5 minutes. During this period, any operation will be invalid. When the lockup time expires, the Remote Keypad

.will emit 1 long beep.

* _**Dual Key Alarm Functions**_
* The dual-key function is disabled by default. To enable it, enter the setting menu of the Remote Keypad to set alarm triggers (Choose **Setting > Panic Alarm/Fire Alarm/Medical Alarm > Enable**, and then press OK).
* Panic Alarm: Press “1 + 3” to trigger a Panic Alarm.
* Fire Alarm: Press “4 + 6” to trigger a Fire Alarm.
* Medical Alarm: Press “7 + 9” to trigger a Medical Alarm.
* When an alarm is triggered, “Alarm! Alarm!” will be displayed on the LCD screen, and the green LED will light up for 10 seconds.
* _**Beep Control:**_

This function is for you to set the Keypad warning beep functions.

* **Entry/Exit Beep:** The function is disabled by default. To enable it, please choose **Setting > Beep Control > Entry/Exit Beep > Enable** in the user menu, and press OK to confirm setting.
* **Alarm Beep:** The function is disabled by default. To enable it, please choose **Setting > Beep Control > Alarm Beep > Enable** in the user menu, and press OK to confirm setting.
* _**Joining in the System Network**_

**Wireless Operation:**

* To add the Remote Keypad into the system network, first put the Control Panel in learning mode.
* Press the OK key once. When “Enter PIN Code” is displayed on the LCD screen, press and hold the **OK** key for 10 seconds.
* “KP will reset in 2 seconds” will be displayed on the LCD screen along with a long beep.
* “Scanning Network” will be displayed on the LCD screen while the Remote Keypad is sending learning code to the Control Panel.
* When the Keypad is added into the Control Panel, “Learning Success” will be displayed on the LCD screen along with 2 beeps.

\<NOTE>

* If the Control Panel promptly responds to the Remote Keypad, the “Scanning Network” process will be skipped,

.and “Learning Success” will be directly displayed on the LCD screen.

* If the Remote Keypad does not receive any signal from the Control Panel within 30 seconds, the LCD screen will

.be turned off, and the Remote Keypad will return to stand-by mode.

**Hardwiring Operation:**

In addition to the wireless operation to join in the system network as stated above, the user can do it through hardwiring.

**Step 1.** Connect the Keypad to the Panel through wiring.

**Step 2.** Choose a located area and a free zone to join in the system network.

|   | **C** | **h** | **o** | **o** | **s** | **e** |       | **A** | **r** | **e** | **a** | **&** | **Z** | **o** | **n** | **e** |   |
| - | ----- | ----- | ----- | ----- | ----- | ----- | ----- | ----- | ----- | ----- | ----- | ----- | ----- | ----- | ----- | ----- | - |
|   | **A** | **n** | **d** |       | **E** | **n** | **t** | **e** | **r** |       | **C** | **o** | **d** | **e** | **s** |       |   |

| **。** | **A** | **r** | **e** | **a** | **1** |   |   |   |   |   |   |   |   |   |   |   |   |
| ----- | ----- | ----- | ----- | ----- | ----- | - | - | - | - | - | - | - | - | - | - | - | - |
|       | **A** | **r** | **e** | **a** | **2** |   |   |   |   |   |   |   |   |   |   |   |   |

| **。** | **Z** | **o** | **n** | **e** | **1** |   |   |   |   |   |   |   |   |   |   |   |   |
| ----- | ----- | ----- | ----- | ----- | ----- | - | - | - | - | - | - | - | - | - | - | - | - |
|       | **Z** | **o** | **n** | **e** | **3** |   |   |   |   |   |   |   |   |   |   |   |   |

**Step 3.** Enter the PIN Code of the located area.

|   | **E** | **n** | **t** | **e** | **r** |   | **P** | **I** | **N** |   | **C** | **o** | **d** | **e** |   |   |   |
| - | ----- | ----- | ----- | ----- | ----- | - | ----- | ----- | ----- | - | ----- | ----- | ----- | ----- | - | - | - |
|   |       |       |       |       |       |   |       |       |       |   |       |       |       |       |   |   |   |

**Step 4.** Enter Installer Code. (Factory Default: 7982)

|   | **E** | **n** | **t** | **e** | **r** |   | **I** | **-** | **C** | **o** | **d** | **e** |   |   |   |   |   |
| - | ----- | ----- | ----- | ----- | ----- | - | ----- | ----- | ----- | ----- | ----- | ----- | - | - | - | - | - |
|   |       |       |       |       |       |   |       |       |       |       |       |       |   |   |   |   |   |

**Step 5.** The Keypad is added to the located area and the zone you chose.

|   | **A** | **d** | **d** | **e** | **d** |   | **K** | **e** | **y** | **p** | **a** | **d** |   | **T** | **o** |   |   |
| - | ----- | ----- | ----- | ----- | ----- | - | ----- | ----- | ----- | ----- | ----- | ----- | - | ----- | ----- | - | - |
|   | **A** | **r** | **e** | **a** | **1** |   | **Z** | **o** | **n** | **e** | **1** |       |   |       |       |   |   |

* _**Fault Conditions**_

_When Remote Keypad is under **NORMAL OPERATION MODE,**_

* If the Control Panel is in Away Armed mode, you CANNOT activate Home Armed Mode by using Remote Keypad. If you do so, the Remote Keypad will emit 2 beeps indicating the Control Panel is in Away Armed mode.
* When any fault situation is detected, the Yellow LED will flash once every 3 seconds. The Yellow LED behavior is decide by the Control Panel.
* If there are 5 incorrect PIN Code attempts within 10 minutes, the Remote Keypad will be automatically locked up for 5 minutes. During this period, any operation will be invalid. When the lockup time expires, the Remote Keypad will emit 1 long beep.
* _**Change of Battery**_

1. Go to the Control Panel programming menu to bypass the KP tamper alarm.
2. Dismount the Remote Keypad.
3. Take out all three old batteries and press the tamper switch for more than 3 seconds to fully discharge before replacing

new batteries. Do not mix new and old batteries.

1. Take out the old battery and press the tamper switch to discharge before replacing the new battery.
2. Screw back the Remote Keypad to the surface with mounting screws.
3. Put the Control Panel back to normal operation mode.

* _**Reset Remote Keypad to Factory Default**_

The Remote Keypad can be reset to clear all learnt-in data and return all settings to default value by following the steps

below:

1. Please follow _**Change of Battery**_ steps for factory default.
2. Within 10 seconds after inserting batteries, enter “0000”. When the last digit of “0000” turns into “🞸” on the LCD screen,

press “#” to reset the Remote Keypad to default value.

1. “Reset Default” will be displayed on the LCD screen along with 3 beeps indicating successful operation.
2. All learnt-in data will be cleared.
3. Entry/ Exit Beeps will be disabled.
4. Alarm Beep will be disabled.
5. Dual Key alarm function will be disabled.

\<NOTE>

* Factory default setting can only be performed within 10 seconds after inserting batteries. If the keypad is not wake

.up within 10 seconds after inserting batteries, remove batteries and try again.

* Whenever the Keypad is removed from the Control Panel, it should be put to factory reset as well to clear its

.Control Panel memory.

* Mounting Remote Keypad

To mount the Remote Keypad:

1. Remove the front cover by loosening the cover fixing screw using a screwdriver.
2. Use the 4 mounting holes on the back cover as a template to mark and drill mounting holes.
3. Drill 4 holes and insert the wall plugs. Ensure the wall plugs are flush with the mounting surface.
4. Screw the back cover onto the wall plugs.
5. Replace the front cover onto the back cover. Screw the cover fixing screw.
6. The installation is now complete.
