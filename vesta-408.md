---
hidden: true
---

# VESTA 408

## Parts Identification

1. Arm Key
2. Home Key
3. Disarm Key
4. Panic Alarm (if enabled)
   * Press both 1 and 3 to trigger Panic Alarm
5. Fire Alarm (if enabled)
   * Press both 4 and 6 to trigger Fire Alarm
6. Medical Alarm (if enabled)
   * Press both 7 and 9 to trigger Medical Alarm
7. Sending learning code
   * Press  and the key 7 (under Test Mode)
   * Press both # and  (under normal operation mode)
8. ## Key
9.  Key
10. Fault LED (Orange)
11. Power LED (Green)
12. Tamper Switch
13. Battery Insulator
14. Mounting Holes

{% hint style="info" %}
* A short beep will sound along with key pressing to indicate that the button pressed is valid.
* 4 continuous beeps will sound indicating mistake and the user should repeat the process again.
{% endhint %}

## LED Indicator

* **Power LED (Green):**
  * On for 5 seconds: after successful completion of a valid keystroke sequence.
  * Flash for 5 seconds: low battery in Normal Operation Mode.
  * If the Power LED turns off before a valid keystroke sequence is completed, the previous entered keys are ignored.
* **Fault LED (Orange):**
  * Disarm Key and Orange LED On along with 5 beeps: Alarm Memory (depend on Control Panel).
  * Flash:
    * Flash only: No response sent by the control panel within 9 seconds.
    * Flash along with 2 beeps: Request for Home mode during Arm mode.
    * Flash along with 3 beeps: Request for Home or Arm Mode when fault condition exists.
    * Flash along with 4 beeps: PIN code was incorrect.

## General Operation

* Enter Test mode — Enter Keypad PIN code and then press ＊ key.
* Panic Alarm — Enter **1** key + **3** key at the same time. (if the function is enabled)
* Fire Alarm — Enter **4** key + **6** key at the same time. (if the function is enabled)
* Medical Alarm — Enter **7** key + **9** key at the same time. (if the function is enabled)
* Check Control Panel Status — Normal Mode: press **#** key.

## Power

* Remote keypad uses one CR123 3V Lithium battery as its power source.
* Remote keypad can also detect the battery status. If the battery voltage is low, the Power LED will flash for 5 seconds during operation. The Low battery signal will be sent along with regular signal transmissions to the Control Panel for displaying the status accordingly.
* Before shipment, the battery is pre-installed by the factory.
* When changing battery, press any key a couple times to discharge before inserting new battery.

## Power Saving Feature

* When idle, Remote keypad is in **Stand-by** mode and uses no power. It will activate and **wake-up** for 5 seconds when any key is pressed.
* After 5 seconds of key inactivity, the power goes off and it returns to **Stand-by** mode.

## Tamper Protection

* The keypad is protected against any attempt to open the lid or to detach keypad from its mounting surface.
* Tamper protection is disabled when the keypad is in Test Mode.

## Supervision Signal

* After installation, the Remote Keypad will automatically transmit Supervision Signals to the Control Panel at an interval of 15-18 minutes.
* If the Control Panel has not received the signal from the Remote Keypad for a preset period of time, the Control Panel will consider the Remote Keypad out of order and react according to panel setting.

## Getting Started

{% stepper %}
{% step %}
### Step 1. Put the Control panel into learning mode.
{% endstep %}

{% step %}
### Step 2. Add the remote keypad into the Control Panel

#### Test Mode

1. Put remote keypad in Test mode by entering KP PIN code (default: **0000**), then press ＊ key.
2. The LEDs will turn on along with a long beep.
3. Press ＊ key then **7** key to transmit learning signal. Remote keypad will sound a long beep.

#### Test Mode Function

1. Press ＊ key and then 2 key — Enable Dual-key Panic Alarm function
2. Press ＊ key and then 3 key — Enable Dual-key Fire Alarm function
3. Press ＊ key and then 4 key — Enable Dual-key Medical Alarm function
4. Press ＊ key and then 5 key — Disable all Dual Key function (Default)
5. Press ＊ key and then 6 key — Edit Keypad Pin Code
   * Enter **Old** Keypad Pin Code and then press ＊ key.
   * Enter **New** a new 4-digit Keypad Pin Code and then press **#** key.
6.  Press ＊ key and then 8 key — Enable Arm/Home without PIN Code function.

    _Please refer to “**Arm/Home without Control Panel PIN Code**” for details, page 3._
7.  Press ＊ key and then 9 key — Enable Arm/Home with Control Panel User PIN Code function (Default).

    _(Please refer to “**Arm/Home with Control Panel PIN Code**” for details, page 3_).\_

#### Notes

* If the remote keypad did not sound a long beep, it means the remote keypad did not send the learning code to the Control Panel. Please press ＊ key then **7** key again to send the learning code.
* If the Control Panel receives the learning code, it will display the info accordingly. Refer to the operation manual of your Control Panel to complete the learn-in process.
* After Control Panel receives the signal from remote keypad, it will send an acknowledgement back to remote keypad. The remote keypad will then beep 3 times to confirm the acknowledgement has been received. If remote keypad does not perform 3 beeps, please restart the learning procedure.
* When attempting to enter test mode, if you input incorrect KP PIN Code (default: **0000**) for 4 times, the Keypad will disable the key function for 1 minute. All the LEDs will flash 3 times along with 6 beeps. After 1 minute, it will emit a long beep to indicate that the key function is back to normal.
{% endstep %}

{% step %}
### Step 3. Confirm the signal range

After the Remote keypad is learnt-in, put the Control Panel into **Walk Test** mode, hold the Remote keypad in the desired location, and send the learning code to the Control Panel to confirm this location is within the signal range of the Control Panel.

To send the learning code, either press the ＊ key then **7** key under Test Mode or press both **#** and ＊ keys together under Normal Operation Mode.
{% endstep %}

{% step %}
### Step 4. Mount the remote keypad

When you are satisfied that the Remote keypad works in the chosen location, you can proceed with mounting the Remote keypad following the steps described below (please refer to “_**Mounting Remote keypad**” for details)_.
{% endstep %}

{% step %}
### Step 5. Exit Test mode

Press Disarm key **twice** to leave Test mode and the installation is completed. Remote keypad will sound a long beep and three system mode LEDs will turn off. The Remote keypad returns to Normal Operation mode.
{% endstep %}
{% endstepper %}

{% hint style="info" %}
The Remote keypad will automatically exit Test mode after 5 minutes of inactivity and return to Stand-by mode. All the LEDs will turn off and the Keypad will emit one long beep.
{% endhint %}

## System Mode Control

After finish learning the Keypad into alarm system Control Panel, the user may change the system using Keypad.

There are two ways to arm the system:

1. Away Arm / Home Arm the system by entering Control Panel User PIN Code.
2. Away Arm / Home Arm the system without entering Control Panel User PIN Code.

Disarming the system always requires entering Control Panel User PIN Code.

### Arm/Home/Disarm with Control Panel PIN Code

Under Test mode, press ＊ key and then **9** key to enable Arm/Home with PIN Code function.

* **Enter Arm Mode**: Enter any one of Control Panel user code and press key. If panel has no fault and arming is successful, the LED will turn ON along with a long beep.
* **Enter Home Mode**: Enter any one of Control Panel user code and key. If panel has no fault and arming is successful, the LED will turn ON along with 3 beeps.
* **Return to Disarm Mode**: Enter any one of Control Panel user code and key. If disarm is successful, the LED will turn ON along with 2 beeps.
* If there is **Alarm Memory**, the LED and the fault LED will turn ON along with 5 beeps.

{% hint style="info" %}
When changing system mode, if incorrect Control Panel PIN Codes are attempted consecutively, the Keypad will not disable its key function, but the Control Panel may temporarily reject any PIN codes entered via the Keypad to prevent malicious attacks, depending the Panel settings.
{% endhint %}

### Arm/Home/Disarm without Control Panel PIN Code

In the Test mode, press ＊ key and then **8** key to enable Arm/Home without PIN Code function.

* **Enter Arm Mode**: Press key. If panel has no fault and arming is successful, the LED will turn ON along with one long beep.
* **Enter Home Mode**: Press key. If panel has no fault and arming is successful, the LED will turn ON along with 3 beeps.
* **Return to Disarm Mode**: Enter any one of Control Panel user code and key. If disarm is successful, the LED will turn ON along with 2 beeps.
* If there is **Alarm Memory**, the LED and the fault LED will turn ON along with 5 beeps.

## Fault Conditions

_When Remote Keypad is under **NORMAL OPERATION MODE**,_

1. When fault condition exists within Control Panel, if the Keypad is used to arm the panel, the Fault LED will flash along with 3 beeps to indicate fault condition.
2. When the Keypad disarms the panel, the LED will turn ON along with two beeps indicating normal operation.
3. If you input incorrect KP Pin code for 4 times under test mode, KP will disable the key function for 1 minute and all the LEDs will flash 3 times along with 6 beeps. After 1 minute, it will emit a long beep to indicate that the key function is back to normal.
4. When attempting to enter test mode, if you input incorrect KP PIN Code (default: **0000**) for 4 times, the Keypad will disable the key function for 1 minute. All the LEDs will flash 3 times along with 6 beeps. After 1 minute, it will emit a long beep to indicate that the key function is back to normal.
5. When changing system mode, if incorrect Control Panel PIN Codes are attempted consecutively, the Keypad will not disable its key function, but the Control Panel may temporarily reject any PIN codes entered via the Keypad to prevent malicious attacks, depending the Panel settings.

## Factory Reset

Resetting the Keypad to factory default will restore Keypad’s own PIN Code to 0000 and clear all panel learning memory.

**Reset to factory default:**

1. Remove the batteries and release the tamper.
2. If “**Arm/Home with Control Panel PIN Code**” method is selected, press & hold **3** key while inserting the battery back.
3. If “**Arm/Home without Control Panel PIN Code**” method is selected, press & hold **4** key while inserting the battery back.
4. Continue pressing **3** key until KP emit 3 beeps to indicate successful reset. Continue pressing 4 key until KP emit 4 beeps to indicate successful reset.
5. Release **3** or **4** key, the reset process is complete.

{% hint style="info" %}
* Resetting the Keypad to factory default will restore Keypad’s own PIN Code to 0000. After reset, the Keypad will need a new learn-in process to start functioning.
* Whenever the Keypad is removed from the Control Panel, it should be put to factory reset as well to clear its Control Panel memory.
{% endhint %}

## Mounting Remote Keypad

To mount the remote keypad:

1. Remove the front cover.
2. Using the 2 mounting holes of the back cover as a template, mark off the positions in the most appropriate place.
3. Insert the wall plugs if fixing into plaster or brick surface.
4. Screw the Remote keypad onto the wall plugs.
5. Replace the front cover.
