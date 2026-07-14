---
hidden: true
---

# VESTA 485 to check and add pictures

KPEX-1

## Outdoor Keypad&#x20;



### Introduction

The KPEX-1 Outdoor Keypad offers secure and convenient access control with a built-in RFID reader and PIN code support. It is designed to have quick access control of the System Control Panel via PIN Code, NFC label, or by approaching the keypad with the paired smartphone to disarm the system.

The Outdoor Keypad is built with an IP66 rating for dust ingress and high-pressure water jets protection.

### Identifying the Parts

<figure><img src=".gitbook/assets/image (1329).png" alt=""><figcaption></figcaption></figure>

1. **Mode & Status LED Indicator Bar**
2. **Panic Alarm**

* Press both 1 & 2 keys for 2 seconds to trigger a panic alarm.

3. **Fire Alarm**

* Press both 3 & 4 keys for 2 seconds to trigger a fire alarm.

4. **Medical Alarm**

* Press both 5 & 6 keys for 2 seconds to trigger a medical alarm.

5. **Arm Key / Return Key**

* Press with OK Key to send a learn signal.
* Press once to arm the system

6. **Disarm Key / OK Key**

* Press with Return Key to send a learn signal.
* Press once to disarm the system

7. **NFC Reader**
8. **Buzzer**
9. **Back Tamper Switch**
10. **Battery Compartment**
11. **Casing Tamper Switch**
12. **Mounting Holes**
13. **External Power Terminals**
14. **Spirit Level**
15. **External Power Cable Outlets**

### LED Behavior

The Keypad features a Mode/Status LED indicator bar in Red, Green, or Orange color, and backlight LED for all input keys.

* **Mode LED**
  * Red: System in Away Arm mode or being Away Armed.
  * Green: System in Disarm mode or being Disarmed.
  * Orange: System in Home Arm mode
* **Backlight LED**
  * The backlight LED turns on for 5 seconds when any key is pressed

### Power Supply

The Outdoor Keypad can be powered by batteries or an external power source.

#### Battery Power

* The Keypad is powered by two L91 1.5 V AA lithium batteries.
* The Keypad reports the battery level to the Control Panel upon battery insertion and every 24 hours thereafter.
* When low battery voltage is detected, a low-battery signal will be sent to the Control Panel along with supervision signals.
* When changing the batteries, press any key twice after removing the old batteries to fully discharge the residual power before inserting new ones.

#### External Power

* The Keypad supports a 9 V – 24 V DC power supply via the external power terminal.
* Ensure the positive (+) and negative (-) polarities are connected correctly.
* When both external power and batteries are connected, the Keypad draws power from the external source.
* The Keypad reports the AC power status to the Control Panel alongside the supervision signal.

### Power-Saving Feature

* When idle, the Keypad is in **Stand-by** mode. It will **wake up** when any key is pressed.
* After 5 seconds of key inactivity, the Keypad returns to **Stand-by** mode.

### Tamper Protection

The Keypad is equipped with two tamper switches:

* Case Tamper: The tamper switch is activated when the Keypad’s bottom cover fixing screw is loosened.
* Wall Tamper: The tamper switch is activated when the when the Keypad is removed from the mounting surface.
* **Supervision Signal**
  * The Keypad automatically transmits supervision signals to the Panel at random intervals of 15-18 minutes.

### Audio Indication

* Entry/Exit Delay – The Keypad emits countdown beeps during Entry or Exit Delay if enabled by the Panel.
* Alarm Siren – The Keypad emits siren sounds for alarms, including alarms triggered by the Control Panel.

### Learning into Control Panel

{% stepper %}
{% step %}
### Insert batteries

Insert the batteries, ensuring correct polarity, to power on the device.
{% endstep %}

{% step %}
### Set the Control Panel to learning mode

Set the Control Panel to learning mode. Please refer to the Panel’s manual for details.
{% endstep %}

{% step %}
### Transmit a learn signal

Simultaneously press and hold both the **Return** and **OK** keys for 2 seconds to transmit a learn signal.
{% endstep %}

{% step %}
### Complete the learning process

Refer to panel manual to complete the learning process. The panel will transmit an acknowledgement signal.

Successful learning: The Keypad emits 2 beeps upon receiving acknowledgement signal.

Unsuccessful learning: The Keypad emits 5 beeps if no acknowledgement signal is received. Repeat from Step 3 to send a learn signal again.
{% endstep %}
{% endstepper %}

### Walk Test

After completing the learning process, conduct **Walk Test** to verify the communication between the Keypad and the Control Panel.

{% stepper %}
{% step %}
### Place the Keypad and start Walk Test

Place the Keypad at the desired mounting location. Put the Control Panel into **Walk Test** mode.
{% endstep %}

{% step %}
### Transmit a learn signal

Press and hold both the **Return** and **OK** keys for 2 seconds to transmit a learn signal.

If the Keypad is within the Panel’s signal range, the Panel will display the Keypad’s information accordingly.
{% endstep %}
{% endstepper %}

### PIN Code Management

The PIN Codes are managed through the Control Panel’s programming webpage, refer to panel manual for detail.

The **“PIN Code (NEW)”** page is used to set PIN codes for multiple control panel area. Enter a **4-digit** PIN Code and select which area the PIN Code should be applied to.

<figure><img src=".gitbook/assets/image (1330).png" alt=""><figcaption></figcaption></figure>

If a PIN is assigned to multiple areas in **“PIN Code (NEW)”** page, the system automatically affixes the area number before the PIN in **“PIN Code”** page. For example, when the PIN 1234 is assigned to Areas 1, 2, and 3, the system automatically updates the PINs to **01**1234 for Area 1, **02**1234 for Area 2, and **03**1234 for Area 3.

In **User Code** column on the **PIN Code** page, the first two digits represent the area to which this PIN is assigned. If users change the PIN code here, the new settings will also be updated to the **PIN Code (NEW)** page.

<figure><img src=".gitbook/assets/image (1331).png" alt=""><figcaption></figcaption></figure>

### NFC Tag Configuration

The Keypad is capable of transmitting NFC (Near Field Communication) tags to the Control Panel, and users can assign a PIN code and user name to each NFC tag on the Panel webpage. The NFC tags can then be used to control alarm system mode through the Keypad. The NFC tag numbers and PIN codes are managed on the Control Panel webpage.

#### A. Add Tag

{% stepper %}
{% step %}
### Add the tag

When the system is under **Disarm** mode, apply an unregistered tag to the NFC Reader area, then press **OK**.
{% endstep %}

{% step %}
### Load the tag number

Navigate to the PIN Code page on the Panel webpage. Click **Load**. The tag number will appear.

<figure><img src=".gitbook/assets/image (1332).png" alt=""><figcaption></figcaption></figure>
{% endstep %}

{% step %}
### Enter user code and user name

Input a user code and user name for the tag, then scroll down and click OK to submit.

The tag has been added. You can use it to change system mode.
{% endstep %}
{% endstepper %}

<mark style="color:$warning;">**NOTE:**</mark> The Keypad treats an unregistered tag as an incorrect tag. If it detects an unregistered tag 5 times in 10 minutes, the keys will be locked for 5 minutes. After adding four new tags, present a registered NFC tag before adding another new tag to prevent the keys from being locked.

#### B. Delete Tag

{% stepper %}
{% step %}
### Open PIN Code page

Go to the **PIN Code** page on the Panel’s webpage.
{% endstep %}

{% step %}
### Delete the tag number

Manually delete the tag number, scroll down, and click “OK” to submit. The tag is now cleared.
{% endstep %}
{% endstepper %}

## Operation

### Mode Change

Use the Keypad to change the system mode with PIN codes or NFC tags.

{% stepper %}
{% step %}
### Press the mode key

Press the mode key. The Outdoor Keypad only supports Away Arm mode and Disarm mode. Home Arm mode is not supported.

For disarm operation, users can also simply present a registered tag without pressing Disarm key.
{% endstep %}

{% step %}
### Enter the PIN or apply the NFC tag

Enter the PIN or apply the NFC tags to the NFC reader on the keypad.

* Away Arm: The Red LED will turn on after input. If arming is successful the LED will flash twice and sound a long beep to confirm.
* Disarm: The Green LED will turn on after input. If disarming is successful the LED will flash twice and sound two beeps to confirm.
{% endstep %}
{% endstepper %}

#### Mode Change Fault and Force Arm

* If incorrect PIN code or Tag is used, the Keypad will emit 5 beeps.
* If no acknowledgement is received from the panel for 5 seconds, the Keypad will timeout and emit 5 beeps.
* If fault exists in the system when arming, the panel will not send acknowledgement and the Keypad will emit 5 beeps, repeat the arming attempt to force arm the system.

#### Alarm Memory

If an alarm was activated when the system was armed, the Keypad Green LED will turn on instead of flash when disarming.

#### Keypad Lockdown

* If incorrect PIN code or NFC tag was used for 5 times, the Keypad will be locked for 1 minute. All key input is disabled during the 5-minute lockdown.
* The Keypad Red LED and Backlight LED will flash 6 times and emit 6 beeps upon entering lockdown.
* The Keypad will emit 1 long beep after 1 minute when lockdown ends.

### Entry / Exit Delay

The Keypad can be programmed to sound continuous beeps during Entry and Exit timer. This function is disabled by default and can be enabled remotely from the Control Panel.

### Check System Mode

When the Keypad is under normal operation and the tamper switch is **closed**, enter PIN code then press the **Return** key to check the system mode. The Keypad will emit a long beep.

* When system is in Away Arm mode, the Red LED will flash twice and the Keypad will emit a long beep.
* When system is in Home Arm mode, the Orange LED will flash twice and the Keypad will emit a long beep.
* When system is in Disarm mode, the Green LED will flash twice and the Keypad will emit two short beeps.

### Bluetooth Device Management

To use the Keypad’s Bluetooth feature to disarm the system via Smartphone, the Control Panel must be registered on Home Portal Server.

**Vesta Home 5 app** is used for Bluetooth pairing the smartphone with the Keypad. Up to **25** smartphones can be paired with the keypad to disarm the system via Vesta Home 5 app. Download **Vesta Home 5** from the App Store or Google Play.

#### Bluetooth Setup

**Pairing the Keypad with smartphones**

{% stepper %}
{% step %}
### Enter pairing mode

Disarm the system and release the back tamper switch.

Press and hold **9** and **0** simultaneously for 2 seconds. The Keypad will emit a long beep and turn on the orange Mode LED to indicate it is under Bluetooth pairing mode.
{% endstep %}

{% step %}
### Connect from the smartphone

On your smartphone, open the **SmartHomeSec app**, enter the registered user ID and password, and tap Connect to log into your account.

_**Note:**_ Make sure Bluetooth is turned on for your smartphone setting.
{% endstep %}

{% step %}
### Start Bluetooth pairing

Go to the **All Devices** page, select the Keypad and tap “**Start Bluetooth Pairing**.”
{% endstep %}

{% step %}
### Enter the PIN

Tap **PIN Code**, and input a **4-digit or 6-digit** Control Panel User PIN. The PIN Code cannot be left blank.
{% endstep %}

{% step %}
### Complete pairing

Pairing is successful when a success message is displayed. Tap **OK**; you will be directed to the Keypad setting page where you can change the Pairing PIN code.
{% endstep %}

{% step %}
### Edit the Pairing PIN Code

To edit the Pairing PIN Code, enter 6-digit PIN Code and press the **Return** key under the BLE Pairing mode. If the PIN Code setting is confirmed, the Keypad emits 1 long beep. If the PIN Code setting is not confirmed, the Keypad emits 4 beeps.
{% endstep %}

{% step %}
### Pair more smartphones or exit

Bluetooth pairing is complete. You can repeat Steps 2 to 8 to pair more smartphones.

Press the **OK** key twice to exit Bluetooth Pairing Mode.
{% endstep %}
{% endstepper %}

**Unpairing the Keypad with smartphone**

{% stepper %}
{% step %}
### Enter Bluetooth Pairing Mode

Enter **Bluetooth Pairing Mode** on the Keypad.
{% endstep %}

{% step %}
### Unpair a smartphone

Enter **smartphone number (0\~24)**, then press the **OK** key to unpair the specific smartphone.

The first smartphone paired is assigned to number **0**, the second one is assigned to number **1**, and so on.

Entering **25** then press the **OK** key will unpair **all** smartphones.
{% endstep %}

{% step %}
### Remove the device from the smartphone

Tap **Remove Bluetooth Function** on your smartphone to remove the Keypad.
{% endstep %}

{% step %}
### Exit pairing mode

Press the **OK** key twice to exit Bluetooth Pairing Mode.
{% endstep %}
{% endstepper %}

#### Disarm the system via Smartphone

When the system is armed, approach the Keypad with the paired smartphone. Once the Keypad detects the paired smartphone within the BLE range, the system will automatically disarm.

* The smartphone’s Bluetooth function needs to be turned ON, and Vesta Home 5 app kept active in the background.
* The smartphone must be correctly paired with the Keypad and assigned a 4-digit or 6-digit PIN code.
* The effective Bluetooth detection distance may vary depending on the smartphone model.
* After the system arms, a 30-second buffer is configured for the paired device to leave the detection range. The Keypad will start detecting paired smartphones only after the system is armed for 30 seconds. If any paired device is detected when the system arms, the system will not Disarm until the 30-second buffer expires.

### Dual-Key Alarm Functions

* The dual-key function allows users to raise panic, fire, or medical alarms by pressing specific key combinations.
* Dual-key function is enabled by default and can be disabled XML commands on from the Control Panel.
* Panic Alarm: Press “1 + 2” for 2 seconds.
* Fire Alarm: Press “3 + 4” for 2 seconds.
* Medical Alarm: Press “5 + 6” for 2 seconds.

If a dual-key function is disabled, the Keypad emits 4 beeps when its key combination is pressed for 2 seconds, indicating and invalid operation.

### Battery Replacement

{% stepper %}
{% step %}
### Disarm the system

Disarm the system.
{% endstep %}

{% step %}
### Remove the keypad from the base

Loosen the bottom fixing screw.

Detach the main unit from the mounting base.
{% endstep %}

{% step %}
### Replace the batteries

Remove the screw of the battery compartment cover and remove the old batteries.

Press any key twice to fully drain the residual power, then insert 2 new batteries.
{% endstep %}

{% step %}
### Reassemble the keypad

Replace the battery compartment cover and fasten the screw.

Re-attach the main unit to the mounting base, then secure the bottom fixing screw.
{% endstep %}
{% endstepper %}

### Factory Reset

If users forget the Keypad PIN code or the Smart Keypad malfunctions, they can reset it to the factory default settings and reinitialize it.

{% stepper %}
{% step %}
### Disconnect power and release tamper

Disconnect the power supply and release the back tamper switch.
{% endstep %}

{% step %}
### Hold key 3 while reconnecting power

Press and hold key **3** while reconnecting the power supply.
{% endstep %}

{% step %}
### Wait for the confirmation beeps

Continue holding key **3** until three short beeps are emitted, indicating a successful reset.

* After the reset, the Keypad PIN code reverts to the factory default **0000**.
* The Smart Keypad must be learned into the system again before it can be used.
{% endstep %}
{% endstepper %}

### Firmware Update

The Keypad firmware can be updated over-the-air via the Control Panel, provided that the system must be in **Disarmed** mode.

{% stepper %}
{% step %}
### Find the Panel IP address

Identify the Panel’s IP address on LAN (refer to the Panel manual for details).
{% endstep %}

{% step %}
### Open the Device Upgrade webpage

Enter **IPaddress/setting/deviceUpgrade.htm** to the address bar of your browser. You will open the Device Upgrade webpage for firmware update.
{% endstep %}

{% step %}
### Select the keypad

Select the keypad you wish to upgrade its firmware.
{% endstep %}

{% step %}
### Choose the firmware file and start update

Click **Select a file**, choose the firmware file on your PC, then click **OK** to begin the update.

After update is complete, the Keypad will reboot automatically.
{% endstep %}
{% endstepper %}

### XML Command Setting

The following Keypad functions are remotely configurable by XML command:

1. Dual-key alarm functions
2. Bluetooth detection range

Please access the Smart Keypad’s **Device Edit** page on Panel webpage.

Enter a **4-digit** hexadecimal (hex) value into KP-EX Configuration 1 (see the configuration table below), then click **OK**. The Keypad will emit a long beep and apply the new setting.

| Bit15                    | Bit14               | Bit13                  | Bit12 | Bit11 | Bit10 | Bit9 | Bit8 |
| ------------------------ | ------------------- | ---------------------- | ----- | ----- | ----- | ---- | ---- |
| Res.                     | Res.                | Res.                   | Res.  | Res.  | Res.  | Res. | Res. |
| Bit7                     | Bit6                | Bit5                   | Bit4  | Bit3  | Bit2  | Bit1 | Bit0 |
| Dual Key 1+3 (Panic)     | Dual Key 4+6 (Fire) | Dual Key 7+9 (Medical) | Res.  | Res.  | Res.  | Res. | Res. |
| **Bit15-Bit8: Reserved** |                     |                        |       |       |       |      |      |

**Bit7: Dual-key Panic Alarm (1+3)**

* 1 = Disable
* 2 = Enable (Default)

**Bit6: Dual-key Fire Alarm (4+6)**

* 1 = Disable
* 2 = Enable (Default)

**Bit5: Dual-key Medical Alarm (7+8)**

* 1 = Disable
* 2 = Enable (Default)

**Bit4-Bit0: Reserved**

## Installation

<figure><img src=".gitbook/assets/image (1333).png" alt=""><figcaption></figcaption></figure>

{% stepper %}
{% step %}
### Remove the main unit

Loosen the bottom fixing screw.

Detach the main unit from the mounting base.
{% endstep %}

{% step %}
### Position the mounting base

Place the mounting base against the surface and use the integrated spirit level to ensure it is level.
{% endstep %}

{% step %}
### Drill and secure the base

Mark and drill six holes using the base as a template.

Secure the mounting base to the mounting surface with the provided screws.
{% endstep %}

{% step %}
### Re-attach the main unit

Re-attach the main unit to the mounting base by hooking the upper tabs first, then closing the bottom.
{% endstep %}

{% step %}

{% endstep %}

{% step %}
### Fasten the fixing screw
{% endstep %}

{% step %}
Fasten the bottom fixing screw firmly to ensure the case tamper and wall tamper switches are properly compressed.
{% endstep %}
{% endstepper %}
