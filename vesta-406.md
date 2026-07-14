# VESTA-406

KP-35 COMBO ADC

## **ADC WIRED/WIRELESS COMBO KEYPAD**&#x20;

{% hint style="warning" %}
Note: VESTA-406 Keypad is compatible with ADC panels only
{% endhint %}

<figure><img src="/broken/files/VnYq06y5Zz3hy3UPD15o" alt=""><figcaption></figcaption></figure>

KP-35-COMBO is a hardwired and wireless keypad designed to have quick access control of the system control panel. The keypad can send wired and wireless signals to and receive signals from the Control Panel within a wire distance, depending on the wire gauge and the total power consumption of all wired devices. The LCD screen will display information the system control panel sends back.

The wired/wireless keypad can either be mounted on a flat surface or a wall with screws. It also has a tamper protection switch which will be activated upon any unauthorized attempt to open the back cover.



## **Parts Identification**

![](<.gitbook/assets/Unknown image (432)>)

#### 1. Backlit LCD Display&#x20;

#### 2. Green LED

* The Green LED is off in stand-by mode.
* The Green LED will light up when any key is pressed.

#### 3. Yellow LED

* The Yellow LED will flash once every 3 seconds when any fault situation is detected, and turn to OFF when all fault conditions are restored. The LED’s behavior is controlled by the Control Panel.

#### 4. Backlit Numeric Keys&#x20;

#### 5. Backlit Star (＊) Key&#x20;

#### 6. Backlit Pound (＃) Key&#x20;

#### 7. Backlit OK Key&#x20;

#### 8. Backlit Restore (![](<.gitbook/assets/Unknown image (433)>)) Key

* For confirming the keyed-in data or confirming the selection.\*\*\*\*
* This key is is used for deleting a digit, canceling the selection, aborting the current screen, and returning to the previous screen etc.

#### 9. Backlit Arm/  <img src=".gitbook/assets/image (1345).png" alt="" data-size="line">Key

* Use this key to move the cursor and scroll the display upwards - The key is also used for entering “Away Armed” mode.

#### 10. Backlit Home Arm/ ![](<.gitbook/assets/image (1346).png>) Key

* Use this key to move the cursor and scroll the display downwards. - The key is also used for entering “Home Armed” mode.

#### 11. Buzzer&#x20;

#### 12. Battery Compartment&#x20;

#### 13. Keypad Terminal

* Hardwiring the four terminals (V, G, A, B) to the Keypad Terminal on the Control Panel. Up to four KP-35-COMBOs can be connected in series. For keypad wiring, refer to _**Keypad Wiring**_ section on the next page for detail.

#### 14. Jumper Switch

**Jumper Off**

If the jumper is OFF (the jumper link is removed or “parked” on one pin), the communication ability is in normal level.

If the jumper is ON, the communication ability is enhanced.&#x20;

* When the keypad is connected as the furthest BUS device from the Control Panel, please set the keypad’s communication Jumper Switch and the Control Panel’s J53 Jumper Switch to ON to serve as a terminating resistor. The connected BUS devices’ communication ability will be enhanced.

#### **15. Wire Management Hole**&#x20;

#### **16. Tamper Switch**&#x20;

#### **17. Cover Fixing Screw x 1**&#x20;

#### **18. Mounting Holes x 4**

* Prepunched hole used to enhance wiring management flexibility.

## Caution ![](<.gitbook/assets/Unknown image (438)>)

* Wiring of the wired/wireless keypad should only be performed by certified technician with proper knowledge and training in electric equipment.
* Before installation or any maintenance work, make sure the power supply of the Control Panel has been disconnected.

## Features

### Power Supply Input

When KPT-35-Combo is hardwired to Control Panel, 13.5V (typical) power supply can be provided by the Control Panel to KPT-35-Combo.

### Battery and Low Battery Detection

* Two L91 1.5V AA lithium batteries can be installed inside the battery compartment to serve as a backup power source in case of power failure. Prior to inserting batteries, ensure correct battery placement to protect your device.
*
* The wired/wireless keypad can also monitor the battery life. When the batteries are low in power, a low battery signal will be sent along with regular signal transmission to the Control Panel to alert users to battery replacement.

{% hint style="info" %}
Note: Use only the specified batteries with the device. When replacing batteries, always replace the whole set and do not mix different types of batteries or new and used ones to avoid damaging the device.
{% endhint %}

### Power Saving Feature

* When idle, the wired/wireless keypad is in **stand-by** mode and consumes no power. It will wake up when any key is pressed.
* After entering User Menu, if neither of the **Arm** key/**Home Arm** key is pressed, the wired/wireless keypad will return to **stand-by** mode within 5 seconds. If either or both of the **Arm** key/**Home Arm** key is/are pressed, the wired/wireless keypad will return to stand-by mode within **20** seconds.
* After “Enter PIN Code” is displayed on the LCD screen, if no key is pressed, the wired/wireless keypad will return to **stand-by** mode within 5 seconds.
* After the mode change request is submitted, if no signal is received from the Control Panel, the keypad will return to\*\* stand-by\*\*mode within 15 seconds.
* Upon completion of a command input, the wired/wireless keypad will return to **stand-by** mode.

### Keypad Wiring

* To connect KP-35-COMBO to the Control Panel, open the front cover by using a Phillips screwdriver to loosen the cover fixing screw.
* Before connecting the “V”, “G”, “A”, “B” terminals, remove the batteries in KP-35-COMBO and make sure the power supply of the Control Panel has been disconnected.
* Loosen KP-35-COMBO’s “V” terminal and the Control Panel’s “VDD” terminal. Connect the “V” terminal to the “VDD” terminal and tighten both terminal screws.
* Loosen KP-35-COMBO’s “G” terminal and the Control Panel’s “GND” terminal. Connect the “G” terminal to the “GND” terminal and tighten both terminal screws.
* Loosen KP-35-COMBO’s “A” terminal and the Control Panel’s “485A” terminal. Connect the “A” terminal to the “485A” terminal and tighten both terminal screws.
* Loosen KP-35-COMBO’s “B” terminal and the Control Panel’s “485B” terminal. Connect the “B” terminal to the “485B” terminal and tighten both terminal screws.
* Power on the Control Panel and wait for the “KP-35 COMBO” to be shown on the wired/wireless keypad’s LCD screen.

<figure><img src=".gitbook/assets/image (1347).png" alt=""><figcaption></figcaption></figure>

* The keypad terminal can be hardwired to the Control Panel. Up to four KP-35-Combos can be connected in series. The maximum wire cable length depends on the wire gauge and the total power consumption of all wired devices; for example: maximum 3000ft @ 22-AWG cable for one KP-35-Combo; maximum 1500ft @ 22-AWG cable for 2 KP-35-Combos; or maximum 1000ft @ 22-AWG cable for 3 KP-35-Combos.
* In the picture below, KP-35-Combo-**A** and KP-35-Combo-**B** are wired correctly in series as the total wire distance of the two keypads from the Control Panel is within 1500ft. For KP-35-Combo-**C** in the picture below, it is **NOT** wired correctly as it is farther than 1000ft from the Control Panel.
* For optimal communication of the wired connection between the Control Panel and the connected BUS devices, ensure the furthest BUS device’s Communication Jumper Switch and the Control Panel’s J53 Jumper Switch are set to ON to serve as a terminating resistor. Be sure to only enable the aforementioned 2 jumper switches and do not set the jumper switches to ON for any other BUS devices in between. For example, for the\*\*\*\*KP-35-Combo-**B** in the picture below, before tightening the cover fixing screw of the keypad, ensure its jumper switch is set to ON to serve as a terminating resistor since it has the furthest distance from the Control Panel.

<figure><img src=".gitbook/assets/image (1348).png" alt=""><figcaption></figcaption></figure>

### Tamper Protection

* The wired/wireless keypad is protected against any unauthorized attempts to open the back cover with a tamper switch. When the back cover is opened, the tamper switch will be triggered and the wired/wireless keypad will transmit a tamper open signal to the system control panel.
* After re-placing the back cover, the wired/wireless keypad will transmit a tamper restore signal to the Control Panel.
* When the wired/wireless keypad is properly mounted with back cover screwed onto the wall, removing the keypad forcefully will break off the back cover from the hollowed section around the screw location and activate tamper switch.

### Supervision Signal

* When in wired mode, the wired/wireless keypad will automatically transmit Supervision Signals to the Control Panel at an interval of 75 seconds.
* When in wireless mode, the wired/wireless keypad will automatically transmit Supervision Signals to the Control Panel at an interval of 15-18 minutes.
* If the Control Panel has not received the signal from the wired/wireless keypad for a preset period of time, the Control Panel will consider the wired/wireless keypad out of order and react according to panel setting.

### System Status Check

The wired/wireless keypad allows the user to check the status of the system. When the Control Panel is not under alarm activation or exits delay status, press the OK key and the current status will be displayed on the LCD screen for 3 seconds. There are three different statuses: Away Armed, Home Armed, and System Disarmed.

### System Mode Change

Users can use the keypad to change the system mode via a PIN code.

* **To change the system mode with a PIN Code:**

After entering the PIN code, press the **Arm/Home Arm/OK** key to enter **Away Armed/Home Armed/System Disarmed** mode.\*\*\*\*

* When the system mode is changed to disarmed mode, the LCD will show “Area No. Alarm Memory” and Yellow LED will flash once every 3 seconds with 5 beeps if there is/are alarm(s) triggered before. Users can manually enter User Menu to view the alarm memory (please refer to User Menu section below for details).
* \*\*Quick Arm Function:\*\*Users can enter Setting Menu to activate the Quick Arm Function (Choose **Setting > Quick Arm > Enable**, and then press OK), which will allow users to change mode by pressing the Arm key or the Home Arm key without entering the PIN code. To disarm the system, users still need to enter the PIN code.

### User Menu

* The keypad will communicate with the system to retrieve information before entering User Menu. The following options will be displayed on LCD screen for selection. Use  and  key to select, and then press the **OK** key to confirm your selection.
* The system is always automatically disarmed upon entering User Menu.
* The keypad will exit User Menu automatically after 20 seconds of inactivity.

<figure><img src=".gitbook/assets/image (1349).png" alt=""><figcaption></figcaption></figure>

* **Away Arm:** Select “Away Arm” and press the OK key to change the system mode to “Away Armed”.
* **Home Arm:** Select “Home Arm” and press the OK key to change the system mode to “Home Armed”.
* **Alarm Memory:**&#x54;his option will become available after an alarm is triggered. Entering the keypad’s User Menu will be directed to the Alarm Memory option automatically. Press **OK** to confirm the selection and use  and  keys to view the alarm memory. \*\*\*\*
* **Fault Display:**&#x54;his option will become available when fault event exists in the system. To view fault events, select “Fault Display” and press OK to confirm the selection. Use  and  keys to view the fault events and press  key to return to menu.

{% hint style="info" %}
Note:&#x20;

* The Yellow LED will flash once every 3 seconds when any fault situation is detected, and turn to OFF when all fault situations are cleared.
* If you try to arm the system when fault event exists, the arming will be prohibited and the LCD screen will jump to Fault Display. If you want to forcibly arm the system, perform the arm action again within 30 seconds. The system will ignore the fault event and enter your selected arm mode.
{% endhint %}

* **Log**: Select “Log” and press OK to view the system log. Use  and  keys to view the events and press  key to return to User Menu.
* **Setting:**&#x53;elect “Setting” and press OK enter setting menu. Use  and  keys to select setting options and press  key to return to User Menu.

<figure><img src=".gitbook/assets/image (1350).png" alt=""><figcaption></figcaption></figure>

### Mode Change Result

* **Away Armed:** When system changes to “Away Armed” mode, “Away Armed” will be displayed on the LCD screen along with a long beep indicating successful operation.
* **Home Armed:** When system changes to “Home Armed” mode, “Home Armed” will be displayed on the LCD screen along with 3 beeps indicating successful operation.
* **System Disarmed:** When system changes to “System Disarmed” mode, “System Disarmed” will be displayed on the LCD screen along with 2 beeps indicating successful operation.
* **Exit/Entry Delay:When the Entry/Exit delay timer is enabled in the Control Panel, and the Entry/Exit Beep function is enabled on the wired/wireless keypad, the wired/wireless keypad will count down with the system when Entry/Exit delay timer begins. "Counting Down” will be displayed on the LCD screen for 10 seconds. The green LED will also light up for 10 seconds along with 1 beep every second. After 10 seconds, the LCD screen and the green LED will turn off, but the warning beeps will continue with the system count down.**
* **Operation Error:** “Operation Error” will be displayed on the LCD screen along with 2 beeps indicating unsuccessful operation; for instance, when you submit the mode change request from **Away Arm** to **Home Arm** mode.
* **Fault Display**: When the system arms with fault, “Fault Display” will be displayed on the LCD screen along with 3 beeps indicating arming fault.
* **Incorrect PIN Code:** When incorrect password is submitted, “Incorrect PIN Code” will be displayed on the LCD screen along with 4 beeps indicating wrong password entered.

{% hint style="info" %}
Note:&#x20;

* After the mode change request is submitted, if no signal is received from the Control Panel, the keypad will return to stand-by mode within 15 seconds.
* If there are 5 incorrect PIN Code attempts within 10 minutes, the wired/wireless keypad will be automatically locked up for 5 minutes. During this period, any operation will be invalid. When the lockup time expires, the wired/wireless keypad .will emit 1 long beep.
* When the keypad is used with EN2-enabled Control Panel, consecutive incorrect User PIN code attempts to change the system mode (5 times within 10 minutes) will cause the Control Panel to temporarily reject any user codes entered via the keypad for 15 minutes to prevent malicious attacks.
{% endhint %}

### Dual Key Alarm Functions

* The dual-key function is disabled by default. To enable it, enter the setting menu of the wired/wireless keypad to set alarm triggers (Choose **Setting > Panic Alarm/Fire Alarm/Medical Alarm > Enable**, and then press OK).
* Panic Alarm: Press “1 + 3” to trigger a Panic Alarm.
* Fire Alarm: Press “4 + 6” to trigger a Fire Alarm.
* Medical Alarm: Press “7 + 9” to trigger a Medical Alarm.
* When an alarm is triggered, “Alarm! Alarm!” will be displayed on the LCD screen, and the green LED will light up for 10 seconds.

### _**Beep Control:**_

This function is for you to set the keypad warning beep functions.\*\*\*\*

* **Entry/Exit Beep:** The function is disabled by default. To enable it, please choose **Setting > Beep Control > Entry/Exit Beep > Enable** in the user menu, and press OK to confirm the setting.
* **Alarm Beep:The function is disabled by default. To enable it, please choose Setting > Beep Control > Alarm Beep > Enable in the user menu, and press OK to confirm the setting.**

### Joining in the System Network

**Wireless Operation:**

* To add the wired/wireless keypad to the system network, first put the Control Panel in learning mode.
* Press the OK key once. When “Enter PIN Code” is displayed on the LCD screen, press and hold the **OK** key for 10 seconds.
* “KP will reset in 2 seconds” will be displayed on the LCD screen along with a long beep.
* “Scanning Network” will be displayed on the LCD screen while the wired/wireless keypad is sending learning code to the Control Panel.
* When the keypad is added to the Control Panel, “Learning Success” will be displayed on the LCD screen along with 2 beeps.

{% hint style="info" %}
Note:&#x20;

* If the Control Panel promptly responds to the wired/wireless keypad, the “Scanning Network” process will be skipped, and “Learning Success” will be directly displayed on the LCD screen.
* If the wired/wireless keypad does not receive any signal from the Control Panel within 30 seconds, the LCD screen will be turned off, and the wired/wireless keypad will return to stand-by mode.
{% endhint %}

**Hardwiring Operation:**

In addition to the wireless operation to join the system network as stated above, the user can do it through hardwiring.

**Step 1.** Connect the keypad to the Panel through wiring.

**Step 2.** Choose a located area and a free zone to join the system network.

<figure><img src=".gitbook/assets/image (1351).png" alt=""><figcaption></figcaption></figure>

**Step 3.** Enter the PIN Code of the located area.

<figure><img src=".gitbook/assets/image (1352).png" alt=""><figcaption></figcaption></figure>

**Step 4.** Enter Installer Code. (Factory Default: 7982)

<figure><img src=".gitbook/assets/image (1353).png" alt=""><figcaption></figcaption></figure>

**Step 5.** The keypad is added to the located area and the zone chosen.

<figure><img src=".gitbook/assets/image (1354).png" alt=""><figcaption></figcaption></figure>

### Identification

The “**Identify**” function is used to localize a specific wired device in the whole wired system. This function is helpful in distinguishing which device is which especially in a large installation where numeral wired devices are included. To locate the wired keypad in the wired system:

**Step 1.** On the Panel’s webpage, click “Identify” under the device list after the Keypad’s device column entry.

**Step 2.** If KP-35-Combo receives the signal from the Panel, the webpage will display a success message and the white backlight of the wired/wireless keypad will flash 10 times to indicate where it is to the user.

{% hint style="info" %}
Note:  If a timeout message is displayed on the webpage, it means the wired/wireless keypad did not receive the signal from the Panel.

Please check whether KP-35-Combo is connected properly to the Panel within appropriate wiring distance.
{% endhint %}

### Edit Device Operation Area

1. Use the “Edit Device” function on the Panel’s webpage to change the area setting.
2. For Hardwiring Operation, area change is complete.

For Wireless Operation, press and hold the OK key for 10 seconds to transmit learn code to the Panel and complete area update.

### Fault Conditions

_When the wired/wireless keypad is under**NORMAL OPERATION MODE,**_

* If the Control Panel is in Away Armed mode, you CANNOT activate Home Armed Mode by the wired/wireless keypad. If you do so, the wired/wireless keypad will emit 2 beeps indicating the Control Panel is in Away Armed mode.
* When any fault situation is detected, the Yellow LED will flash once every 3 seconds. The Yellow LED behavior is decided by the Control Panel.
* If there are 5 incorrect PIN Code attempts within 10 minutes, the wired/wireless keypad will be automatically locked up for 5 minutes. During this period, any operation will be invalid. When the lockup time expires, the wired/wireless keypad will emit 1 long beep.
* When the keypad is used with EN2-enabled Control Panel, consecutive incorrect User PIN code attempts to change the system mode (5 times within 10 minutes) will cause the Control Panel to temporarily reject any user codes entered via the keypad for 15 minutes to prevent malicious attacks.

### Change of Batteries

1. Go to the Control Panel programming menu to bypass the KP tamper alarm.
2. Dismount the wired/wireless keypad.
3. Take out the two old batteries and press the tamper switch for more than 3 seconds to fully discharge before inserting new batteries. Do not mix new and used batteries.
4. Take out the used batteries and press the tamper switch to discharge before putting in new batteries.
5. Screw back the wired/wireless keypad to the mounting surface with the mounting screws.
6. Put the Control Panel back to normal operation mode.

### Reset the Wired/Wireless Keypad to Factory Default

The wired/wireless keypad can be reset to clear all learnt-in data and return all settings to the default values by the steps below:

1. Please follow _**Change of Batteries**_ steps for factory default.
2. Within 10 seconds after inserting the batteries, enter “0000”. When the last digit of “0000” turns into “” on the LCD screen, press “#” to reset the wired/wireless keypad to default values.
3. “Reset Default” will be displayed on the LCD screen along with 3 beeps indicating successful operation.
4. All learnt-in data will be cleared.
5. Entry/ Exit Beeps will be disabled.
6. Alarm Beep will be disabled.
7. Dual Key alarm function will be disabled.

{% hint style="info" %}
Note:&#x20;

* Factory default setting can only be performed within 10 seconds after inserting the batteries. If the keypad does notwake up within 10 seconds after inserting the batteries, remove the batteries and try again.
* Whenever the keypad is removed from the Control Panel, it should be put to factory default as well to clear its Control Panel memory.
{% endhint %}

### Mounting the Wired/Wireless Keypad

To mount the wired/wireless keypad:

1. Remove the front cover by loosening the cover fixing screw using a screwdriver.
2. Use the 4 mounting holes on the back cover as a template to mark and drill mounting holes.
3. Drill 4 holes and insert the wall plugs. Ensure the wall plugs are flush with the mounting surface.
4. Screw the back cover onto the wall plugs.
5. Re-place the front cover onto the back cover. Screw the cover fixing screw.
6. The installation is now complete.
