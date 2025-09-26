# VESTA-153

**KPT-23N, KPT-23N-F1**

## **REMOTE KEYPAD with NFC Label**

## _**Identifying the Parts**_

![](<.gitbook/assets/0 (64).jpeg>)



1. **Active LED**
2. **Status LED**
3. **Fault Display LED**
4. <img src=".gitbook/assets/image (134).png" alt="" data-size="line"> **Arm Key**
5. <img src=".gitbook/assets/image (135).png" alt="" data-size="line"> **Home Key**
6.  &#x20; <img src=".gitbook/assets/image (138).png" alt="" data-size="line"> **Key**

    Check Control Panel Status
7.  <img src=".gitbook/assets/image (139).png" alt="" data-size="line"> **Disarm Key**

    to move back one step
8. &#x20;<img src=".gitbook/assets/image (140).png" alt="" data-size="line">**Key**
9. &#x20;<img src=".gitbook/assets/image (141).png" alt="" data-size="line">**key**&#x20;
10. &#x20;**Send learning code**

    Press both # and \* keys together to Send Learning Code
11. **Medical Alarm (if enabled)**

    Press both 7 and 9 to trigger Medical alarm
12. **Fire Alarm (if enabled)**

    Press both 4 and 6 to trigger fire alarm
13. **Panic Alarm (if enabled)**

    Press both 1 and 3 to trigger panic alarm
14. **Battery Insulator**
15. **Mounting Holes**
16. &#x20;**Tamper Swtich**

{% hint style="info" %}
* A short beep will sound along with key pressing to indicate that the button pressed is valid.
* 4 continuous beeps will sound indicating mistake and the user should repeat the process again.
{% endhint %}

### _**LED Indicator**_

#### _**Active LED (Blue/Amber)**_**:**

* Blue LED on 5 seconds: the system is in **Normal Operation Mode.**
* Blue LED flashes for 5 seconds: **low battery in Normal Operation Mode**.
* Amber LED on: the system is in **Test Mode**.
* Amber LED flash: **low battery in Test Mode**.

{% hint style="info" %}
- The keypad will enter sleep mode when idle and turn off all LEDs. After any key press, the Active Blue LED will turn on on for 5 seconds indicating that Remote keypad is active.
- Active Blue LED will turn off after successful completion of a valid keystroke sequence, or when the pause in between keystrokes exceeds 5 seconds.
- When Active Blue LED turns off before a valid key sequence is completed, the previous entered keys are ignored.
{% endhint %}

#### _**Status LED (Blue/Red):**_

* Red LED on: the system is in **Away Mode**
* Red LED flash: the system is in **Home Mode**.
* Blue LED on: activation of **Disarm Mode**.
* Blue LED flash: failure due to the following reasons:
  * No response sent by the control panel within 4 seconds.
  * PIN code was incorrect.
  * Request for **Home** mode during **Arm** mode.
  * Request for **Force arm**.

#### _**Fault LED (Amber)**_**:**

* Flash: system failure (panel tamper, AC fault, sensor temper, sensor out of order, open door)

### _**Power**_

* Remote keypad uses one 3V, CR2 Lithium battery as its power source.
* Remote keypad can also detect the battery status. If the battery voltage is low, the Active LED will flash (**Amber** in **Test mode** or **Blue** in **Normal mode**) during operation. The Low battery signal will be sent along with regular signal transmissions to the Control Panel for displaying the status accordingly.
* Before shipment, the battery is pre-installed by the factory.

### _**Power Saving Feature**_

* When idle, Remote keypad is in **Stand-by** mode and uses no power. It will activate and **wake-up** for 5 seconds when any key is pressed.
* After 5 seconds of key inactivity, the power goes off and it returns t**o Stand-by** mode.
* Upon completion of a command input, the power goes off and Remote keypad returns to **Stand-by** mode.

### _**Test Mode**_

* Remote keypad can be put into Test mode by entering the PIN code (default: **0000**) followed by ＊ key. The Active **Amber** LED goes on along with a long beep sounding.
* To exit Test mode, press <img src=".gitbook/assets/image (142).png" alt="" data-size="line"> key **twice**, Remote keypad will sound a long beep and the Active LED will turn from **Amber** to Blue, it returns to **Stand-by** mode. Otherwise, Remote keypad will automatically exit Test mode after 5 minutes and return to **Stand-by mode.**

{% hint style="info" %}
- The Test Mode is helpful to bypass Remote keypad Tamper alarm when installing, replacing low batteries or removing to different mount site.
- When Remote keypad is in Test mode, it operates as **wake-up** condition thus will NOT disconnect after 5 seconds.
{% endhint %}

#### _**Under the Test mode, the following functions can be enabled:**_

* Press ＊ key and then **1** key — to enter the NFC Learning mode. KPT-23N will emit one long beep and its LED 2’s red light will go on to indicate. (To exit the NFC Learning mode, press <img src=".gitbook/assets/image (143).png" alt="" data-size="line"> to return to the Test mode.)
* Press ＊ key and then **7** key — to transmit Remote keypad learn signal. (If KPT-23N will emit 3 beeps to indicate that it is learnt into the Panel.)
* Press ＊key and then **2** key — to enable Dual-key Panic Alarm function
* Press ＊ key and then **3** key — to enable Dual-key Fire Alarm function
* Press ＊ key and then **4** key — to enable Dual-key Medical Alarm function
* Press ＊ key and then **6** key — to change the Pin Code
  * Enter **Old** Pin Code and then press <img src=".gitbook/assets/image (144).png" alt="" data-size="line">key
  * Enter **New** 4-digit Pin Code and then press **#** key
* Press ＊ key and then **5** key — to disable all Dual Key function. (Default)
* Press <img src=".gitbook/assets/image (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1).png" alt="" data-size="line"> key **twice** — to leave the Test Mod&#x65;**.**
* Press ＊ key and then **8** key — to enable Arm/ Home without PIN Code function
* Press ＊ key and then **9** key — to enable Arm/ Home with PIN Code function(Code checked by panel) (Default)

### _**Tamper Protection**_

* The keypad is protected against any attempt to open the lid or to detach keypad from its mounting surface.
* Tamper protection is disabled when the keypad is in Test Mode.

### _**NFC Label Learning/Clearing/ Installation Procedures**_

NFC stands for Near Field Communication, which is a wireless communication technology that establishes connection between two devices by putting them close together. You can store a User PIN Code in a NFC label and use the NFC label to access the alarm system without entering a User PIN Code on KPT-23N.&#x20;

30 NFC labels are allowed to be learned into one KPT-23N

#### _**A) NFC Learning Procedure**_

1. Enable Remote keypad to enter a test mode first. Enter the PIN code (default: **0000**) followed by ＊ key. The Active **Orange** LED goes on along with a long beep sounding.
2. Press ＊ key and then **1** key to enter to the NFC Learning mode.
3. Enter an User PIN code followed by # key.
   1. If a new User PIN code is entered, the Status LED will flash Red and the Keypad will emit one long beep. The Keypad is now ready to learn a NFC label.
   2. If an existent User PIN code is entered, the Status LED will flash Red and the Keypad will emit one short beep. The Keypad is now ready to learn a NFC label.
   3. If a 31st User PIN code is entered (only 30 User PIN codes are allowed), the Status LED will flash Red and the Remote Keypad will emit 4 short beeps.
4. &#x20;Put a NFC label close to KPT-23N within 5 seconds (the NFC learning period).
   1. If the NFC Label is a new label, the Status LED will turn on Red and the Keypad will emit two short beeps upon successful learning.
   2. If the NFC Label is an existent label, the Status LED will turn on Red and the Keypad will emit 4 short beeps to indicate the error condition.
   3. If attempting to learn a 31st NFC Label (only 30 NFC Labels are allowed), the Status LED will flash Red and the Remote Keypad will emit 4 short beeps.

{% hint style="info" %}
If a new NFC label learns an existent User PIN code, the new NFC label will replace the old NFC label (that learnt the existent User PIN code previously).
{% endhint %}

If the NFC learning period times out (exceeds 5 seconds), the Status LED will turn on Red briefly. Re-enter the same User PIN code if you wish to learn more NFC labels using the same PIN code.

5. &#x20;To learn in another NFC label, please repeat steps 3-4
6. Press <img src=".gitbook/assets/image (8) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1).png" alt="" data-size="line">key to exit the NFC learning procedure.

{% hint style="info" %}
If the User Pin Code which you entered exceeds the pin code length (4 digits allowed), the Status Blue LED will flash along with 4 short beeps to indicate the error condition
{% endhint %}

#### _**B) NFC Clearing Procedure**_

You can clear NFC information through the following steps.

1. &#x20;Enable Remote keypad to enter a test mode first. Enter the PIN code (default: **0000**) followed by ＊ key. The Active **Orange** LED goes on along with a long beep sounding.
2. &#x20;Press ＊ key and then **1** key to enter to the NFC label Learning mode. Enter the User

Pin corresponding to the User Pin Code of the NFC label that you wish to clear and then press to clear the existing NFC label information. If clearing succeeds, KPT-23N will emit a long beep. If it fails, KPT-23N will emit 3 short beeps with Status Blue LED flash to indicate.

#### _**C)  NFC Installation Procedure**_



<figure><img src=".gitbook/assets/1 (108).png" alt="" width="116"><figcaption></figcaption></figure>

You can apply NFC label to the back of your cell phone for easy access.

1. &#x20;Learn in the NFC label to Remote Keypad
2. Remove the protective cover on the NFC label.
3. Apply the NFC label to the back cover of your cell phone horizontally.
4. &#x20;You can now use the NFC label to access the system.



{% hint style="info" %}
* Take care not to bend the NFC label, or it could be damaged and become unusable.
* The NFC label needs to be applied horizontally or the Remote Keypad may have difficulty reading the label.
* KPT-23N supports only ISO 14443A protocol for NFC label.
{% endhint %}

### _**Installation Procedures**_

**Step 1.** Put the Control Panel into **Learning Mode**. Please refer to the Control Panel manual.

**Step 2.** Adding remote keypad into the Control Panel:

**Test Mode Learning:**

1. Put remote keypad in Test mode by entering KP PIN code (default: **0000**), then press ＊ key. The Active Blue LED will turn on along with a long beep sound.
2. Press ＊ key then **7** key. Remote keypad will sound a long beep.

{% hint style="info" %}
If the remote keypad did not sound a long beep, it means the remote keypad did not send the learning code to the Control Panel, please press ＊ key then 7 key again under Test Mode to send the learning code..
{% endhint %}

3. Refer to the operation manual of your Control Panel to complete the learn-in process.
4. After Control Panel receives the signal from remote keypad, it will send an acknowledgement back to remote keypad. The remote keypad will then beep 3 times to confirm the acknowledgement has been received.

**Dual-Key Learning:**

1. Press both **#** and ＊ keys together under Normal Operation Mode. Remote Keypad will sound a long beep.

{% hint style="info" %}
If the remote keypad did not sound a long beep, it means the remote keypad did not send the learning code to the Control Panel, please press both **#** and ＊ keys together under Normal Operation Mode to send the learning code
{% endhint %}

2. Refer to the operation manual of your Control Panel to complete the learn-in process.
3. After Control Panel receives the signal from remote keypad, it will send an acknowledgement back to remote keypad. The remote keypad will then beep 3 times to confirm the acknowledgement has been received.

_**\<IMPORTANT NOTE>**_

{% hint style="info" %}
If remote keypad does not perform 3 beeps, please restart the learning procedure from Step 1.
{% endhint %}

**Step 3.** After the Remote keypad is learnt-in, put the Control Panel into **Walk Test** mode, hold the Remote keypad in the desired location, and send the learning code to the Control Panel to confirm this location is within the signal range of the Control Panel. To send the learning code, either press the ＊ key then **7** key under Test Mode or press both **#** and **＊** keys together under Normal Operation Mode.

**Step 4.** When you are satisfied that the Remote keypad works in the chosen location, you can proceed with mounting the Remote keypad following the steps described below (see _**Mounting Remote keypad**)_.

**Step 5.** Setting the KP Pin Code:

1. When the keypad is under Test mode, press ＊ key then **6** key, a long beep will be sound.
2. Enter **0000** (default PIN code)
3. Press <img src=".gitbook/assets/image (6) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1).png" alt="" data-size="line">key, remote keypad sounds a long beep.
4. &#x20;Enter your new 4-digit code.
5. Press **#** key, remote keypad sounds a long beep. The new PIN code is enabled.

**Step 6.** Press <img src=".gitbook/assets/image (7) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1).png" alt="" data-size="line"> key **twice** to leave Test mode and the installation is completed.

### _**Mounting Remote Keypad**_

To mount the remote keypad:

1. Remove the front cover.
2. Using the 2 mounting holes of the back cover as a template, mark off the positions in the most appropriate place.
3. Insert the wall plugs if fixing into plaster or brick surface.
4. Screw the Remote keypad onto the wall plugs.
5. Replace the front cover.

### _**How to Set System Mode**_

You may choose to arm/home arm with a Pin Code, with NFC label, or without a Pin Code :

#### **Arm/Home with Pin Code**

In the Test mode, Pressing ＊ key and then **9** key can enable Arm/ Home with PIN Code function (**Default**)

* _**Enter Arm Mode**_: Enter any one of Control Panel user code and press <img src=".gitbook/assets/image (3) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1).png" alt="" data-size="line">key. If panel has no fault and arming is successful, the Status Red LED will turn ON alone with a long beep.
* _**Enter Home Mode:**_ Enter any one of Control Panel user cods and <img src=".gitbook/assets/image (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1).png" alt="" data-size="line"> key. If panel has no fault and arming is successful, the Status Red LED will flash 4 times alone with 3 beeps.
* _**Return to Disarm Mode:**_ Enter any one of Control Panel user code and <img src=".gitbook/assets/image (2) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1).png" alt="" data-size="line"> key. If disarm is successful, the Status Blue LED will turn ON along with 2 beeps.

#### **Arm/Home with NFC Label**

* _**Enter Arm Mode:**_ press <img src=".gitbook/assets/image (3) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1).png" alt="" data-size="line"> key and put NFC label close to KPT-23N active the PIN code access. If panel has no fault and arming is successful, the Status Red LED will turn ON alone with a long beep.&#x20;
* _**Enter Home Mode:**_ press <img src=".gitbook/assets/image (4) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1).png" alt="" data-size="line">key and put/ NFC label close to KPT-23N active the PIN code access. If panel has no fault and arming is successful, the Status Red LED will flash 4 times alone with 3 beeps.&#x20;
* &#x20;_**Return to Disarm Mode:**_ <img src=".gitbook/assets/image (5) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1).png" alt="" data-size="line">key and put NFC label close to KPT-23N to active the PIN code access. If disarm is successful, the Status Blue LED will turn ON along with 2 beeps.

{% hint style="info" %}
NFC label has to be learnt into KP first.
{% endhint %}

#### **Arm/Home without PIN Code**

In the Test mode, Pressing ＊ key and then **8** key can enable Arm/ Home without PIN Code function

* _**Enter Arm Mode:**_ Press <img src=".gitbook/assets/image (13) (1) (1) (1) (1) (1) (1) (1).png" alt="" data-size="line"> key. If panel has no fault and arming is successful, the Status Red LED will turn ON alone with one long beep.&#x20;
* _**Enter Home Mode:**_ Press <img src=".gitbook/assets/image (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1).png" alt="" data-size="line"> key. If panel has no fault and arming is successful, the Status Red LED will flash 4 times alone with 3 beeps.
* _**Return to Disarm Mode:**_ Enter any one of Control Panel user code and <img src=".gitbook/assets/image (2) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1).png" alt="" data-size="line"> Key. If disarm is successful, the Status Blue LED will turn ON along with 2 beeps.

{% hint style="info" %}
When the **Arm/Home without PIN Code** function is enabled, the NFC label function will be **DISABLED**.
{% endhint %}

### _**Dual-key Alarm function**_

* Panic Alarm — Press both **1** key + **3** key to trigger Panic alarm.
* Fire Alarm — Press both **4** key + **6** key to trigger Fire alarm.
* Medical Alarm — Press both **7** key + **9** key to trigger Medical alarm.

{% hint style="info" %}
The dual-key function is disabled by default. To enable it, please refer to the **Test Mode** section
{% endhint %}

### _**General Operation**_

* Enter Test mode — Enter **Keypad PIN code** and then press ＊ key.
* Panic Alarm — Press **1** key + **3** key at the same time. (if the function is enabled)
* Fire Alarm — Press **4** key + **6** key at the same time. (if the function is enabled)
* Medical Alarm — Press **7** key + **9** key at the same time. (if the function is enabled)
* Check Control Panel Status — Normal Mode Press <img src=".gitbook/assets/image (145).png" alt="" data-size="line">key.
  * Red LED on: the system is in **Away Mode**
  * Red LED flash: the system is in **Home Mode**.
  * Blue LED on: activation of **Disarm Mode**.
  * Blue flash: failure due to the following reasons:
    * No response sent by the control panel within 4 seconds.
    * PIN code was incorrect.
    * Request for **Home** mode during **Arm** mode.
    * Request for **Force arm**.

### _**Change of Battery**_

1. Put the Control Panel to programming menu to bypass the KP tamper alarm.
2. Dismount the Remote keypad.
3. Take out the old battery and press any key to discharge before replacing the new battery in the battery compartment, with unmarked (negative) side of battery facing down.
4. Close the case using the rear fixing screws.
5. Screw back the Remote keypad to the surface with mounting screws.
6. &#x20;Put the Control Panel back to normal operation mode.

### _**Fault Conditions**_

_When Remote Keypad is under **NORMAL OPERATION MODE,**_

1. When fault condition exists within Control Panel, if the Keypad is used to arm the panel, the keypad Status Blue and Fault Amber LED will flash 4 times along with 3 beeps to indicate fault condition. User can force arm the Control Panel by performing the arm action again.
2. When the Keypad is used to disarm the panel, the Active Blue LED will turn ON alone with two short beeps indicating normal operation. At a fault situation, it will emit 5 times and turn on both Status Blue and Fault Amber LED for 5 seconds.
3. If the **Control Panel** is under Arm Mode, you **CANNOT** activate Home mode with Remote keypad. The Status Blue LED will flash 4 times to indicate transmission error.
4. If you input incorrect KP Pin code for 4 times, KP will disable the key function for 1 minute, indicating by all LEDs flashing 3 times and 6 beeps. After 1 minute, KP will emit a long beep to indicate that the key function is back to normal.

### _**Appendix**_

If you have forgotten the Pin Code or anything wrong happened in the Remote keypad, you can reset the Remote keypad to factory default and reinitialize it.

_**Reset to factory default:**_

Step 1 --> Remove the batteries and release the tamper.

Step 2 --> Press & hold **3** key while inserting the battery back.

Step 3 -->  Continue pressing **3** until three short beeps to indicate successful reset.

Step 4 --> Release **3** key, the reset process is complete.

{% hint style="info" %}
* Resetting the Keypad to factory default will restore Keypad’s own PIN Code to 0000. After reset, the Keypad will need a new learn-in process to start functioning.
* Whenever the Keypad is removed from the Control Panel, it should be put to factory reset as well to clear its Control Panel memory.
{% endhint %}

