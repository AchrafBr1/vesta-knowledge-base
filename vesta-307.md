# VESTA 307

![](<.gitbook/assets/0 (113).jpeg>)**BLUETOOTH REMOTE KEYPAD with NFC Tag (KPT-32N-BLE)**

KPT-32N-BLE is a Remote Keypad with Bluetooth feature and NFC reader. It is designed to have quick access control of the System Control Panel via PIN Code, NFC label, or by approaching the keypad with the paired smartphone to disarm the system. The Keypad can send wireless signals to and receive wireless signals from the Control Panel.

The Remote Keypad can be mounted on a flat surface or wall with screws. It also has a tamper protection switch which will be activated upon any unauthorized attempt to open the lid or to detach keypad from mounting surface.

![](<.gitbook/assets/1 (82).png>)

* _**Identifying the Parts**_

1. **Siren**
2. **Orange LED: Home Arm Key** ![](<.gitbook/assets/2 (78).jpeg>)

**3. Red LED: Away Arm Key** ![](<.gitbook/assets/3 (77).jpeg>)

**4. Panic Alarm (if enabled)**

\- Press both 1 and 3 to trigger panic alarm

**7.**  **Key**

* Enter Keypad PIN Code (Default: **0000**) +  Key to enter Programming Mode.

1. **Keypad Sensor (for tag)**
2. **# Key**

| **5.**                                     | **Fire Alarm (if enabled)**    | **10. Tamper Switch** |   |
| ------------------------------------------ | ------------------------------ | --------------------- | - |
|                                            |                                |                       |   |
| - Press both 4 and 6 to trigger fire alarm | **11. Mounting Holes**         |                       |   |
|                                            |                                |                       |   |
| **6.**                                     | **Medical Alarm (if enabled)** | **12. NFC Tag**       |   |
|                                            |                                |                       |   |

\- Press both 7 and 9 to trigger Medical alarm

![](<.gitbook/assets/4 (93).png>)

_**\<NOTE>**_

*
  * A short beep will sound along with key pressing to indicate that the button pressed is valid.
  * Backlight will be ON for any key pressed or command sent from the Keypad.
* _**LED Indicator**_

![](<.gitbook/assets/5 (94).png>)

* **Red LED (Away Arm Key)**
  * **Red LED on:** the system is in **Programming Mode**.
  * **Red LED flashes and backlight on** in the **Away Arm Mode.**
  * **Red LED flashes with 4 beeps**: mode change fails due to the following reasons:
    * No response from the control panel.
    * Request for **Home mode** during **Arm mode**.
    * Request for **Force arm**.
* **Orange LED (Home Arm Key)**
  * **Orange LED flashes and backlight on** in the **Home Mode**.
  * **Orange LED flashes for 5 seconds:** low battery in Normal Operation Mode or Tamper open.

![](<.gitbook/assets/6 (72).png>)

1

*
  * **LED flash with 4 beeps:** mode change fails due to the following reasons:
    * No response from the control panel.
    * Request for **Home mode** during **Arm mode**.
    * Request for **Force arm**.
* **Both Red LED and Orange LED on:** the keypad is in **BLE Pairing Mode**.

![](<.gitbook/assets/7 (56).jpeg>) ![](<.gitbook/assets/8 (67).png>)

_**\<NOTE>**_

*
  * When Arm/Home, Red/Orange LED will turn off after successful completion of a valid keystroke sequence, or when the pause in between Control panel User code/PIN code keystrokes exceeds 2 seconds along with 4 beeps.
  * If Arm/Home button is pressed but no Control Panel User Code/PIN code is entered, in 5 seconds the keypad will enter sleep mode.
* _**Power**_

![](<.gitbook/assets/9 (37).jpeg>)

*
  * Remote keypad uses two **1.5V “AA” Alkaline batteries** as its power source.
  * Remote keypad can also detect the battery status. If the battery voltage is low, the Orange LED will flash for 5 seconds. The Low battery signal will be sent along with regular signal transmissions to the Control Panel for displaying the status accordingly.
  * When the battery is exhausted, the Remote keypad will stop all function, all LED will flash every 4 seconds.
* _**Power Saving Feature**_
  * When idle, Remote keypad is in **Stand-by** mode and uses no power. It will activate and **wake-up** when any key is pressed, keypad sensor detects an NFC tag, or keypad detects a paired smartphone.
  * Upon completion of a command input, or after 5 seconds of key inactivity, the remote keypad returns to **Stand-by** mode, the power goes off.
* _**Learning Keypad into Control Panel**_

![](<.gitbook/assets/10 (27).jpeg>) ![](<.gitbook/assets/11 (29).jpeg>)

Step 1. Put the Control Panel into **Learning Mode**. Please refer to the Control Panel manual.

Step 2. **Normal Mode**

Under Keypad Normal Mode, press and hold ＊ key and # key for 2 seconds to transmit learn code to Control Panel.

**Programming Mode**

Alternatively, you can enable Remote keypad to enter Programming Mode first. Enter Keypad PIN Code (Default: **0000**) and then press **＊** key. The **Red** LED will turn on and sound a long beep. Press ＊ key and then **7** key to transmit learn code to Control Panel.

Step 3. Refer to Control Panel manual to complete the learning process. If learning is successful, the Keypad will emit 3 beeps upon receiving acknowledgement signal from Control Panel. If the Keypad does not sound 3 beeps to indicate receiving the signal from the Control Panel, the Orange LED will flash. Please repeat Step 2 to transmit learn code again.

Step 4. After the Remote keypad is learnt-in, put the Control Panel into **Walk Test** mode, hold the Remote keypad in the desired location, and send the learning code to the Control Panel to confirm this location is within the signal range of the Control Panel.

![](<.gitbook/assets/12 (28).jpeg>)

* _**Edit Keypad Operation Area**_
  * Follow instructions below to change Keypad Area in the Control Panel
    1. Use the panel Edit Device function to change Keypad area setting.
    2. Put the Control Panel into **Learning Mode**.
    3. Press and hold ＊ key and **#** key of keypad for 2 seconds to transmit learn code to Control Panel.
    4. The keypad will be displayed under learned device. Area update is complete.
* _**Add Tag/Clear Tag Procedures**_

![](<.gitbook/assets/13 (34).jpeg>)

The Keypad is capable of transmitting NFC (Near Field Communication) tags to the Control Panel, and you can assign a PIN Code and user name to each NFC tag on the Panel webpage. The NFC tags can then be used to control alarm system mode through the Keypad. The number of NFC tags and PIN Codes are managed on the Control Panel webpage.

1. _**Add Tag:**_

When adding a new tag, the keypad must be in normal operation mode.

Step 1. Go to the PIN Code page on the Control Panel webpage, input a 4-digit or 6-digit user pin code and user name for the tag, assign the user pin code to an Area.

2

![](<.gitbook/assets/14 (40).png>)

Step 2. After KPT-32N-BLE is successfully learnt into the panel, apply a new tag to the Keypad Tag sensor zone. The white backlight will turn on with 4 beeps to indicate this tag is new (not added to the system yet).

Step 3. Click the Load button on the PIN Code page as below. The corresponding tag number will be loaded. Click Submit to save the user code setting.

![](<.gitbook/assets/15 (41).png>)

Step 4. The tag has been added. You can use the tag to arm/home arm/disarm the system. When Keypad is powered on by inserting batteries, the Orange LED will flash and the white backlight will turn on. When LED is off, wait 10 seconds for keypad tag sensor to start functioning.

1. _**Clear Tag:**_

Step 1. Go to the PIN Code page on the Control Panel webpage.

Step 2. Manually delete the tag number and click Submit.

![](<.gitbook/assets/16 (43).png>)

Step 3. The tag is cleared.

![](<.gitbook/assets/17 (21).jpeg>)

* _**Programming Mode**_
* Put the Remote keypad into Programming Mode by entering the Keypad PIN code (default: **0000**) followed by “**＊**” key along with a long beep sounding, the Red LED and backlight will turn on.

![](<.gitbook/assets/18 (37).png>)

_**\<NOTE>**_

*
  * If you enter incorrect 4-digit PIN Code, the Remote Keypad will emit 4 beeps.
  * If you enter incorrect 4-digit PIN Code 5 times in a row, all LEDs will flash for 6 times, the keypad will emit 6 long beeps. The keys will be locked for 1 minute. After 1 minute, 1 long beep sounds.
* To exit Programming Mode, press # key **twice** (long beep). Otherwise, the Remote keypad will automatically exit Programming Mode after 5 minutes and return to Stand-by mode.

_**Under Programming Mode, the following functions can be enabled:**_

* Press ＊ key and then **1** key — to enter the BLE Pairing mode. When entering the Pairing mode, the Keypad emits a long beep, the Red and Orange LED turn on.
* _Note:_ The BLE Pairing must be operated by both of the Keypad and the _**Vest Home 5 APP**_. Except pressing ＊ key and then **1** key under Programming Mode to enter the BLE Pairing Mode, the quick access to the BLE

Pairing mode is pressing ＊ key and **0** key at the same time for 2 seconds on the Keypad in the Tamper Open state.

* Press ＊ key and then **2** key — to enable Dual-key (1+3) Panic Alarm function
* Press ＊ key and then **3** key — to enable Dual-key (4+6) Fire Alarm function
* Press ＊ key and then **4** key — to enable Dual-key (7+9) Medical Alarm function
* Press ＊ key and then **5** key — to disable all Dual Key functions (long beep). (**Default**)
* Press ＊ key and then **6** key — to change the Keypad Programming Mode PIN Code
  1. Enter **Old** Keypad Pin Code and then press \* key along with a long beep. If incorrect PIN Code is entered, the Keypad will emit 4 beeps and exit PIN Code change function. (Pressing # key will also exit PIN Code change function)
  2. Enter **New** 4-digit Keypad PIN Code and then press **#** key. The Keypad will emit a long beep and will exit change Keypad PIN Code function automaticall&#x79;**.**

3

* Press ＊ key and then **7** key — to transmit Remote keypad learn signal with a long beep.

_Note 1:_ The Keypad will emit 3 beeps upon receiving acknowledgement signal from Control Panel. If within 30 seconds the keypad does not receive the signal from the Control Panel, the Orange LED will flash.

_Note 2:_ When not in the Programming Mode, you are able to pair the Remote Keypad and the Control Panel by pressing ＊ key and # key for 2 seconds in the normal mode.

* Press ＊ key and then **8** key — to enable Quick Arm/ Home without Control Panel User Code function with a long beep.
* Press ＊ (the code
* Press “#”

key and then **9** key — to enable Arm/ Home with Control Panel User Code function with a long beep checked by panel) (**Default**).

key **twice** — to exit Programming Mod&#x65;**.**

![](<.gitbook/assets/19 (10).jpeg>)

* _**Tamper Protection**_
  * The keypad is protected against any attempt to open the lid or to detach keypad from its mounting surface.
  * Tamper protection is disabled when the keypad is in Programming Mode.
* _**How to Set System Mode**_

![](<.gitbook/assets/20 (17).jpeg>)

You may choose to arm/home arm with or without a Control Panel User Code.

**Arm/Home without Control Panel User Code (Quick Arm)**

In the Programming Mode, Pressing ＊ key and then 8 key to enable Arm/ Home without Control Panel User Code function, then exit Programming Mode by pressing the # key twice.

* **Enter Arm Mode**: Press  key. If panel has no fault and arming is successful, the Red LED will turn ON with a short beep. When successful Arm, Red LED flashes, Backlight turns on with a long beep.
* **Enter Home Mode**: Presskey. If panel has no fault and arming is successful, the Orange LED will turn ON with a short beep. When successful Home Arm, Orange LED flashes, Backlight turns on with a long beep.
* **Return to Disarm Mode**: Enter Control Panel User Code or put Tag on the Keypad Sensor will emit a short beep. If disarm is successful, Backlight flashes along with 2 beeps. (Disarm always requires a Control Panel User Code or NFC Tag).

**Arm/Home with Control Panel User Code or NFC Tag**

In Programming Mode, Pressing ＊ key and then 9 key can enable Arm/ Home with User Code function, then exit Programming Mode by pressing the # key twice. **(Default)**

**This function must be enabled for NFC tag to be used.**

*

If disarm is successful, Backlight flashes along with 2 beeps.

* _**Dual-key Alarm function**_

The Dual Key function allows you to activate alarm from Keypad by pressing 2 keys at the same time. Press and hold both keys for 1 second to transmit signal, the Keypad will emit a long beep to confirm. The dual-key function is **disabled** by default. To enable it, please refer to the Programming Mode section.

*
  *
    * **Panic Alarm**: **1** key + **3** key.
    * **Fire Alarm**: **4** key + **6** key.
    * **Medical Alarm**: **7** key + **9**.
* _**Built-in Siren**_
  1. Exit Delay — The keypad continuously beeps. When entering Arm or Home Mode, the Keypad will emit long beep.

1. Entry Delay —The keypad continuously beeps. When entering Disarm Mode, the Keypad will emit 2 beeps.
   1. Alarm siren — Siren will sound continuously when alarm is triggered. Fire Alarm will sound 2 seconds and 1 second off.

* _**Check System Mode**_

When keypad is in standby mode (the tamper switch must be in close state), you can press **#** key to check current system mode of the panel.

4

*
  * If system is in Arm Mode, the Keypad Red LED turns on for 1 second and emits a long beep.
  * If system is in Home Mode, the Keypad Orange LED turns on for 1 second and emits a long beep.
  * If system is in Disarm Mode, the Keypad White Backlight turns on for 1 second and emits a long beep.
* _**Bluetooth Function to Disarm the System via Smartphone**_

To use the keypad’s Bluetooth feature to disarm the system via Smartphone, the Control Panel must be registered on Home Portal Server.

_**Vesta Home 5 APP**_ is used for Bluetooth pairing the smartphone with the keypad. Up to **25** smartphones can be paired with the keypad to disarm the system via Vesta Home 5 APP.

Please go to APP store or Google Play and search _**Vesta Home 5**_ to download the application.

* **Bluetooth Setup**

**Pairing the Keypad with one or multiple smartphones**

**Step 1.** In keypad **tamper open state**, put the keypad into the **BLE Pairing mode** by pressing and holding both **＊** key and **0** key together for **2 seconds**. When entering the BLE Pairing mode, the Keypad emits a long beep and Red and Orange LED will turn on during BLE Pairing mode.

**Step 2.** On your smartphone, open the _**Vesta Home 5 App**_, enter the registered user ID and password, and tap

Connect to log into your account. _Note:_ Make sure Bluetooth is turned on for your smartphone setting.

**Step 3.** Go to the All Devices page, select KPT-32N-BLE. Tap “**Start Bluetooth Pairing**.”

5

**Step 4.** The app will automatically start scanning the Keypad that is under BLE Pairing mode. If it does not start

scanning automatically, tap the  button on the screen to search for the Keypad.

When the detected Keypad is shown on the list, tap it to enter the Pairing PIN Code page. Enter the BLE Pairing PIN Code **(Default: 000000)** and tap **Pair** button to proceed.

_Note:_ To edit the Pairing PIN Code, enter 6-digit PIN Code and ＊ on the Keypad under the BLE Pairing mode. If the PIN Code setting is confirmed, the Keypad emits 1 long beep. If the PIN Code setting is not confirmed, the Keypad emits 4 beeps.

**Step 5.** When the dialog box of Pairing Successful is shown on the APP, Pairing is successful.

Click OK, and you will be directed to the KPT device setting page where you will need to set your PIN code.

6

**Step 6.** Select PIN Code, and input a 4-digit or 6-digit Control Panel User PIN.

If the user wants to leave this page but the User PIN field is empty, the system will pop up an error message.

_**Please Note:**_

* When the Keypad is under the BLE Pairing mode, users can pair the Keypad with one or multiple smartphones. Whether the first pairing smartphone is connected or not, the second and more smartphones can be paired with the Keypad by following the **Step 2\~6** in the instructions above.
* The Keypad can pair with a maximum of 25 smartphones.

**Step 7.** Leave the BLE Pairing Mode by pressing **#** key once. Otherwise, the Remote keypad will automatically exit BLE Pairing Mode after 5 minutes and return to Stand-by mode.

**Unpairing a Keypad with One or Multiple Smartphones**

**Step 1.** Under keypad **BLE Pairing mode**, you can unpair the Keypad with one or multiple smartphones.

In keypad **tamper open state**, put the keypad into the **BLE Pairing mode** by pressing and holding both **＊** key and **0** key together for **2 seconds**. The Keypad emits a long beep and Red and Orange LED turn on.

* Press **0, or 1, or 2, … 24** key and then **#** key — to unpair the 1st , 2nd, 3rd, ….or the 25th smartphone.
* Press **25** key and then **#** key — to unpair all smartphones.

**Step 2.** Besides unpairing the keypad with your smartphone, you will also need to remove the Bluetooth Function of the keypad in your Smartphone APP.

7

**Step 3.** Then, delete the paired Keypad from your smartphone. Navigate the Smartphone’s **Settings** > **Bluetooth** > **My Devices.** Tap the paired Keypad and select **Forget This Device** to remove it from the device list.

* **Disarming the System via Smartphone**

To disarm the system via a paired smartphone:

*
  * The smartphone’s Bluetooth function needs to be turned ON, and the Vesta Home 5 APP must be kept active in the background so that the device can communicate with the App.
  * A 4-digit or 6-digit Control Panel User Code must have been saved in the Vesta Home 5 APP.

When the system is armed, approach the keypad with the paired smartphone. Once the Keypad detects the paired smartphone within the BLE range, the system will automatically disarm.

_**Note:**_

*
  *
    * The effective BLE range may differ depending on different mobile devices.
    * After the system arms, a 30-second buffer is configured for the paired mobile to be out of the Keypad BLE range. The keypad will start detecting only after the system is armed for 30 seconds. If the paired mobile is within the BLE range when the system arms, the system will not Disarm until the 30-second buffer passes.
* _**Supervisory Signal**_
  * The Remote Keypad will automatically transmit Supervisory Signals periodically to the Control Panel at random intervals of 30-50 minutes.
* _**Mounting Remote Keypad**_

To mount the remote keypad:

1. Remove the front cover.
2. Using the 4 mounting holes of the back cover as a template, mark off the positions in the most appropriate place.
3. Insert the wall plugs if fixing into plaster or brick surface.

IV. Screw the Remote keypad onto the wall plugs.

*
  1. Replace the front cover.
* _**Change of Battery**_

1. Before changing battery, make sure the system is in disarm mode to avoid triggering keypad tamper alarm.
2. Loosen the bottom fixing screw to open the Keypad’s cover.
3. Take out the old battery and press any key to discharge before replacing the new battery in the battery compartment.

IV. Close the case using the bottom fixing screw.

*
  1. Put the Control Panel back to normal operation mode.
* _**Fault Conditions**_

_When Remote Keypad is under **NORMAL OPERATION MODE**_

*
  1. When fault event exists in Control Panel, the arming command from Keypad will be ignored by Control Panel. The Keypad Red and Orange LED will flash for 3 seconds along with 4 beeps to indicate error. You can override the fault event and force arm the Control Panel by performing the arm action again.
  2. If the **Control Panel** is under Arm Mode, you **CANNOT** activate Home mode with Remote keypad. The Keypad Red LED flashes + Orange LED flashes for 3 seconds along with 4 beeps to indicate transmission error.
  3. If sent Arm/Home/Disarm signal but have no response from the Control Panel, the Red LED flashes + Orange LED flashes for 3 seconds along with 4 beeps.
  4. When incorrect Keypad PIN code is entered to enter Programming mode, The Keypad will emit 4 beeps. If incorrect Keypad PIN codes are entered for 5 times in a row, all LEDs will flash for 6 times, the keypad will emit 6 long beeps. The keys will be locked for 1 minute. After 1 minute, 1 long beep sounds.
* _**Factory Reset**_

If you have forgotten the Keypad PIN Code or anything wrong happened in the Remote keypad, you can reset the Remote keypad to factory default and reinitialize it.

_**Reset to factory default:**_

Step 1 Remove the batteries and release the tamper.

Step 2 Press & hold **3** key while inserting the battery back.

Step 3 Continue pressing **3** until three short beeps to indicate successful reset.

Step 4 Release **3** key, the reset process is complete.

_**\<NOTE>**_

* After reset, Keypad PIN code reverts to factory default values, **0000** and clears all user code and tag data. Remote keypad will need a new learn-in process to start functioning.

8
