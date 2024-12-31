# VESTA-114

**WIRED/WIRELESS COMBO KEYPAD (KP-35-COMBO)**

KP-35-COMBO is a hardwired and wireless keypad designed to have quick access control of the system control panel. The keypad can send wired and wireless signals to and receive signals from the Control Panel within wire distance, depending on the wire gauge and the total power consumption of all wired devices. The LCD screen will display information the system control panel sends back.

The wired/wireless keypad can either be mounted on a flat surface or a wall with screws. It also has a tamper protection switch which will be activated upon any unauthorized attempt to open the back cover.

## **Parts Identification**

<figure><img src=".gitbook/assets/image (110).png" alt=""><figcaption></figcaption></figure>

1. **Backlit LCD Display**
2. **Green LED**
   * The Green LED is off in stand-by mode.
   * The Green LED will light up when any key is pressed.
3. **Yellow LED**
   * The Yellow LED will flash once every 3 seconds when any fault situation is detected, and turn to OFF when all fault conditions are restored. The LED’s behavior is controlled by the Control Panel.
4. **Backlit Numeric Keys**
5. **Backlit Star (＊) Key**
6. **Backlit Pound (＃) Key**
7. **Backlit OK Key**
   * For confirming the keyed-in data or confirming the selection.
8. **Backlit Restore (**![](<.gitbook/assets/3 (7).jpeg>)) **Key**
   * This key is is used for deleting a digit, canceling the selection, aborting the current screen, and returning to the previous screen etc.
9. **Backlit Arm/** ![](<.gitbook/assets/image (108).png>) **Key**
   * Use this key to move the cursor and scroll the display upwards
   * The key is also used for entering “Away Armed” mode.
10. **Backlit Home Arm/** ![](<.gitbook/assets/image (109).png>) **Key**
    * Use this key to move the cursor and scroll the display downwards.
    * The key is also used for entering “Home Armed” mode.
11. **Buzzer**
12. **Battery Compartment**
13. **BUS Terminal**

* Hardwiring the four terminals (V, G, A, B) to the connected in series. For keypad wiring, refer to

BUS Terminal on the Control Panel. Up to four KP-35-Combos can be _**Keypad Wiring**_ section on the next page for detail.

14. **Wire Management Hole**
    * Prepunched hole used to enhance wiring management flexibility.
15. **Terminal Resistor Jumper Switch**
    * When the keypad is connected as the furthest BUS device on a BUS line, please set the keypad's terminal resistor jumper and the first BUS device’s Jumper Switch to ON to serve as terminating resistors. The connected BUS line’s communication ability will be enhanced.

<div align="left"><img src=".gitbook/assets/4 (7).jpeg" alt=""> <img src=".gitbook/assets/5 (5).jpeg" alt=""></div>

**Jumper On**

If the jumper is ON, the communication ability will be enhanced.

**Jumper Off**

<div align="left"><img src=".gitbook/assets/7 (5).jpeg" alt=""></div>

If the jumper is OFF (the jumper link is removed or “parked” on one pin), the communication ability is in normal level.

16. **Tamper Switch**
17. **Mounting Holes x 4**
18. **Bottom Fixing Screw x 1**&#x20;

## **Caution**

* Wiring of the wired/wireless keypad should only be performed by certified technicians with proper knowledge and training in electric equipment.
* Before installation or any maintenance work, make sure the power supply of the Control Panel has been disconnected.

## **Features**

### _**Power Supply**_

When KP-35-Combo is hardwired to Control Panel, 13.5V (typical) power supply can be provided by the Control Panel to KP-35-Combo.

### _**Battery and Low Battery Detection**_

* Two L91 1.5V AA lithium batteries can be installed inside the battery compartment to serve as a backup power source in case of power failure. Prior to inserting batteries, ensure correct battery placement to protect your device.
* The wired/wireless keypad can also monitor the battery life. When batteries are low in power, a low battery signal will be sent along with regular signal transmission to the Control Panel to alert users to battery replacement.

_\<NOTE>_

* Use only the specified batteries with the device. When replacing batteries, always replace the whole set and do not mix different types of batteries or new and used ones to avoid damaging the device.

### _**Power Saving Feature**_

* When idle, the wired/wireless keypad is in **stand-by** mode and consumes no power. It will wake up when any key is pressed.
* After entering User Menu, if neither of the **Arm** key/**Home Arm** key is pressed, the wired/wireless keypad will return to **stand-by** mode within 5 seconds. If either or both of the **Arm** key/**Home Arm** key is/are pressed, the wired/wireless keypad will return to stand-by mode within **20** seconds.
* After “Enter PIN Code” is displayed on the LCD screen, if no key is pressed, the wired/wireless keypad will return to **stand-by** mode within 5 seconds.
* After the mode change request is submitted, if no signal is received from the Control Panel, the keypad will return to **stand-by** mode within 15 seconds.
* Upon completion of a command input, the wired/wireless keypad will return to **stand-by** mode.

### _**Keypad Wiring**_

* To connect KP-35-COMBO to the Control Panel, open the front cover by using a Phillips screwdriver to loosen the cover fixing screw.
* Before connecting the “V”, “G”, “A”, “B” terminals, remove the batteries from KP-35-COMBO and make sure the power supply of the Control Panel has been disconnected.
* Loosen KP-35-COMBO’s “V” terminal and the Control Panel’s “VDD” terminal. Connect the “V” terminal to the “VDD” terminal and tighten both terminal screws.
* Loosen KP-35-COMBO’s “G” terminal and the Control Panel’s “GND” terminal. Connect the “G” terminal to the “GND” terminal and tighten both terminal screws.
* Loosen KP-35-COMBO’s “A” terminal and the Control Panel’s “485A” terminal. Connect the “A” terminal to the “485A” terminal and tighten both terminal screws.
* Loosen KP-35-COMBO’s “B” terminal and the Control Panel’s “485B” terminal. Connect the “B” terminal to the “485B” terminal and tighten both terminal screws.
* Power on the Control Panel and wait for the “KP-35 COMBO” to be shown on the wired/wireless keypad’s LCD screen.

![](<.gitbook/assets/11 (5).jpeg>)

* The keypad terminal can be hardwired to the Control Panel. Up to four KP-35-Combos can be connected in series. The maximum wire cable length depends on the wire gauge and the total power consumption of all wired devices, for example: maximum 3000ft @ 22-AWG cable for one KP-35-COMBO; maximum 1500ft @ 22-AWG cable for 2 KP-35-COMBOs; or maximum 1000ft @ 22-AWG cable for 3 KP-35-COMBOs.
* In the picture below, KP-35-COMBO-**A** and KP-35-COMBO-**B** are wired correctly in series as the total wire distance of two keypads from the Control Panel is within 1500ft. For the KP-35-COMBO-**C** in the picture below, it is **NOT** wired correctly as it is farther than 1000ft from the Control Panel.
* For optimal communication of the connected BUS line devices, ensure the terminal resistor jumper switches of the first and the furthest BUS devices on a BUS line are set to ON to serve as terminating resistors. Be sure to only enable the aforementioned 2 jumper switches, and do not set the jumper switches to ON for any other BUS devices in between.

For example, for KP-35-COMBO-**B** in the picture below, it is the farthest device on the BUS line, and Hybrid Panel is the first device on the BUS line. Ensure to set the KP-35-COMBO-**B**'s terminal resistor jumper switch and Hybrid Panel's J53 Jumper Switch to ON to serve as terminating resistors.

<div align="left"><figure><img src=".gitbook/assets/image (1) (1) (1) (1) (1) (1) (1) (1) (1).png" alt=""><figcaption></figcaption></figure></div>

### _**Tamper Protection**_

* The wired/wireless keypad is protected against any unauthorized attempts to open the back cover with a tamper switch. When the back cover is opened, the tamper switch will be triggered and the wired/wireless keypad will transmit a tamper open signal to the system control panel.
* After re-placing the back cover, the wired/wireless keypad will transmit a tamper restore signal to the Control Panel.
* When the wired/wireless keypad is properly mounted with back cover screwed onto the wall, removing the keypad forcefully will break off the back cover from the hollowed section around the screw location and activate tamper switch.

### _**Supervision Signal**_

* When in wired mode, the wired/wireless keypad will automatically transmit Supervision Signals to the Control Panel at an interval of 20-30 seconds.
* When in wireless mode, the wired/wireless keypad will automatically transmit Supervision Signals to the Control Panel at an interval of 30-50 minutes.
* If the Control Panel has not received the signal from the wired/wireless keypad for a preset period of time, the Control Panel will consider the wired/wireless keypad out of order and react according to panel setting.

## _**Joining the System Network**_

### **Wireless Operation:**

* To add the wired/wireless keypad to the system network, first put the Control Panel in learning mode.
* Press the OK key once. When “Enter PIN Code” is displayed on the LCD screen, press and hold the **OK** key for 10 seconds.
* “KP will reset in 2 seconds” will be displayed on the LCD screen along with a long beep.
* “Scanning Network” will be displayed on the LCD screen while the wired/wireless keypad is sending learning code to the Control Panel.
* When the keypad is added to the Control Panel, “Learning Success” will be displayed on the LCD screen along with 2 beeps.

_\<NOTE>_

* If the Control Panel promptly responds to the wired/wireless keypad, the “Scanning Network” process will be skipped, and “Learning Success” will be directly displayed on the LCD screen.
* If the wired/wireless keypad does not receive any signal from the Control Panel within 20 seconds, the LCD screen will be turned off, and the wired/wireless keypad will return to stand-by mode.

## **Hardwiring Operation:**

In addition to the wireless operation to join the system network as stated above, the user can do it through hardwiring.

**Step 1.** Connect the Keypad to the Panel through wiring.

**Step 2.** Choose a located area and a free zone to join the system network.

**Choose** **Area & Zone**

**And**  **Enter Codes**

* **Area 1**&#x20;

&#x20;      **Area 2**

* **Zone 1**&#x20;

&#x20;      **Zone 3**

**Step 3.** Enter the PIN Code of the located area.

**Enter PIN Code**

**Step 4.** Enter Installer Code. (Factory Default: 7982)

**Enter -I Code**

**Step 5.** The keypad is added to the located area and the zone you chose.

**Added** **Keypad** **To**

**Area 1** **Zone 1**

## _**Identification**_

The “**Identify**” function is used to localize a specific wired device in the whole wired system. This function is helpful in distinguishing which device is which especially in a large installation where numerous wired devices are included.

To locate KP-35-Combo in the wired system:

**Step 1.** On the Panel’s webpage, click “Identify” under the device list after the Keypad’s device column entry.

**Step 2.** If KP-35- Combo receives the signal from the Panel, the webpage will display a success message and the white backlight of the wired/wireless keypad will flash 10 times to indicate where it is to the user.

_\<NOTE>_

* If a timeout message is displayed on the webpage, it means the wired/wireless keypad did not receive the signal from the Panel.

Please check whether KP-35-Combo is connected properly to the Panel within appropriate wiring distance.

### _**Area Status Check**_

* The wired/wireless keypad allows the user to check the status mode of each area. When the Control Panel is under stand-by mode, press the OK key and the current status of each area will be displayed on the LCD screen for 3 seconds.
* There are three different statuses: A = Away Armed / H = Home Armed / D = System Disarmed.
* A question mark “?” will be displayed if the area status cannot be identified.
* Example:

<table><thead><tr><th width="26"></th><th width="26">1</th><th width="44">2</th><th width="44">3</th><th width="45">4</th><th width="43">5</th><th width="43">6</th><th width="43">7</th><th width="44">8</th><th width="26"></th></tr></thead><tbody><tr><td></td><td>A</td><td>H</td><td>D</td><td>?</td><td>D</td><td>H</td><td>?</td><td>?</td><td></td></tr></tbody></table>



### _**System Mode Change**_

Users can use the keypad to change the system mode via a PIN code.

* **To change the system mode with a PIN Code:**

After entering the PIN code, press the **Arm/Home Arm/OK** key to enter **Away Armed/Home Armed/System Disarmed** mode.

* When the system mode is changed to disarmed mode, the LCD will show “Area No. Alarm Memory” and Yellow LED will flash once every 3 seconds with 5 beeps if there is/are alarm(s) triggered before. Users can manually enter User Menu to view the alarm memory (please refer to User Menu section below for details).
* **Quick Arm Function:** Users can enter Setting Menu to activate the Quick Arm Function (Choose **Setting > Quick Arm > Enable**, and then press OK), which will allow users to change the mode by pressing the Arm key or the Home Arm key without entering the PIN code. To disarm the system, users still need to enter the PIN code.
* After entering User Menu with the system disarmed, users can also select **Away Arm** or **Home Arm**, and press OK to change the system mode.

## _**User Menu**_

* The keypad will communicate with the system to retrieve information before entering User Menu. The following options will be displayed on LCD screen for selection. Use ![](<.gitbook/assets/image (125).png>) and ![](<.gitbook/assets/image (126).png>) keys to select and press the **OK** key to confirm your selection.
* To enter User Menu, press and hold “![](<.gitbook/assets/image (124).png>)” for 2 seconds in idle mode of the keypad when the system of the area where KP-35-Combo is located is already in **Disarmed mode**.
* The keypad will exit User Menu automatically after 20 seconds of inactivity.

**Away Arm**

**Home Arm**

**Alarm Memory**

**Fault Memory**

**Log**

**Bypass**

**Setting**

* **Away Arm:** Select “Away Arm” and press the OK key to change the system mode to “Away Armed”.
* **Home Arm:** Select “Home Arm” and press the OK key to change the system mode to “Home Armed”.
* **Alarm Memory:** This option will become available after an alarm is triggered. Entering User Menu will be directed to the Alarm Memory option automatically. Press **OK** to confirm the selection, and then use ![](<.gitbook/assets/image (119).png>) and ![](<.gitbook/assets/image (120).png>) keys to view the alarm memory.
* **Fault Display:** This option will become available when fault event exists in the system. To view fault events, select “Fault Display” and press OK to confirm the selection. Use ![](<.gitbook/assets/image (121).png>) and ![](<.gitbook/assets/image (122).png>) keys to view the fault events and press ![](<.gitbook/assets/image (123).png>) key to return to User Menu.

_\<NOTE>_

* The Yellow LED will flash once every 3 seconds when any fault situation is detected, and turn to OFF when all fault situations are cleared.
* If you try to arm the system when fault event exists, the arming will be prohibited and the LCD screen will jump to Fault Display. If you want to forcibly arm the system, perform the arm action again within 30 seconds. The system will ignore the fault event and enter your selected arm mode.
* **Log**: Select “Log” and press OK to view the system log. Use ![](<.gitbook/assets/image (116).png>) and ![](<.gitbook/assets/image (117).png>) keys to view the events and press ![](<.gitbook/assets/image (118).png>) key to return to User Menu.
* **Bypass:** This function is only available under wired connection. “Enter M. Code” will be shown on the LCD screen (default M. Code is **1111**). The Panel will ignore all signals received from the device being bypassed and not respond at all when such device is triggered.
* **Setting:** For wireless connection, after entering Unser Menu, input the default M. code “**1111**” to enter the setting menu. For wired connection, input the default I. code “**7982**” to enter the setting menu. Use ![](<.gitbook/assets/image (114).png>) and ![](<.gitbook/assets/image (115).png>) keys to select setting options and press key to return to User Menu.

**Beep Control**

**Panic Alarm**

**Fire Alarm**

**Medical Alarm**

**Quick Arm**

**Language**

**Change M. Code**

* **Language:** Select “Language” and press OK to enter language menu. Use ![](<.gitbook/assets/image (112).png>) and ![](<.gitbook/assets/image (113).png>) keys to select the language for display, and press key to return to User Menu.

**English**

**Español**

**Portugues**

**Français**

**Deutsche**

**Italiano**

**Nerderlands**

### **Change M. Code:**&#x20;

This function is only available under wireless connection. The default M. code is 1111. Users can change it manually, and only when the correct M. Code is entered can the user enter the setting menu.

### _**Mode Change Result**_

* **Away Armed:** When the system changes to “Away Armed” mode, “Area No. Away Armed” will be displayed on the LCD screen along with a long beep indicating successful operation.
* **Home Armed:** When the system changes to “Home Armed” mode, “Area No. Home Armed” will be displayed on the LCD screen along with 3 beeps indicating successful operation.
* **System Disarmed:** When the system changes to “System Disarmed” mode, “Area No. System Disarmed” will be displayed on the LCD screen along with 2 beeps indicating successful operation.
* **Exit/Entry Delay:** When the Entry/Exit delay timer is enabled in the Control Panel, and the Entry/Exit Beep function is enabled on the wired/wireless keypad, the wired/wireless keypad will count down with the system when Entry/Exit delay timer begins. "Counting Down Area No.” will be displayed on the LCD screen for 10 seconds. The green LED will also light up for 10 seconds along with 1 beep every second. After 10 seconds, the LCD screen and the green LED will turn off, but the warning beeps will continue with the system count down.
* **Operation Error:** “Operation Error” will be displayed on the LCD screen along with 2 beeps indicating unsuccessful operation; for instance, when you submit the mode change request from **Away Arm** to **Home Arm** mode.
* **Fault Display**: When the system arms with fault, “Fault Display” will be displayed on the LCD screen along with 3 beeps indicating arming fault.
* **Incorrect PIN Code:** When incorrect password is submitted, “Incorrect PIN Code” will be displayed on the LCD screen along with 4 beeps indicating wrong password entered.

_\<NOTE>_

* After the mode change request is submitted, if no signal is received from the Control Panel, the keypad will return to stand-by mode within 15 seconds.
* If there are 5 incorrect PIN Code attempts within 10 minutes, the wired/wireless keypad will be automatically locked up for 5 minutes. During this period, any operation will be invalid. When the lockup time expires, the wired/wireless keypad will emit. 1 long beep.

### _**Dual Key Alarm Functions**_

* The dual-key function is disabled by default. To enable it, enter the setting menu of the wired/wireless keypad to set alarm triggers (Choose **Setting > Panic Alarm/Fire Alarm/Medical Alarm > Enable**, and then press OK).
* Panic Alarm: Press “1 + 3” to trigger a Panic Alarm.
* Fire Alarm: Press “4 + 6” to trigger a Fire Alarm.
* Medical Alarm: Press “7 + 9” to trigger a Medical Alarm.
* When an alarm is triggered, “Alarm! Alarm!” will be displayed on the LCD screen, and the green LED will light up for 10 seconds.

### _**Beep Control:**_

This function is for you to set the keypad warning beep functions.

* **Entry/Exit Beep:** The function is disabled by default. To enable it, please choose **Setting > Beep Control > Entry/Exit Beep > Enable** in User Menu, and press OK to confirm the setting. The duration of Entry/Exit Beep lasts for 4 minutes at most.
* **Alarm Beep:** The function is disabled by default. To enable it, please choose **Setting > Beep Control > Alarm Beep > Enable** in User Menu, and press OK to confirm the setting. The duration of Alarm Beep lasts for 15 minutes at most.

## _**Fault Conditions**_

_When the wired/wireless keypad is under **NORMAL OPERATION MODE,**_

* If the Control Panel is in Away Armed mode, you CANNOT activate Home Armed Mode by the wired/wireless keypad. If you do so, the wired/wireless keypad will emit 2 beeps indicating the Control Panel is in Away Armed mode.
* When any fault situation is detected, the Yellow LED will flash once every 3 seconds. The Yellow LED behavior is decided by the Control Panel.
* If there are 5 incorrect PIN Code attempts within 10 minutes, the wired/wireless keypad will be automatically locked up for 5 minutes. During this period, any operation will be invalid. When the lockup time expires, the wired/wireless keypad will emit 1 long beep.

## _**Change of Batteries**_

1. Go to the Control Panel programming menu to bypass the KP tamper alarm.
2. Dismount the wired/wireless keypad.
3. Take out the two used batteries and press the tamper switch for more than 3 seconds to fully discharge before inserting new batteries. Do not mix new and used batteries.
4. Take out the used battery and press the tamper switch to discharge before putting in new batteries.
5. Screw back the wired/wireless keypad to the mounting surface with the mounting screws.
6. Put the Control Panel back to normal operation mode.

## _**Reset the Wired/Wireless Keypad to Factory Default**_

The wired/wireless keypad can be reset to clear all learnt-in data and return all settings to the default values by the steps below:

1. Please follow _**Change of Battery**_ steps for factory default.
2. Within 10 seconds after inserting batteries, enter “0000”. When the last digit of “0000” turns into “ ![](<.gitbook/assets/image (111).png>)” on the LCD screen, press “#” to reset the wired/wireless keypad to the default values.
3. “Reset Default” will be displayed on the LCD screen along with 3 beeps indicating successful operation.
4. All learnt-in data will be cleared.
5. Entry/ Exit Beeps will be disabled.
6. Alarm Beep will be disabled.
7. Dual Key alarm function will be disabled.

_\<NOTE>_

* Factory default setting can only be performed within 10 seconds after inserting the batteries. If the keypad does not wake up within 10 seconds after inserting the batteries, remove the batteries and try again.
* Whenever the keypad is removed from the Control Panel, it should be put to factory default as well to clear its Control Panel memory.
* _**Mounting the Wired/Wireless Keypad**_

To mount the wired/wireless keypad:

1. Remove the front cover by loosening the cover fixing screw using a screwdriver.
2. Use the 4 mounting holes on the back cover as a template to mark and drill mounting holes.
3. Drill 4 holes and insert the wall plugs. Ensure the wall plugs are flush with the mounting surface.
4. Screw the back cover onto the wall plugs.
5. Re-place the front cover onto the back cover. Screw the cover fixing screw.
6. The installation is now complete.

