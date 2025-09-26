# VESTA-011

&#x20;**KP-39**

## **REMOTE KEYPAD** WIRELESS

<figure><img src=".gitbook/assets/image (8).png" alt=""><figcaption></figcaption></figure>

## _**Parts Identification**_

<figure><img src=".gitbook/assets/0 (35).png" alt=""><figcaption></figcaption></figure>

1. Arm Key
2. Home Key
3. Disarm Key
4. Panic Alarm (if enabled), press both 1 and 3 to trigger the Panic Alarm
5. Fire Alarm (if enabled), press both 4 and 6 to trigger Fire Alarm
6. Medical Alarm (if enabled), press both 7 and 9 to trigger Medical alarm
7. Send Learning Code
   * press ＊then 7 Key (under Test Mode)
   * press both # and  keys (under Normal Operation Mode)
8. \# Key
9. \* Key
10. Fault LED (Orange LED)
11. Power LED (Green LED)
12. Mounting Holes
13. Tamper Switch

{% hint style="warning" %}
Note:

A short beep will sound along with a key press to indicate that the button pressed is valid.

4 continuous beeps will sound, indicating a mistake, and the user should repeat the process again.
{% endhint %}



## _**LED Indicator**_

* **Power LED (Green):**
  * On for 5 seconds: after successful completion of a valid keystroke sequence.
  * Flash for 5 seconds: low battery in Normal Operation Mode.
  * If the Power LED turns off before a valid keystroke sequence is completed, the previous entered keys are ignored.
* **Fault LED (Orange):**
  * Disarm Key and Orange LED on along with 5 beeps: Alarm Memory (depends on Control Panel).
  * Flash:
* &#x20;           Flash only: No response is sent by the control panel within 10 seconds.
* &#x20;           Flash along with 2 beeps: Request for Home mode during Arm mode.
* &#x20;           Flash along with 3 beeps: Request for Home or Arm Mode when fault condition exists.
* &#x20;           Flash along with 4 beeps: PIN code was incorrect.

_**General Operation**_

* Enter Test mode — Enter Keypad PIN code and then press ＊ key.
* Panic Alarm — Press **1** key + **3** key at the same time. (if the function is enabled)
* Fire Alarm — Press **4** key + **6** key at the same time. (if the function is enabled)
* Medical Alarm — Press **7** key + **9** key at the same time. (if the function is enabled)
* Check Control Panel Status — Normal Mode Press **#** key.
* Enable/Disable Entry & Exit Sound —Press **1** key + **2** key at the same time for 2 seconds. (The Keypad will emit one long beep to indicate the function is enabled and emit 2 short beeps to indicate the function is disabled.)

## _**Power**_

* Remote keypad uses one CR123 3V Lithium battery as its power source.
* Remote keypad can also detect the battery status. If the battery voltage is low, the Power LED will flash for 5 seconds during operation. The Low battery signal will be sent along with regular signal transmissions to the Control Panel for displaying the status accordingly.
* Before shipment, the battery is pre-installed by the factory.
* When changing battery, press any key a couple times to discharge before inserting new battery.

## _**Power Saving Feature**_

* When idle, the Remote keypad is in **Stand-by** mode and uses no power. It will activate and **wake up** for 5 seconds when any key is pressed.
* After 5 seconds of key inactivity, the power goes off, and it returns t**o Stand-by** mode.

## _**Tamper Protection**_

* The keypad is protected against any attempt to open the lid or to detach the keypad from its mounting surface.
* Tamper protection is disabled when the keypad is in Test Mode.

## _**Supervision Signal**_

* After installation, the Remote Keypad will automatically transmit Supervision Signals to the Control Panel at an interval of 30-50 minutes.
* If the Control Panel has not received the signal from the Remote Keypad for a preset period of time, the Control Panel will consider the Remote Keypad out of order and react according to panel setting.

## _**Getting Started**_

Step 1. Put the Control panel into learning mode, .

Step 2. Adding remote keypad into the Control Panel:

### **Test Mode:**

1. Put the remote keypad in Test mode by entering the KP PIN code (default: **0000**), then press the **＊** key.

The three![](<.gitbook/assets/10 (21).png>)![](<.gitbook/assets/11 (10).jpeg>) LEDs will turn on, along with a long beep.

1. Press ＊ key then **7** key to transmit learning signal. The remote keypad will sound a long beep.

### **Test Mode Function:**

1. Press ＊ key and then 2 key — Enable Dual-key Panic Alarm function
2. Press ＊ key and then 3 key — Enable Dual-key Fire Alarm function
3. Press ＊ key and then 4 key — Enable Dual-key Medical Alarm function&#x20;
4. Press ＊ key and then 5 key — Disable all Dual Key function (Default)
5. Press ＊ key and then 6 key — Edit Keypad Pin Code

&#x20;                                                               Enter **Old** Keypad Pin Code and then press **＊** key

&#x20;                                                               Enter **New** a new 4-digit Keypad Pin Code and then press **#** ke&#x79;**.**

6\. Press ＊ key and then 8 key — .Enable Arm/ Home without PIN Code function.

_(Please refer to “**Arm/Home without Control Panel PIN Code**” for details, page 3)._

7\. Press ＊ key and then 9 key — Enable Arm/ Home with Control Panel User PIN Code function(Default).

(_Please refer to “**Arm/Home with Control Panel PIN Code**” for details, page 3_).

{% hint style="warning" %}
Note:

If the remote keypad does not sound a long beep, it means the remote keypad did not send the learning code to the Control Panel. Please press the ＊ key, then the **7** key again to send the learning code.

If the Control Panel receives the learning code, it will display the info accordingly. Refer to the operation manual of your Control Panel to complete the learn-in process.

After the Control Panel receives the signal from the remote keypad, it will send an acknowledgement back to the remote keypad. The remote keypad will then beep 3 times to confirm the acknowledgement has been received. If the remote keypad does not perform 3 beeps, please restart the learning procedure.
{% endhint %}

Step 3. After the Remote keypad is learnt-in, put the Control Panel into **Walk Test** mode, hold the Remote keypad in the desired location, and send the learning code to the Control Panel to confirm this location is within the signal range of the Control Panel. To send the learning code, either press the **＊** key then **7** key under Test Mode or press both the **#** and **＊** keys together under Normal Operation Mode.

Step 4. When you are satisfied that the Remote keypad works in the chosen location, you can proceed with mounting the Remote keypad following the steps described below (please refer to “_**Mounting Remote keypad**” for details)_.

Step 5. Press the Disarm key **twice** to leave Test mode, and the installation is completed. Remote keypad will sound a long beep, and three system mode LEDs will turn off. The Remote keypad returns to Normal Operation mode.

_\<NOTE>_

{% hint style="warning" %}
Note:

The Remote keypad will automatically exit Test mode after 5 minutes of inactivity and return to Stand-by mode. All the LEDs will turn off and the Keypad will emit one long beep.
{% endhint %}

## _**System Mode Control**_

After finish learning the Keypad into the alarm system Control Panel, the user may change the system using the Keypad.

There are two ways to arm the system.

1. Away Arm / Home Arm the system by entering the Control Panel User PIN Code.
2. Away Arm / Home Arm the system without entering the Control Panel User PIN Code. Disarming the system always requires entering the Control Panel User PIN Code.

### **Arm/Home/Disarm with Control Panel PIN Code:**

Under Test mode, press ＊ key and then **9** key to enable Arm/ Home with PIN Code function.

**Enter Arm Mode**: Enter any one of the Control Panel user codes and press ![](<.gitbook/assets/15 (4).jpeg>) key. If the panel has no fault and arming is successful, the ![](<.gitbook/assets/16 (3).jpeg>) LED will turn ON along with a long beep.

**Enter Home Mode**: Enter any one of the Control Panel user codes and ![](<.gitbook/assets/17 (5).jpeg>) key. If the panel has no fault and arming is successful, the ![](<.gitbook/assets/18 (3).jpeg>) LED will turn ON along with 3 beeps.

**Return to Disarm Mode**: Enter any one of the Control Panel user code and ![](<.gitbook/assets/19 (2) (1).jpeg>) key. If disarm is successful, the LED will turn ON along with 2 beeps.

If there is **Alarm Memory,** the  LED and fault LED will turn ON along with 5 beeps.

**Arm/Home/Disarm without Control Panel PIN Code:\*+**

In the Test mode, press ＊ key and then the **8** key to enable Arm/ Home without PIN Code function

**Enter Arm Mode**:  Press ![](<.gitbook/assets/15 (4).jpeg>) key. If the panel has no fault and arming is successful, the ![](<.gitbook/assets/16 (3).jpeg>) LED will turn ON along with a long beep.

**Enter Home Mode**: Press ![](<.gitbook/assets/17 (5).jpeg>) key. If the panel has no fault and arming is successful, the ![](<.gitbook/assets/18 (3).jpeg>) LED will turn ON along with 3 beeps.

**Return to Disarm Mode**: Enter any one of the Control Panel user code and ![](<.gitbook/assets/19 (2) (1).jpeg>) key. If disarm is successful, the LED will turn ON along with 2 beeps.

If there is **Alarm Memory,** the  LED and fault LED will turn ON along with 5 beeps.

## _**Entry/Exit Sound**_

* After the Entry/Exit Sound is enabled by pressing **1** key + **2** key at the same time for 2 seconds (indicated by one long beep), the keypad will sound beeps when the Entry/exit timer is activated.
* After the Entry/Exit Sound is disabled by pressing **1** key + **2** key at the same time for 2 seconds (indicated by two short beeps), the keypad will remain silent when the Entry/exit timer is activated.

## _**Fault Conditions**_

_When the Remote Keypad is in **NORMAL OPERATION MODE,**_

1. When a fault condition exists within the Control Panel, if the Keypad is used to arm the panel, the Fault LED will flash along with 3 beeps to indicate the fault condition.
2. When the Keypad disarms the panel, the  LED will turn ON along with two beeps indicating normal operation.
3. If you input the incorrect KP Pin code 4 times within 10 minutes under test mode, KP will disable the key function for 1 minute, and all the LEDs will flash 3 times along with 6 beeps. After 1 minute, it will emit a long beep to indicate that the key function is back to normal.
4. If you input the incorrect KP Pin code 4 times within 10 minutes when changing system mode, KP will disable the key function for 5 minutes. After 5 minutes, the keypad will emit a long beep to indicate that the key function is back to normal.

## _**Factory Reset**_

Resetting the Keypad to the factory default will restore the Keypad’s PIN Code to 0000 and clear all panel learning memory.

### _**Reset to factory default:**_

Step 1 Remove the batteries and release the tamper.

Step 2 If “**Arm/Home with Control Panel PIN Code**” method is selected, press & hold the **3** key while inserting the battery back.

.If “**Arm/Home without Control Panel PIN Code**” method is selected, press & hold the **4** key while inserting the battery back.

Step 3 Continue pressing the **3** key until KP emit 3 beeps to indicate a successful reset.

.Continue pressing the 4 key until KP emit 4 beeps to indicate a successful reset.

Step 4 Release **3** or 4 key, the reset process is complete.

* After reset, the PIN code reverts to factory default values, 0000. Remote keypad will need a new learn-in process to start functioning.
* Whenever the Keypad is removed from the Control Panel, it should be put to factory reset as well to clear its Control Panel memory.

## _**Mounting Remote Keypad**_

To mount the remote keypad:

1. Remove the front cover.
2. Using the 2 mounting holes of the back cover as a template, mark off the positions in the most appropriate place.
3. Insert the wall plugs if fixing into a plaster or brick surface.
4. Screw the remote keypad onto the wall plugs.
5. Replace the front cover.
