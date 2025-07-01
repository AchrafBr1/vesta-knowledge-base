# VESTA-108

SR-32 / SR-32-F1

## Wireless Indoor Siren

The Indoor Siren is used to attract attention when alarm signal is received from Control Panel by activating its siren. The Siren can also alert you to tamper violation, and low battery status.

## **Identifying the Parts**

![](<.gitbook/assets/0 (30).png>)

**1. Tamper Switch**

The Tamper switch will be activated when the Siren is removed from mounted surface, or when its cover opened.

**2. Battery Compartment**

The Siren is powered by two 1.5V D-Cell alkaline batteries.

**3. Battery Switch**

The battery switch is used when battery is installed in the Indoor Siren. To power on/off the Indoor Siren, switch the ON/OFF switch.

**4. Mounting Holes x 3**

**5. Learn Button**

* Accessories included

In addition to the Siren itself, the following accessories are also included in the package:

3 x large wall plugs.

3 x fixing screws for wall mounting

2 x 1.5V D alkaline batteries (pre-inserted)

## Battery and Low Battery Detection

The Siren is powered by two 1.5V Alkaline D batteries, it features low battery detection and will transmit low battery signal when low battery voltage is detected.

When changing batteries, after removing the old batteries, press the Tamper Switch a couple times to fully discharge before inserting new batteries.

{% hint style="warning" %}
Note:

Only use specified batteries with the device. When replacing batteries, always replace the whole set, do not mix different types of batteries or new and used ones to avoid damaging the device.

Supervision
{% endhint %}

The Siren will transmit a supervisory signal every 30-50 minutes in normal operation mode. If this signal is not received, the Control Panel will indicate that the particular Siren is experiencing an out-of-order problem.

## Siren Function Overview

### **Audio & Visual Status Indication**

While arming / disarming the system, the SR-32 uses different methods to distinguish various statuses for the user, as listed in the table.

|                      | Siren Audio      |
| -------------------- | ---------------- |
| Arm/Home             | 1 beep\*         |
| Disarm               | 2 beeps\*        |
| Arm (Low Battery)    | 3 beeps          |
| Disarm (Low Battery) | 3 beeps          |
| Arm (Tamper)         | 5 beeps          |
| Disarm (Tamper)      | 5 beeps          |
| Entry/Exit Sound     | Count-down beeps |

**\*** The Siren Audio indication will be affected by the Confirmation ON / OFF setting. When setting Confirmation to OFF, the confirmation sound will not be available. Refer to Control Panel Siren setting for Confirmation function.

### **Alarm Memory**

If an alarm was triggered in your absence and the system was not disarmed before alarm length expiry, the Siren will sound a short alarm when the system is disarmed or home armed to warn the user that an alarm has been triggered when he is away. This suggests that the intruder could still be within the premises.

### **Alarm Length**

When an alarm is activated by Control Panel, the Control Panel will notify the Siren to start alarming according to the panel’s own alarm length setting. When the Panel’s alarm length expires, it will notify the Siren to stop alarm.

If the Siren does not receive the Control Panel’s signal to stop alarm, it will sound alarm for a maximum of 15 minutes, then stop the alarm.

For example:

* If the Panel alarm length is set more than 15 minutes, after an alarm is activated, instead of waiting panel alarm length to expire, the Siren will stop alarming after 15 minutes.
* If the panel is under disarm mode and the Siren\` tamper switch is triggered, the Siren will activate alarm for 15 minutes since the panel is under disarm mode and will not activate alarm from tamper trigger.

### **Siren Tamper**

The Siren is protected against any attempt to open the lid or to detach the Siren from its mounting surface.

If the Siren detects a tamper condition, it will activate the siren. A tamper signal will be sent to the Control Panel along with regular signal transmissions for the Control Panel to display the status accordingly. If the tamper condition persists, the Siren will sound a series of five beeps either every time the system is armed or when the tamper is enabled, to indicate a fault.

Tamper feature can be disabled temporaily from the Control Panel using Siren Tamper control function. The Siren will stop tamper detection temporarity for one hour. This function is mainly designed for replacing battery or changing Siren installation location. After one hour, The Control Panel will automatically turn the function back ON after the duration. The tamper detection can also be enabled again manually using the Siren Tamper function.

## Getting Started

### **Learning**

Step 1: Release the bottom screw of the Siren using a Phillips screwdriver and remove the top cover.

Step 2: Put the Control Panel into learning mode (refer to Control Panel’s user manual for details).

Step 3: Slide the battery switch to ON position to power on the Siren. The buzzer will emit 1 beep.

Step 4: Press the Learn button once. The Siren will emit a short beep. The Siren is now in learning mode and will transmit a learning code to the Control Panel.

Step 5: If the Control Panel did not receive a learning code, press the learn button again (the Siren will not sound a beep this time).

Step 6: If the Control Panel receives the learning code, it will list the device information accordingly, follow Control Panel manual instruction to complete the learning procedure. An acknowledgement will be sent to the Siren. When the acknowledgment is received, the Siren will sound five beeps to indicate that learning process is successful. The Siren will then leave learning mode.

Step 7: Refer to the Control Panel manual and use Edit Device function to check Siren settings. You can edit the operation area, zone number, and device name for the Siren.

{% hint style="warning" %}
Note:

If the learning process fails, please remove the Siren from the Control Panel and repeat Steps 4-7 again.

If the Siren does not receive the confirm code from the Control Panel within one minute, the Siren will leave learning mode. Restart learning process from Step 4.
{% endhint %}

### **Edit Siren Operation Area**

Follow instruction below to change Siren Operation Area in the Control Panel

Step 1: Use the panel Edit Device function to change Siren area setting.

Step 2: Press the learn button on the Siren to send signal to panel.

Step 3: When the Siren receives acknowledgement signal from panel, it will emit a beep to indicate the setting has been updated. The Siren will return to normal operation.

## **Programming:**

### **Sound/Siren Setting**

Use the Control Panel “**Sound/Siren Setting**” webpage to set siren configuration function:

_<mark style="color:blue;">**Tamper On/ Tamper Off**</mark>_

You can enable or disable all RF Sirens’ tamper protection with this function. Select to turn on or off the siren’s tamper function.

{% hint style="warning" %}
Note:

When turned off, the Siren will stop tamper detection temporarity for one hour. After one hour, the Control Panel will automatically turn the function back ON if the tamper function is not turned on manually.
{% endhint %}

### **Individual Siren Function**

Edit the device editing page to enter the Siren setting and information accordingly.

* **Name:** Enter a name for the Siren.
* **Area:** Select the area which the Siren belongs to.
* **Zone:** Select the Siren zone number.

_<mark style="color:blue;">**Attribute:**</mark>_

* **Permanently Bypass:** If checked, the Control Panel will completely ignore all signal received from the Siren. A bypassed Siren will not be able to trigger any response, including alarm or fault from the Control Panel. All other attribute settings will also be ignored.
* **Whole Area:** if checked, all the Volume, Voice and Behavior functions will be simultaneously enabled in Area 1 and Area 2.

_<mark style="color:blue;">**Volume:**</mark>_

* **Alarm Sound:** set the volume of the alarm sound of the Siren when alarming.
* **Full arm confirm beep:** set the volume of the confirm beep sound of the Siren when Control Panel is put into Full Arm Mode.
* **Home arm confirm beep:** set the volume of the confirm beep sound of the Siren when Control Panel is put into Home Arm Mode.
* **Disarm confirm beep:** set the volume of the confirm beep sound of the Siren when Control Panel is put into Disarm Mode.
* **Exit beeps of full arm:** set exit countdown beep volume under Full Arm Mode.
* **Exit beeps of home arm:** set exit countdown beep volume under Home Arm Mode.
* **Entry beeps of full arm:** set entry countdown beep volume under Full Arm Mode.
* **Entry beeps of home arm:** set entry countdown beep volume under Home Arm Mode.
* **Door Chime:** set the volume of the Door Chime sound (Ding-Dong Sound).

_<mark style="color:blue;">**Behavior**</mark>_

* **Burglar trigger in home arm:** Enable or Disable whether Siren is activated when an alarm is triggered under Home Arm.
* **Burglar trigger in full arm:** Enable or Disable whether Siren is activated when an alarm is triggered under Full Arm.
* **Strobe activation:** Enable or Disable Siren LED strobe activation.
* **Confirm flash:** Enable or Disable Siren LED flash when system Armed/Disarmed.
* **Exit flash:** Enable or Disable Siren LED flash during an exit countdown period.
* **Entry flash:** Enable or Disable Siren LED flash during an entry countdown perio&#x64;**.**
* **Trigger flash:** Enable or Disable the flashing from the Siren LED when alarming.
* **Alarm-in-memory sound:** Enable or Disable Alarm in Memory sound.
* **Fault sound:** Enable or Disable system fault sounds.

## Installation

Proceed to installation after complete learning.

Step 1. Disable the Siren Tamper function on the Control Panel (please refer to the Control Panel instruction manual). The Siren will sound a beep to indicate the tamper switch is now disabled.

{% hint style="warning" %}
Note:

The siren tamper can be turned off temporarily for 1 hour, refer to Control Panel instruction manual for further setup. The siren tamper will be turned on automatically after 1 hour in case users forget to turn it on.
{% endhint %}

Step 2. Find the location where the Siren is to be mounted.

Step 3. Remove the Top cover by releasing the bottom screw using a Phillips screwdriver and remove the top cover.

Step 4. Hold the Siren at the position where it will be mounted.

Step 5. Check whether BX has a strong enough signal with the Control Panel by putting the Control Panel into **Walk Test** mode (please refer to Control Panel manual). Press the **Learn Button** to check whether the signal is strong enough (please refer to Control Panel manual for signal strength).

Step 6. If you are satisfied with the signal strength, you can proceed to mounting the Siren.

Step 7. Identify the upside down keyhole mounting hole located at upper part of the Siren. The hole is larger than the slot, which allows you to easily slip the hole over the head of the screw and then slide down to securely hold the Siren against the wall. Drill one hole and insert one wall plug if required (a), as shown in Figure 1.

Step 8. Identify the two mounting holes at lower part of the Siren. Drill two holes and insert wall plugs if required (b), as shown in Figure 1. Make sure the wall plugs are flush with the wall.

<figure><img src=".gitbook/assets/image (38).png" alt=""><figcaption></figcaption></figure>

&#x20;                                                                                                Figure 1

Step 9. Secure the screw using a Phillips screwdriver. Make sure the Tamper Switch is fully depressed against the wall

{% hint style="warning" %}
Note:

The tamper switch protrudes through the back of the unit. When the siren is pulled off from the wall, the alarm will be activated. Ensure it is fully depressed when the siren is mounted.
{% endhint %}

Step 10. Replace the Top cover and tighten the bottom screw using a Phillips screwdriver, as shown below.

<figure><img src=".gitbook/assets/image (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1).png" alt=""><figcaption></figcaption></figure>

&#x20;                                                                                           Figure 2

Step 11. Enable Siren Tamper function on the Control Panel (Please refer to the Control Panel instruction manual)

Step 12. Check if the installation is successful by testing from the Control Panel by arming and disarming function.

Successful arming/disarming is indicated by the table provided in **Audio & Visual Status Indication**.

{% hint style="warning" %}
Note:

If 5 short-beeps are noticed while arming/disarming, it means the tamper is not fully depressed. Check to ensure that tamper is properly set and then test from Control Panel again.
{% endhint %}

Step 13. The installation is now completed.

## Changing the Battery

Step 1: Disable the Siren Tamper function on the Control Panel. The Siren will sound a beep to indicate the tamper switch is now disabled.

{% hint style="warning" %}
Note:

The siren tamper can be turned off temporarily for the need of changing batteries, refer to Control Panel instruction manual for further setup. The siren tamper will be turned on automatically after 1 hour in case users forget to turn it on after battery replacement is completed.
{% endhint %}

Step 2: Release the cover-fixing screw at the bottom of Siren using a Phillips screwdriver and pull the outer case out carefully.

Step 3: Slide the battery switch to OFF position.

Step 4: The battery compartment is a large box in the Siren with a lid secured by 2 screws. Release the screws using a Phillips screwdriver and take off the compartment lid. Please save the screws for later use.

Step 5: Remove the old batteries and press the Tamper Switch a couple times to discharge.

{% hint style="info" %}
Note:

When changing batteries, after removing the old batteries, press the Learn Button twice to fully discharge before inserting new batteries.

Only use specified batteries with the device. When replacing batteries, always replace the whole set, do not mix different types of batteries or new and used ones to avoid damaging the device.
{% endhint %}

Step 6: Insert new batteries into the battery compartment.

Step 7: After inserting batteries, slide the battery switch to ON position. The buzzer will emit 1 beep as the Siren powers on.

Step 8: Replace and secure the battery compartment lid with 2 screws using a Phillips screwdriver.

Step 9: Replace and secure the Top cover by tightening the bottom screw using a Phillips screwdriver.

Step 10: Enter the Control Panel Program Siren webpage again to enable the Siren Tamper function again. The Siren will sound a beep to indicate the tamper switch is now activated.

## Factory Reset

The Siren can be reset and memory contents cleared. Whenever the Siren is removed from the Control Panel, it should be put to factory reset to clear its Control Panel memory, otherwise the Siren will still raise alarm if it receives alarm signal from panel.

Step 1: Disable the Siren Tamper function on the Control Panel (please refer to the Control Panel instruction manual). The Siren will sound a beep to indicate the tamper switch is now disabled.

Step 2: Remove the Siren from Control Panel device list (please refer to the Control Panel instruction manual).

Step 3: Release the bottom screw of the Top cover using a Phillips screwdriver, remove the top cover..

Step 4: Slide the battery switch to the OFF position.

Step 5: Press and hold the Learn Button and slide the battery switch to ON position. Continue to hold the Learn Button for 7 seconds. Release the Learn Button when you hear 2 short beeps and a long beep. The previous parameters in the Siren will be cleared and it will return to normal mode.

{% hint style="warning" %}
Note:

Whenever the siren is removed from the Control Panel, it should be put to factory reset as well to clear its Control Panel memory.
{% endhint %}

*
