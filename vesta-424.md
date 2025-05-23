# VESTA 424

**KPT-41N-SFV**

## **TWO-WAY VOICE REMOTE KEYPAD with NFC Tag**

![](<.gitbook/assets/1 (111).png>)

## _**Identifying the Parts**_

1. **Siren**
2. **Speaker**
3. **Orange LED: Home Arm Key** ![](<.gitbook/assets/2 (90).jpeg>)
4. **Red LED 1: Away Arm Key** ![](<.gitbook/assets/3 (92).jpeg>)
5. **NFC Tag Sensor Zone**
6. **SOS button**
   * Press the SOS button to transmit Emergency Signal.
7. **Red LED 2**
8. **Green LED**
9. **Panic Alarm (if enabled)**
   * Press both 1 and 3 to trigger panic alarm
10. **Fire Alarm (if enabled)**
    * Press both 4 and 6 to trigger fire alarm
11. **Medical Alarm (if enabled)**
    * Press both 7 and 9 to trigger Medical alarm
12. **Service Call**
    * Press both 7 and 8 for Service Report
    * During the service call communicaiton, press and hold both 7 and 8 keys for 5 seconds to end the call. Then the Two-Way Voice Remote Keypad will emit one beep to indicate.
13. **\* Key**
    * In Stand-by mode, press \* Key to enter Test and Programming Mode.
    * Enter Keypad PIN Code + \* Key to adjust the volume (Low/Medium/High). The volume is Low by default.
14. **# Key**
    * In Stand-by mode, press **#** Key to check current system mode, the corresponding LED will light up.
15. **Battery Compartment**
16. **Tamper Switch**
17. **Mounting Holes**
18. **NFC Tag**

{% hint style="warning" %}
Note:

* A short beep will sound along with key pressing to indicate that the button pressed is valid.
* A long beep will sound along with key pressing to indicate successful command.
* 4 continuous beeps will sound indicating mistake and the user should repeat the process again.
* Backlight will be ON for any key pressed, or command sent from the Keypad. When the system is in Disarm Mode, the backlight will also light up by pressing the \* key.
{% endhint %}

* _**LED Indicator**_

 **Red LED (Away Arm Key)**

*
  *
    * **Red LED on:** the system is in **Test & Programming Mode**.
    * **Red LED on for 5 seconds:** to show the system is in the **Away Arm Mode** by pressing  key.
    * **Red LED flashes, and Backlight on**: the system is in the **Away Arm Mode.**
    * **Red LED flashes without beep:** request for **Force arm**.
    * **Red LED flash with 4 beeps**: failure due to the following reasons:
      * No response from the control panel.
      * Request for **Home mode** during **Arm mode**.

**Orange LED (Home Arm Key)**![](<.gitbook/assets/7 (69).jpeg>)

* **Orange LED:** Orange flashes and backlight on in the **Home Mode**.
* **Orange LED on for 5 seconds:** to show the system is in the **Home Mode** by pressing  key.
* **Orange LED flashes for 5 seconds:** low battery in Normal Operation Mode, and Tamper open.
* **Orange LED flashes without beep:** request for **Force arm**.
* **Orange LED flashes with 4 beeps:** failure due to the following reasons:
  * No response from the control panel.
  * Request for **Home mode** during **Arm mode**.

_\<NOTE>_

*
  * When Arm/Home, Red/Orange LED will turn off after successful completion of a valid keystroke sequence, or when the pause in between Control panel User code/PIN code keystrokes exceeds 2 seconds along with 4 beeps.
  * If Arm/Home button is pressed but no Control Panel User Code/PIN code is entered, in 5 seconds the keypad will enter sleep mode.
* _**Built-in Siren**_

1. Exit Delay — the Two-Way Voice Remote Keypad continuously beeps. If enter Arm mode or Home Mode, the Two-Way Voice Remote Keypad will emit long beep.
2. Entry Delay —The Two-Way Voice Remote Keypad continuously beeps. When entering Disarm Mode, the Two-Way Voice Remote Keypad will emit 2 beeps.
   *
     1. Alarm siren — Siren will sound continuously when an alarm is triggered. Alarm sound will increase progressively from 85dB to 105dB in 15 seconds. Fire Alarm will sound 2 seconds and 1 second off.

* _**Power**_
  * The Two-Way Voice Remote Keypad uses four CR123 3V Lithium batteries as its power source.
  * The Two-Way Voice Remote Keypad can also detect the battery status. If the battery voltage is low, the Orange LED will flash for 5 seconds. The Low battery signal will be sent along with regular signal transmissions to the Control Panel for displaying the status accordingly.
* When the battery is exhausted, the Two-Way Voice Remote Keypad will stop all function, all LED will flash every 4 seconds.
* _**Power Saving Feature**_
  * When idle, the Two-Way Voice Remote Keypad is in **Stand-by** mode and uses no power. It will activate and **wake-up** for 5 second when any key is pressed or keypad sensor is detected.
  * After 5 seconds of key inactivity, the power goes off and it returns t**o Stand-by** mode.
  * Upon completion of a command input, the power goes off and the Two-Way Voice Remote Keypad returns to **Stand-by** mode.

_\<NOTE>_

 You can also press and hold **＊**&#x61;nd **#** key for 2 seconds to send learning code when Idle.

* _**Supervisory Signal**_
  * The Two-Way Voice Remote Keypad will automatically transmit Supervisory Signals periodically to the Control Panel at random intervals of 30-50 minutes.
* _**Test and Programming Mode**_
  * The Two-Way Voice Remote Keypad can be put into this mode by entering the Keypad PIN code (default: **0000**) followed by “**＊**” key along with a long beep sounding, the Red LED and backlight will turn on.
  * To exit Test mode, press **#** key **twice** (long beep). Otherwise, the Two-Way Voice Remote Keypad will automatically exit Test mode after 5 minutes and return to Stand-by mode.

_**Under the Test and Programming Mode, the following functions can be enabled:**_

* Press **＊** key and then **2** key — to enable Dual-key Panic Alarm function.
* Press **＊** key and then **3** key — to enable Dual-key Fire Alarm function.
* Press **＊** key and then **4** key — to enable Dual-key Medical Alarm function
* Press **＊** key and then **5** key — to disable all Dual Key function (long beep). (**Default**)
* Press **＊** key and then **6** key — to change the Keypad PIN Code.
  1. Enter **Old** Keypad Pin Code and then press **\*** key along with a long beep. If incorrect PIN Code is entered, they Keypad will emit 4 beeps and exit PIN Code change function. (Pressing **#** key will also exit PIN Code change function)
  2. Enter **New** 4-digit Keypad PIN Code and then press **#** key. The Keypad will emit a long beep and will exit change Keypad PIN Code function automaticall&#x79;**.**
* Press **＊** key and then **7** key — to transmit the Two-Way Voice Remote Keypad learn signal with a long beep.
* Press **＊** key and then **8** key — to enable Arm/ Home without Control Panel User Code function with a long beep. (the code is checked by panel.)
* Press **＊** key and then **9** key — to enable Arm/ Home with Control Panel User Code function with a long beep. (the code is checked by panel.) (**Default**)
* Press **＊** key and then **0** key — to select sound setting mode of “**Beep**”, “**Voice prompt**” or “**Mute**”.

a. When the “Beep” function is enabled, a long beep will emit.

b. When the “Voice prompt” function is enabled, the voice prompt of Volume Low / Volume Medium / Volume High will be played.

c. When the “Mute” function is enabled, the Orange LED (Home Arm Key) will flash twice.



* Press **#** key **twice** — to exit Test Mod&#x65;**.**
* _**Audio Setting**_
  * Under Test Mode, user can press **＊** key and then **0** key to select sound setting mode of “**Beep**”, “**Voice prompt**” or “**Mute**”.
  * Under the normal operation mode, user can also adjust audio volume to low (default), medium or high by pressing **＊** key.
  * When “Voice prompt” function is enabled, the voice prompt will be played on the conditions below.

| **No.** | **Condition** | **Audio**              |   |   | **Indication**                    |   |
| ------- | ------------- | ---------------------- | - | - | --------------------------------- | - |
|         |               |                        |   |   |                                   |   |
|         |               |                        |   |   |                                   |   |
| 1       | Arm           | Voice Prompt           |   |   | System is Armed - Exit Now        |   |
|         |               | System is in Arm mode  |   |   |                                   |   |
|         |               |                        |   |   |                                   |   |
|         |               |                        |   |   |                                   |   |
| 2       | Home Mode     | Voice Prompt           |   |   | System is Armed - Exit Now        |   |
|         |               | System is in Home mode |   |   |                                   |   |
|         |               |                        |   |   |                                   |   |
|         |               |                        |   |   |                                   |   |
| 3       | Disarm        | Voice Prompt           |   |   | System is Disarmed - Welcome Home |   |
|         |               |                        |   |   |                                   |   |
|         |               |                        | 3 |   |                                   |   |

| 4      | System fault    | Voice Prompt | System Fault - Please check              |   |
| ------ | --------------- | ------------ | ---------------------------------------- | - |
|        |                 |              |                                          |   |
| 5      | Alarm in memory | Voice Prompt | Alarm in memory                          |   |
|        |                 |              |                                          |   |
| 6      | Adjusting audio | Voice Prompt | Volume Low / Volume Medium / Volume High |   |
| volume |                 |              |                                          |   |
|        |                 |              |                                          |   |

_\<NOTE>_

*
  *
    * The voice prompts will only be played once each time when activated.
    * Sound setting can be configured under **Panel setting** of the Control Panel. On the control panel, the prompt can be configured for mode change, entry, or exit respectively.
* _**Tamper Protection**_
  * The keypad is protected against any attempt to open the lid or to detach keypad from its mounting surface.
  * Tamper protection is disabled when the keypad is in Test and Programming Mode.
* _**Installation Procedures**_

Step 1 Put the Control Panel into **Learning Mode**. Please refer to the Control Panel manual.

Step 2 **Keypad Normal Mode**

Under Keypad Normal Mode, press and hold **＊** key and **#** key for 2 seconds to transmit learn code to Control Panel.

**Keypad Programming Mode**

Alternatively, you can enable Remote keypad to enter Test and Programming Mode first. Enter Keypad PIN Code (Default: **0000**) and then press **＊** key. The **Red** LED will turn on and sound a long beep. Press **＊** key and then **7** key to transmit learn code to Control Panel. Remote keypad will sound a long beep.

Step 3 During the learning process, the Green LED will light on to indicate. Refer to Control Panel manual to complete the learning process.

**\<Note>** When learnt into the Panel, the keypad will be recognized as 2 separate devices and will occupy 2 zones in the Panel. Add both devices into the Panel.

![](<.gitbook/assets/20 (46).png>)

Step 4 If learning is successful, the Keypad will emit 3 high-tone beeps upon receiving acknowledgement signal from Control Panel and meanwhile the Green LED will turn off.

If learning fails, the Two-Way Voice Remote Keypad will emit 5 low-tone beeps. Please restart learning procedure from Step 1.

Step 5 After the Two-Way Voice Remote Keypad is learnt-in, put the Control Panel into **Walk Test** mode. Hold the Two-Way Voice Remote Keypad in the desired location, and press **SOS** button to confirm this location is within the signal range of the Control Panel.

Step 6 When you are satisfied that the Two-Way Voice Remote Keypad works in the chosen location, you can proceed with mounting the Two-Way Voice Remote Keypad following the steps described below (see _**Mounting Remote Keypad**)_.

* _**Two-way Voice Communication**_

Refer to the Control Panel manual to program the telephone number to be called with the Two-Way Voice Remote Keypad is activated. During two-way communication channel, the Two-Way Voice Remote Keypad Green LED will turn on.

* **Alarm Activation**

Press the **SOS** Button to transmit an Emergency alarm signal to the Control Panel. The Control Panel will activate alarm and dial to programmed alarm call recipient and establish two-way communication between the Remote Keypad and call recipient.

* **Service Report (Non-Emergency Call)**

Press dual keys **7** and **8** simultaneously to transmit a service report signal to the Control Panel. The Control Panel will dial to programmed service call recipient (different from alarm call recipient) and establish two-way communication between the Remote Keypad and call recipient.

During the service call, pressing and holding both **7** and **8** keys for 5 seconds will end the call. The Two-Way Voice Remote Keypad will emit one beep to indicate.

_\<NOTE>_

* If the Control Panel encounters power failure during two-way communication period, the Remote Keypad will automatically be disconnected and emit one beep to notify the user. The Remote Keypad has a 3-minute communication time and cannot be extended.
* If the Two-Way Voice Remote Keypad fails to establish two-way communication, it will emit 1 low-tone beep.

4

* **Incoming Calls**

Users can program authorized callers via the Panel’s webpage. To do this, go to the “**GSM**” tab and access “**Two-Way Setting**” function, and enter the numerals from the authorized phone number. The Panel will only answer incoming calls that contain the programmed numerals.

To answer incoming calls:

*
  1. Program the caller’s phone number (up to 60 digits, including spaces and commas) in the “Two-way Setting” section of the Panel’s webpage.

For example, users can enter “**123456,654321**” in the Caller column, indicating that two sets of phone numbers are programmed. The Panel will answer calls containing these numerals, such as 0987**123456**, because it includes

“**123456**”.

*
  1. If the phone number of an incoming call contains the programmed numerals, the Panel will pick up the call and assign the Remote Keypad to handle the two-way communication for 3 minutes (non-extendable).
  2. The call will automatically end after 3 minutes or when the caller terminates it.
* _**Tag Learning/Clearing Procedures**_

The Keypad is capable of transmitting NFC (Near Field Communication) signals to the Control Panel, and you can assign a PIN Code and user name to each NFC label on the Panel webpage. The NFC labels can then be used to control alarm system mode through the Keypad. The number of NFC labels and PIN Codes are managed on the Control Panel webpage.

1. _**Add Label:**_

When adding a new label, the keypad must be in normal operation mode.

Step 1 Go to the PIN Code page on the Control Panel webpage, input a 4-digit or 6-digit user pin code and user name for the tag, and assign the user pin code to an Area.

Step 2 After Keypad is successfully learnt into the panel, apply a new label to the Keypad Tag sensor zone. The Keypad will emit 4 beeps to indicate this label is new (not added to the system yet).

Step 3 Click the Load button on the PIN Code page as below. The corresponding label number will be loaded. Click Submit to save the user code setting.

Step 4 The label has been added. You can use the label to arm/home arm/disarm the system.

1. _**Clear label:**_

Step 1 Go to the PIN Code page on the Control Panel webpage.

Step 2 Manually delete the label number and click Submit.

Step 3 The label is cleared.

* _**Mounting the Two-Way Voice Remote Keypad**_

To mount the Remote Keypad:

1. Undo the two bottom fixing screws and detach the back case. 5
2. Using the 4 mounting holes of the back base as a template, mark off the positions in the most appropriate place.
   1. Replace the Remote Keypad and tighten the two bottom fixing screws.

* _**How to Set System Mode**_

You may choose to arm/home arm with or without a Control Panel User Code

**Arm/Home without Control Panel User Code**

In the Test mode, pressing **＊** key and then **8** key to enable Arm/ Home without Control Panel User Code function, then exit Test mode by pressing the **#** key twice.

* **Enter Arm Mode**: Press  key. If panel has no fault and arming is successful, the Red LED will turn ON with a short beep. When successful Arm, Red LED flashes, Backlight turns on with a long beep.

 **Enter Home Mode**: Press key. If panel has no fault and arming is successful, the Orange LED will turn ON with a short beep. When successful Home Arm, Orange LED flashes, Backlight turns on with a long beep.

* **Return to Disarm Mode**: Enter Control Panel User Code or put Tag on the Keypad Sensor will emit a short beep.

If disarm is successful, Backlight flashes along with 2 beeps.

**Arm/Home with Control Panel User Code or NFC Tag**

In the Test mode, Pressing **＊** key and then **9** key can enable Arm/ Home with User Code function, then exit Test mode by pressing the **#** key twice. **(Default)**

**This function must be enabled for NFC tag to be used.**

*

If disarm is successful, Backlight flashes along with 2 beeps.

* _**Dual-key Alarm function**_

The Dual Key function allows you to activate alarm from Keypad by pressing 2 keys at the same time. Press and hold both keys for 1 second to transmit signal, the Keypad will emit a long beep to confirm. The dual-key function is **disabled** by default. To enable it, please refer to the Test Mode section.

*
  *
    * **Panic Alarm**: **1** key + **3** key.
    * **Fire Alarm**: **4** key + **6** key.
    * **Medical Alarm**: **7** key + **9**.
* _**Change of Battery**_
  1. Put the Control Panel to programming menu to bypass the Keypad tamper alarm.

1. Dismount the Two-Way Voice Remote Keypad.
2. Undo the two bottom fixing screws and detach the back case.

IV. Take out the old batteries and press any key to fully discharge the residual power before inserting new batteries in the battery compartment.

*
  1. Insert new batteries, attach the back case to the Keypad and tighten the bottom fixing screws.

VI. Screw back the Two-Way Voice Remote Keypad to the surface with mounting screws.

VII. Put the Control Panel back to normal operation mode.

* _**Fault Conditions**_

When the Two-Way Voice Remote Keypad is under **NORMAL OPERATION MODE,**

1. When fault event exists in Control Panel, the arming command from Keypad will be ignored by Control Panel. The Keypad Red and Orange LED will flash without beep to indicate error. You can override the fault event and force arm the Control Panel by performing the arm action again.
2. If the **Control Panel** is under Arm Mode, you **CANNOT** activate Home mode with the Two-Way Voice Remote Keypad. The Keypad Red LED flashes + Orange LED flashes for 3 seconds along with 4 beeps to indicate transmission error.
3. If sent Arm/Home/Disarm signal but have no response from the Control Panel, the Red LED flashes + Orange LED flashes for 3 seconds along with 4 beeps.
4. When incorrect Keypad PIN code is entered to enter Test mode, the Keypad will emit 4 beeps. If incorrect Keypad

6

PIN codes are entered for 4 times, the Keypad will disable key input function for 1 minute and indicate error by flashing all LEDs for 6 times and emitting 6 beeps. All key press during the next 1-minute period will be ignored.

After 1 minute, the Keypad will return to normal operation and emit a long beep to indicate.

* _**Factory Reset**_

If you have forgotten the Keypad PIN Code or anything wrong happened in the Two-Way Voice Remote Keypad, you can reset the Two-Way Voice Remote Keypad to factory default and reinitialize it.

Step 1 Remove the batteries and release the tamper.

Step 2 Press & hold **3** key while inserting the batteries back.

Step 3 Continue pressing **3** until three short beeps to indicate successful reset.

Step 4 Release **3** key, the reset process is complete.

_\<NOTE>_

* After reset, Keypad PIN code reverts to factory default value, **0000** and clears all user code and tag data. The Two-Way Voice Remote Keypad will need a new learn-in process to start functioning.

