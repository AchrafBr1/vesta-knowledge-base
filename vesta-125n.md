# VESTA-125N

**KPT-35N-Combo-BYD**

## **WIRED/WIRELESS COMBO KEYPAD with NFC READER**

KPT-35N-Combo-BYD is a hardwired and wireless keypad with an NFC reader designed to have quick access control of the system control panel. The keypad can send wired and wireless signals to and receive signals from the Control Panel within wire distance, depending on the wire gauge and the total power consumption of all wired devices. The LCD screen will display information the system control panel sends back.

The wired/wireless keypad can either be mounted on a flat surface or a wall with screws. It also has a tamper protection switch which will be activated upon any unauthorized attempt to open the back cover.

## **Parts Identification**

![](<.gitbook/assets/1 (10).png>)

1. **Backlit LCD Display**
2. **Green LED**
   * The Green LED is off in stand-by mode.
   * The Green LED will light up when any key is pressed.
3. **Yellow LED**
   * The Yellow LED will flash once every 3 seconds when any fault situation is detected, and turn to OFF when all fault conditions are restored. The LED’s behavior is controlled by the Control Panel.
4. **Backlit Numeric Keys**
5. **Backlit Star (＊) Key**
6. **Cover Case**
7. **Backlit Restore (**![](<.gitbook/assets/2 (9).jpeg>)) **Key**
   * This key is is used for deleting a digit, canceling the selection, aborting the current screen, and returning to the previous screen etc.
8. **Backlit OK Key**
9. **Backlit Pound (＃) Key**
   * For confirming the keyed-in data or confirming the selection.
10. **Backlit Arm/ " UP ARROW " Key**
    * Use this key to move the cursor and scroll the display upwards
    * The key is also used for entering “Away Armed” mode.
11. **Backlit NFC Sensor Zone**
12. **Backlit Home Arm/"DOWN ARROW" Key**
    * Use this key to move the cursor and scroll the display downwards.
    * The key is also used for entering “Home Armed” mode.
13. **Buzzer**
14. **Battery Compartment**
15. **BUS Terminal**
    * Hardwiring the four terminals (V, G, A, B) to the Keypad Terminal on the Control Panel. Up to four KPT-35N-Combo-BYDs can be connected in series. For keypad wiring, refer to _**Keypad Wiring**_ section on the next page for detail.
16. **Wire Management Hole**
    * Prepunched hole used to enhance wiring management flexibility.

**17.** **Terminal Resistor Jumper Switch**

When the keypad is connected as the furthest BUS device from the Control Panel, please set the keypad’s communication Jumper Switch and Control Panel’s J53 Jumper Switch to ON to serve as a terminating resistor. The connected BUS devices’ communication ability will be enhanced.

**Jumper On**

<figure><img src=".gitbook/assets/jumper on.png" alt=""><figcaption></figcaption></figure>

If the jumper is ON, the communication ability will be enhanced.

**Jumper Off**

![](<.gitbook/assets/5 (6).jpeg>)

If the jumper is OFF (the jumper link is removed or “parked” on one pin), the communication ability is in normal level.

18. **Tamper Switch**
19. **Bracket Holes x 3**
20. **Mounting Holes x 4**
21. **Bottom Fixing Screw x 1**
22. **NFC Tag**

**Caution**

* Wiring of the wired/wireless keypad should only be performed by certified technicians with proper knowledge and training in electric equipment.
* Before installation or any maintenance work, make sure the power supply of the Control Panel has been disconnected.

## **Supported Control Panel Models**

* The wired/wireless keypad supports the following models:
  * Hybrid Panel Series
  * HSGW Series
  * ESGW Series
* The wired/wireless keypad currently does not support BOGP-3 Series.

## **Features**

### _**Power Supply Input**_

When KPT-35N-Combo-BYD is hardwired to Control Panel, 13.5V (typical) power supply can be provided by the Control Panel to KPT-35N-Combo-BYD.

### _**Battery and Low Battery Detection**_

* Two L91 1.5V AA lithium batteries can be installed inside the battery compartment to serve as a backup power source in case of power failure. Prior to inserting batteries, ensure correct battery placement to protect your device.
* The wired/wireless keypad can also monitor the battery life. When batteries are low in power, a low battery signal will be sent along with regular signal transmission to the Control Panel to alert users to battery replacement.

{% hint style="warning" %}
Note:

Use only the specified batteries with the device. When replacing batteries, always replace the whole set and do not mix different types of batteries or new and used ones to avoid damaging the device.
{% endhint %}

### _**Power Saving Feature**_

* When idle, the wired/wireless keypad is in **stand-by** mode and consumes no power. It will wake up when any key is pressed.
* After entering User Menu, if neither of the **Arm** key/**Home Arm** key is pressed, the wired/wireless keypad will return to **stand-by** mode within 5 seconds. If either or both of the **Arm** key/**Home Arm** key is/are pressed, the wired/wireless keypad will return to stand-by mode within **20** seconds.
* After “Enter PIN Code” is displayed on the LCD screen, if no key is pressed, the wired/wireless keypad will return to **stand-by** mode within 5 seconds.
* After the mode change request is submitted, if no signal is received from the Control Panel, the keypad will return to **stand-by** mode within 15 seconds.
* Upon completion of a command input, the wired/wireless keypad will return to **stand-by** mode.

### _**Keypad Wiring**_

* To connect KPT-35N-Combo-BYD to the Control Panel, open the front cover by using a Phillips screwdriver to loosen the cover fixing screw.
* Before connecting the “V”, “G”, “A”, “B” terminals, remove the batteries from KPT-35N-Combo-BYD and make sure the power supply of the Control Panel has been disconnected.
* Loosen KPT-35N-Combo-BYD’s “V” terminal and the Control Panel’s “VDD” terminal. Connect the “V” terminal to the “VDD” terminal and tighten both terminal screws.
* Loosen KPT-35N-Combo-BYD’s “G” terminal and the Control Panel’s “GND” terminal. Connect the “G” terminal to the “GND” terminal and tighten both terminal screws.
* Loosen KPT-35N-Combo-BYD’s “A” terminal and the Control Panel’s “485A” terminal. Connect the “A” terminal to the “485A” terminal and tighten both terminal screws.
* Loosen KPT-35N-Combo-BYD’s “B” terminal and the Control Panel’s “485B” terminal. Connect the “B” terminal to the “485B” terminal and tighten both terminal screws.
* Power on the Control Panel and wait for the “KPT-35N-Combo-BYD” to be shown on the wired/wireless keypad’s LCD screen.

![](<.gitbook/assets/9 (13).png>)

* The keypad terminal can be hardwired to the Control Panel. Up to four KPT-35N-COMBO-BYDs can be connected in series. The maximum wire cable length depends on the wire gauge and the total power consumption of all wired devices, for example: maximum 3000ft @ 22-AWG cable for one KPT-35N-COMBO-BYD; maximum 1500ft @ 22-AWG cable for 2 KPT-35N-COMBO-BYDs; or maximum 1000ft @ 22-AWG cable for 3 KPT-35N-COMBO-BYDs.
* In the picture below, KPT-35N-COMBO-BYD-**A** and KPT-35N-COMBO-BYD-**B** are wired correctly in series as the total wire distance of two keypads from the Control Panel is within 1500ft. For the KPT-35N-COMBO-BYD-**C** in the picture below, it is **NOT** wired correctly as it is farther than 1000ft from the Control Panel.
* For optimal communication of the connected BUS line devices, ensure the terminal resistor jumper switches of the first and the furthest BUS devices on a BUS line are set to ON to serve as terminating resistors. Be sure to only enable the aforementioned 2 jumper switches, and do not set the jumper switches to ON for any other BUS devices in between. For example, for KPT-35N-COMBO-BYD-**B** in the picture below, it is the farthest device on the BUS line, and Hybrid Panel is the first device on the BUS line. Ensure to set the KPT-35N-COMBO-BYD-**B**'s terminal resistor jumper switch and Hybrid Panel's J53 Jumper Switch to ON to serve as terminating resistors.

![](<.gitbook/assets/10 (14).png>)

### _**Tamper Protection**_

* The wired/wireless keypad is protected against any unauthorized attempts to open the back cover with a tamper switch. When the back cover is opened, the tamper switch will be triggered and the wired/wireless keypad will transmit a tamper open signal to the system control panel.
* After re-placing the back cover, the wired/wireless keypad will transmit a tamper restore signal to the Control Panel.
* When the wired/wireless keypad is properly mounted with back cover screwed onto the wall, removing the keypad forcefully will break off the back cover from the hollowed section around the screw location and activate tamper switch.

### _**Supervision Signal**_

* When in wired mode, the wired/wireless keypad will automatically transmit Supervision Signals to the Control Panel at an interval of 20-30 seconds.
* When in wireless mode, the wired/wireless keypad will automatically transmit Supervision Signals to the Control Panel at an interval of 30-50 minutes.
* If the Control Panel has not received the signal from the wired/wireless keypad for a preset period of time, the Control Panel will consider the wired/wireless keypad out of order and react according to panel setting.

### _**Label Addition/Deletion Procedures**_

The Keypad is capable of transmitting NFC (Near Field Communication) signals to the Control Panel, and you can assign a PIN Code and user name to each NFC label on the Panel webpage. The NFC labels can then be used to control alarm system mode through the Keypad. The number of NFC labels and PIN Codes are managed on the Control Panel webpage.

1. _**Add Label:**_

When adding a new label, the keypad must be in normal operation mode.

Step 1. Go to the PIN Code page on the Control Panel webpage, input a 4-digit or 6-digit user pin code and user name for the tag, assign the user pin code to an Area.

![](<.gitbook/assets/11 (10).png>)

Step 2. After KPT-35N-COMBO-BYD is successfully learnt into the panel, apply a new label to the Keypad Tag sensor zone. The white backlight will turn on with 4 beeps to indicate this label is new (not added to the system yet).

Step 3. Click the Load button on the PIN Code page as below. The corresponding label number will be loaded. Click Submit to save the user code setting.

![](<.gitbook/assets/12 (12).png>)

Step 4. The label has been added. You can use the label to arm/home arm/disarm the system. When Keypad is powered on by inserting batteries, the Orange LED will flash and the white backlight will turn on. When LED is off, wait 10 seconds for keypad tag sensor to start functioning.

{% hint style="warning" %}
Note:

Consecutively sensing 5 unadded labels or unadded label(s) for 5 times will generate an error record and cause the Keypad to be locked up for 5 minutes. To prevent lockup from happening, an added label must be sensed once to clear the error record.

If the Keypad is locked up, it will be automatically unlocked after the 5-minute lockup period expires.
{% endhint %}

_**B. Clear label:**_

Step 1. Go to the PIN Code page on the Control Panel webpage.

Step 2. Manually delete the label number and click Submit.

![](<.gitbook/assets/13 (12).png>)

Step 3. The label is cleared.

## _**Joining the System Network**_

### **Wireless Operation:**

* To add the wired/wireless keypad to the system network, first put the Control Panel in learning mode.
* **Press the OK key once. When “Enter PIN Code” is displayed on the LCD screen, press and hold the OK key for 10 seconds.**
* “KP will reset in 2 seconds” will be displayed on the LCD screen along with a long beep.
* “Scanning Network” will be displayed on the LCD screen while the wired/wireless keypad is sending learning code to the Control Panel.
* When the keypad is added to the Control Panel, “Learning Success” will be displayed on the LCD screen along with 2 beeps.

{% hint style="warning" %}
Note:

If the Control Panel promptly responds to the wired/wireless keypad, the “Scanning Network” process will be skipped, and “Learning Success” will be directly displayed on the LCD screen.

If the wired/wireless keypad does not receive any signal from the Control Panel within 20 seconds, the LCD screen will be turned off, and the wired/wireless keypad will return to stand-by mode.
{% endhint %}

### **Hardwiring Operation:**

In addition to the wireless operation to join the system network as stated above, the user can do it through hardwiring.

**Step 1.** Connect the Keypad to the Panel through wiring.

**Step 2.** Choose a located area and a free zone to join the system network.

<figure><img src=".gitbook/assets/1 (123).png" alt=""><figcaption></figcaption></figure>

**Step 3.** Enter the PIN Code of the located area.

<figure><img src=".gitbook/assets/4 (122).png" alt=""><figcaption></figcaption></figure>

**Step 4.** Enter Installer Code. (Factory Default: 7982)

<figure><img src=".gitbook/assets/5 (122).png" alt=""><figcaption></figcaption></figure>

**Step 5.** The keypad is added to the located area and the zone you chose.

<figure><img src=".gitbook/assets/2 (132).png" alt=""><figcaption></figcaption></figure>

### _**Identification**_

The “**Identify**” function is used to localize a specific wired device in the whole wired system. This function is helpful in distinguishing which device is which especially in a large installation where numerous wired devices are included.

To locate KPT-35N-Combo-BYD in the wired system:

**Step 1.** On the Panel’s webpage, click “Identify” under the device list after the Keypad’s device column entry.

**Step 2.** If KPT-35N-Combo-BYD receives the signal from the Panel, the webpage will display a success message and the white backlight of the wired/wireless keypad will flash 10 times to indicate where it is to the user.

{% hint style="warning" %}
Note:

If a timeout message is displayed on the webpage, it means the wired/wireless keypad did not receive the signal from the Panel. Please check whether KPT-35N-Combo-BYD is connected properly to the Panel within proper wiring distance.
{% endhint %}

### _**Area Status Check**_

* The wired/wireless keypad allows the users to check the status mode of each area. When the Control Panel is under stand-by mode, press the OK key and the current status of each area will be displayed on the LCD screen for 3 seconds.
* There are three different statuses: A = Away Armed / H = Home Armed / D = System Disarmed.
* A question mark “?” will be displayed if the area status cannot be identified.
* Example:

<figure><img src=".gitbook/assets/3 (119).png" alt=""><figcaption></figcaption></figure>

### _**System Mode Change**_

Users can use the keypad to change the system mode with a PIN code or an NFC label.

1. **Change the system mode with a PIN Code:**

After entering the PIN code, press the **Arm/Home Arm/OK** key to enter **Away Armed/Home Armed/System Disarmed** mode.

1. **Change the system mode with a label:**

Press the **Arm/Home Arm/OK** key, and then swipe the label. If the label info is correct, “Success” will be displayed on the LCD screen, indicating that the system has entered **Away Armed/Home Armed/System Disarmed** mode.

* When the system mode is changed to disarmed mode, the LCD will show “Area No. Alarm Memory” and Yellow LED will flash once every 3 seconds with 5 beeps if there is/are alarm(s) triggered before. Users can manually enter User Menu to view the alarm memory (please refer to User Menu section below for details).
* **Quick Arm Function:** Users can enter Setting Menu to activate the Quick Arm Function (Choose **Setting > Quick Arm > Enable**, and then press OK), which will allow users to change the mode by pressing the Arm key or the Home Arm key without entering the PIN code or swiping the label. To disarm the system, users still need to enter PIN code or use the label.
* After entering User Menu with the system disarmed, users can also select **Away Arm** or **Home Arm**, and press OK to change the system mode.

### _**User Menu**_

* The keypad will communicate with the system to retrieve information before entering User Menu. The following options will be displayed on the LCD screen for selection. Use "UP ARROW" and "DOWN ARROW" keys to select, and press the **OK** key to confirm your selection.
* To enter User Menu, press and hold “**＊**” for 2 seconds in idle mode of the keypad when the system of the area where KPT-35N-Combo-BYD is located is already in **Disarmed mode**.
* The keypad will exit User Menu automatically after 20 seconds of inactivity.

<figure><img src=".gitbook/assets/4 (123).png" alt=""><figcaption></figcaption></figure>

* **Away Arm:** Select “Away Arm” and press the OK key to change the system mode to “Away Armed”.
* **Home Arm:** Select “Home Arm” and press the OK key to change the system mode to “Home Armed”.
* **Alarm Memory:** This option will become available after an alarm is triggered. Entering User Menu will be directed to the Alarm Memory option automatically. Press **OK** to confirm the selection, and then use **** and **** keys to view the alarm memory.
* **Fault Display:** This option will become available when fault event exists in system. To view fault events, select “Fault Display” and press OK to confirm the selection. Use  and  keys to view the fault events and press key to return to User Menu.

{% hint style="warning" %}
Note:

The Yellow LED will flash once every 3 seconds when any fault situation is detected, and turn to OFF when all fault situations are cleared.

If you try to arm the system when fault event exists, the arming will be prohibited and the LCD screen will jump to Fault Display. If you want to forcibly arm the system, perform the arm action again within 30 seconds. The system will ignore the fault event and enter your selected arm mode.
{% endhint %}

* **Log:** Select “Log” and press OK to view the system log. Use "UP ARROW" and "DOWN ARROW" keys to view the events and press key to return to User Menu.
* **Bypass:** This function is only available under wired connection. “Enter M. Code” will be shown on the LCD screen (default M. Code is **1111**). The Panel will ignore all signals received from the device being bypassed and not respond at all when such device is triggered.
* **Setting:** For wireless connection, after entering User Menu, input the default M. Code “**1111**” to enter the setting menu. For wired connection, input the default I. code “**7982**” to enter the setting menu. Use  and  keys to select setting options and press key to return to User Menu.

<figure><img src=".gitbook/assets/5 (123).png" alt=""><figcaption></figcaption></figure>

* **Language:** Select “Language” and press OK key to enter the language menu. Use"UP ARROW" and "DOWN ARROW" keys to select the 6 language for display, and press key to return to User Menu.

<figure><img src=".gitbook/assets/6 (102).png" alt=""><figcaption></figcaption></figure>

* **Change M. Code:** This function is only available under wireless connection. The default M. code is **1111**. Users can change it manually, and only when the correct M. Code is entered can the user enter the setting menu.

### _**Mode Change Result**_

* **Away Armed:** When the system changes to “Away Armed” mode, “Area No. Away Armed” will be displayed on the LCD screen along with a long beep indicating successful operation.
* **Home Armed:** When the system changes to “Home Armed” mode, “Area No. Home Armed” will be displayed on the LCD screen along with 3 beeps indicating successful operation.
* **System Disarmed:** When the system changes to “System Disarmed” mode, “Area No. System Disarmed” will be displayed on the LCD screen along with 2 beeps indicating successful operation.
* **Exit/Entry Delay:** When the Entry/Exit delay timer is enabled in the Control Panel, and the Entry/Exit Beep function is enabled on the wired/wireless keypad, the wired/wireless keypad will count down with the system when Entry/Exit delay timer begins. "Counting Down Area No.” will be displayed on the LCD screen for 10 seconds. The green LED will also light up for 10 seconds along with 1 beep every second. After 10 seconds, the LCD screen and the green LED will turn off, but the warning beeps will continue with the system count down.
* **Operation Error:** “Operation Error” will be displayed on the LCD screen along with 2 beeps indicating unsuccessful operation; for instance, when you submit the mode change request from **Away Armed** to **Home Armed** mode.
* **Fault Display**: When the system arms with fault, “Fault Display” will be displayed on the LCD screen along with 3 beeps indicating arming fault.
* **Incorrect PIN Code:** When incorrect password is submitted, “Incorrect PIN Code” will be displayed on the LCD screen along with 4 beeps indicating wrong password entered.

{% hint style="warning" %}
Note:

After the mode change request is submitted, if no signal is received from the Control Panel, the keypad will return to stand-by mode within 15 seconds.

If there are 5 incorrect PIN Code attempts within 10 minutes, the wired/wireless keypad will be automatically locked up for 5 minutes. During this period, any operation will be invalid. When the lockup time expires, the wired/wireless keypad will emit 1 long beep.
{% endhint %}

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

### _**Fault Conditions**_

_When the wired/wireless keypad is under **NORMAL OPERATION MODE,**_

* If the Control Panel is in Away Armed mode, you CANNOT activate Home Armed Mode by the wired/wireless keypad. If you do so, the wired/wireless keypad will emit 2 beeps indicating the Control Panel is in Away Armed mode.
* When any fault situation is detected, the Yellow LED will flash once every 3 seconds. The Yellow LED behavior is decided by the Control Panel.
* If there are 5 incorrect PIN Code attempts within 10 minutes, the wired/wireless keypad will be automatically locked up for 5 minutes. During this period, any operation will be invalid. When the lockup time expires, the wired/wireless keypad will emit 1 long beep.

### _**Change of Batteries**_

1. Go to the Control Panel programming menu to bypass the KPT tamper alarm.
2. Dismount the wired/wireless keypad.
3. Take out the two used batteries and press the tamper switch for more than 3 seconds to fully discharge before inserting new batteries. Do not mix new and used batteries.
4. Screw back the wired/wireless keypad to the mounting surface with the mounting screws.
5. Put the Control Panel back to normal operation mode.

### _**Reset the Wired/Wireless Keypad to Factory Default**_

The wired/wireless keypad can be reset to clear all learnt-in data and return all settings to the default values by the steps below:

1. Please follow _**Change of Batteries**_ steps for factory default.
2. Within 10 seconds after inserting the batteries, enter “0000”. When the last digit of “0000” turns into “ \* ” on the LCD screen, press “#” to reset the wired/wireless keypad to the default values.
3. “Reset Default” will be displayed on the LCD screen along with 3 beeps indicating successful operation.
4. All learnt-in data will be cleared.
5. Entry/ Exit Beeps will be disabled.
6. Alarm Beep will be disabled.
7. Dual Key alarm function will be disabled

{% hint style="warning" %}
Note:

Factory default setting can only be performed within 10 seconds after inserting the batteries. If the keypad does not wake up within 10 seconds after inserting the batteries, remove the batteries and try again.

Whenever the keypad is removed from the Control Panel, it should be put to factory default as well to clear its Control Panel memory.
{% endhint %}

### _**Mounting the Wired/Wireless Keypad**_

To mount the wired/wireless keypad:

1. Remove the front cover by loosening the cover fixing screw using a screwdriver.
2. Use the 4 mounting holes on the back cover as a template to mark and drill mounting holes.
3. Drill 4 holes and insert the wall plugs. Ensure the wall plugs are flush with the mounting surface.
4. Screw the back cover onto the wall plugs.
5. Re-place the front cover onto the back cover. Screw the cover fixing screw.
6. The installation is now complete.
