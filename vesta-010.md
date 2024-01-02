# VESTA 010

* Remote Keypad KP-15-(NT)/ KP-15-(NT)-F1

Mar-24-2017

* The Remote Keypad includes following models:
* KP-15 / KP-15-F1: Remote Keypad with Tamper Switch
* KP-15-NT / KP-15-NT-F1: Remote Keypad without Tamper Switch
* _**Parts Identification**_

![](<.gitbook/assets/0 (4) (1).png>)

![](<.gitbook/assets/1 (6) (1).png>)

**1. Green Active LED**

**2. Red TX LED**

**3. Orange Fault LED**

**4. Slide Out Section**

![](<.gitbook/assets/2 (6) (1).png>)

**5. Arm Key**

**6. Home Key**

![](<.gitbook/assets/3 (6) (1).png>)

**7. Key**

**8. Disarm Key**

![](<.gitbook/assets/4 (6) (1).png>)

**9. ＃ Key**

**10. 🞸 Key**

**11. + Key**

\-press both 7 and 9 to trigger Medical alarm

**12. Fire Key**

\-press both 4 and 6 to trigger fire alarm

**13. A Key**

\-press both 1 and 3 to trigger panic alarm

**14. Mounting Hole**

**15. Tamper Swtich**

**16. Buzzer**

**17. Battery Insulator**

* _**LED Indicator:**_
* **Green Active LED:**
  *
    * Green Active LED on: the system is in **Normal Operation Mode**.
    * Green Active LED flash: the system is in **Test Mode**.
    * When the Keypad is idle, all LEDs are off. After any key press, the Green Active LED turns on for 5 seconds indicating that Keypad is active.
    * The Green Active LED will turn off after successful completion of a valid keystroke sequence or when the pause in between keystrokes is longer than 5 seconds.
    * When the Green Active LED turns off before a valid keystroke sequence is completed (5 seconds), the previous entered keys are ignored.
* **Red TX LED:**
  *
    * The Red TX LED flash: the signal is transmitted.
* **Orange Fault LED:**
  *
    * Orange Fault LED flash: Battery is low during operation.
    * Orange Fault LED on: Tamper is trigger during operation.
    * When Keypad Tamper is trigger and battery is low, the Orange Fault LED turns on during operation.

**\<NOTE>**

* A short beep will be sounded with each key press, which confirms valid pressing.
* 4 continuous beeps will sound indicating the user that he has entered invalid keystroke, and the user is asked to repeat the process again.
* _**Power:**_
* The Keypad uses a CR2450 3V 540mAH lithium battery as its power source.
* The Keypad can also detect the battery status. Low battery detection operates where the Keypad has enough reserve energy to typically operate for 4 month before complete exhaustion.
* When the Keypad has low battery, the Orange Fault LED will flash during operation and a low battery signal will be transmitted along with regular signal transmissions.
* Before shipment, the battery is pre-installed by the factory.
* _**Tamper Protection:**_
* Keypad is protected against any attempt to open the lid or to detach Keypad from its mounting surface.
* Tamper protection is disabled when in Test Mode.
* When Keypad Tamper is trigger, it will send KP Tamper Fault signal to Control Panel and the Orange Fault LED will turn on. In addition, during using the keypad, Orange Fault LED will stay on to indicate the KP Tamper Fault.
* _**Power Saving Feature:**_
* When the Keypad is not being used, no power is consumed. Whenever a key is pressed, the Keypad will activate and “**wake-up**” for 5 seconds when any key is pressed.
* After 5 seconds of key inactivity, the power turns off again and returns to Stand-by mode.
* Upon completion of a command input, the power turns off and returns to Stand-by mode.
* _**Test mode:**_
* Keypad can be put into Test mode by entering the PIN code (default: **0000**) followed by ＊. The Green Active LED will flash and Keypad sounds a long beep.
* To exit Test mode, press ![](<.gitbook/assets/5 (5) (1).png>) **twice**, Keypad will sound a long beep and the Green Active LED will turn on, then Keypad returns to Normal Operation mode.

**\<NOTE>**

* Test Mode is helpful to bypass Keypad Tamper alarm when installing, replacing low batteries or removing to different mount site.
* When Keypad is in Test mode, it operates as **wake-up** condition thus will NOT disconnect after 5 seconds.
* In Test Mode, if no key is pressed within 30 minutes, the Keypadl will automatically exit Test Mode to Normal Operation mode.

_The **Keypad Test mode** enables the following functions:_

*
  *
    *
      *
        * Transmit Keypad learn signal — press ＊ and then **1**
        * Dual-key Panic Alarm Enable — press ＊ and then **2**
        * Dual-key Fire Alarm Enable — press ＊ and then **3**
        * Dual-key Medical Alarm Enable — press ＊ and then **4**
        * Change the Pin Code — press ＊ and then **6**

Enter Old Pin Code and then press

Enter New 4-digit Pin Code and then press **#**

*
  *
    *
      *
        * Dual Key Disable — Press ＊ and then **5**
        * Quit Test Mode —press ![](<.gitbook/assets/6 (1) (1).png>) **twice**.
        * Arm/ Home without PIN Code — press ＊ and then **8**
        * Arm/ Home with PIN Code — press ＊ and then **9**

**\<NOTE>**

* For wrong entering or operating the Keypad will sound 4 short beeps.
* When the wrong Pin Code is entered for 4 times, the Keypad will sound 6 beeps and all LED 3 times. The Keypad will be locked for 1 min. After 1 minute, the Keypad will sound one beep and can be used again.
* _**Installation Procedures:**_

Step 1. Put the Control Panel into **Learning Mode**. Please refer to the Control Panel manual.

Step 2. Adding Keypad into the Control Panel:

**Test Mode Learning:**

1. Put remote keypad in Test mode by entering KP PIN code (default: **0000**), then press ＊ key. The Active Blue LED will turn on along with a long beep sound.
2. Press ＊ key then **1** key. Remote keypad will sound one beep.

\<NOTE>

* If the remote keypad did not sound one beep, it means the remote keypad did not send the learning code to the Control Panel, please press ＊ key then **1** key again under Test Mode to send the learning code..

1. Refer to the Control Panel manual to complete the learn-in process.

**Dual-Key Learning:**

1. Press both **#** and ＊ keys together under Normal Operation Mode. Remote Keypad will sound a long beep.

\<NOTE>

* If the remote keypad did not sound one beep, it means the remote keypad did not send the learning code to the Control Panel, please press both **#** and ＊ keys together under Normal Operation Mode to send the learning code.

1. Refer to the Control Panel manual to complete the learn-in process.

Step 3. After the Keypad is learnt-in, put the Control Panel into **Walk Test** mode. Hold the Keypad in the desired location, and send the learning code to the Control Panel to confirm this location is within the signal range of the Control Panel. To send the learning code, either press the ＊ key then **1** key under Test Mode or press both **#** and ＊ keys together under Normal Operation Mode.

Step 4. When you are satisfied that the Keypad works in the chosen location, you can proceed with mounting the Keypad following the steps described below (see _**Mounting Keypad**)_.

Step 5. Setting the Pin Code:

1. Press ＊ then **6**, a long beep will be sound.
2. Enter **0000** (default PIN code)
3. Press, Keypad sounds a long beep.
4. Enter your new 4-digit code.
5. Press **#**, Keypad sounds a long beep.

Step 6. Press ![](<.gitbook/assets/7 (2) (1).png>) **twice** to exit Test mode and the installation is completed.

* _**Mounting the Keypad:**_

To mount the Keypad:

1. Remove the 2 slide-out sections of front cover.
2. Using the 2 mounting holes as a template, mark off the positions in the most appropriate place.
3. Insert the wall plugs if fixing into plaster or brick surface.
4. Screw the Keypad onto the wall plugs.
5. Replace the 2 slide-out sections.

* _**System Mode Control**_

After finish learning the Keypad into alarm system Control Panel, the user may change the system using Keypad.

There are two ways to arm the system.

1. Away Arm / Home Arm the system by entering Control Panel User PIN Code.
2. Away Arm / Home Arm the system without entering Control Panel User PIN Code.

Disarming the system always requires entering Control Panel User PIN Code

**Arm/Home with Control Panel PIN Code**

Under Test mode, Pressing ＊ key and then **9** key to enable Arm/ Home with PIN Code function (**Default**).

**Arm/Home without Control Panel PIN Code**

In the Test mode, Pressing ＊ key and then **8** key to enable Arm/ Home without PIN Code function

1. Put the Control Panel to programming menu.
2. Dismount the Keypad by first removing the slide-out sections then the mounting screws.
3. Open the Keypad by loosening the 2 fixing screw located behind the Keypad
4. Take out the old battery and insert the new battery in the battery compartment, with unmarked (negative) side of battery facing down.
5. Close the case using the rear fixing screws.
6. Screw back the Keypad to the surface with mounting screws, and then re-insert the slide-outs.
7. Put the Control Panel to exit Programming Menu.

* _**Appendix:**_

If you have forgotten the Pin Code or anything wrong happened in the Keypad, you can reset the Keypad to factory default and reinitialize it.

_**Reset to factory default:**_

Step 1 Remove one of the batteries and release the tamper

Step 2 Press **3** while inserting the removed battery back in

Step 3 Continue pressing **3** until 3 short beeps to indicate successful reset

Step 4 Release **3**

**\<NOTE>**

* After reset, PIN code reverts to factory default values, “**0000**”. Keypad will need a new learn-in process to start functioning.
* Whenever the Keypad is removed from the Control Panel, it should be put to factory reset as well to clear its Control Panel memory.
