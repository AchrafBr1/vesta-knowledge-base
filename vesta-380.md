# VESTA-380

**BX-32**

## **Wireless Outdoor Bell Box**&#x20;

The Outdoor Bell Box is used to attract attention when alarm signal is received from Control Panel, by activating its siren and strobe light.

The Bell Box can also alert you to tamper violation, and low battery status.

<figure><img src=".gitbook/assets/0 (1) (1) (1).jpeg" alt=""><figcaption></figcaption></figure>

## Identifying the Parts

### 1 Tamper Switch

The Tamper switch will be activated when the Bellbox is removed from mounted surface, or when its cover is opened.

### **2. Battery Compartment**

The Bellbox is powered by two 1.5V D-Cell alkaline batteries.

### **3. Battery Switch**&#x20;

### **4. Wall Mounting Holes x 3**&#x20;

### **5. Learn Button**&#x20;

### **6. LED 3 & 2 & 1 (From Left to Right)**

### Accessories included

In addition to the Bell Box itself, the following accessories are also included in the package:&#x20;

1. 3 x large wall plugs
2. 3 x fixing screws for wall mounting
3. 2 x 1.5V D alkaline batteries (pre-inserted)

### Battery and Low Battery Detection

The Bellbox is powered by two 1.5V Alkaline D batteries; it features low battery detection and will transmit low battery signals when low battery voltage is detected.

When changing the batteries, after removing the old batteries, press the Tamper Switch a couple times to fully drain the residual energy before inserting new ones.

### Supervision

The Bell Box is supervised by sending a periodic supervision signal to the Control Panel. When the Control Panel fails to receive a supervision signal within the preprogrammed period, it will indicate a fault.

## Function Overview

### Alarm Memory

If an alarm was triggered in your absence and the system was not disarmed before alarm length expiry, the Bellbox will sound a short alarm when the system is disarmed to warn the user that an alarm has been triggered when he is away. This suggests that the intruder could still be within the premises.

### Alarm Length

When an alarm is activated by Control Panel, the Control Panel will notify the Bellbox to start alarming according to the panel’s own alarm length setting. When the Panel’s alarm length expires, it will notify the Bellbox to stop alarm.

If the Bellbox does not receive the Control Panel’s signal to stop alarm, it will sound alarm for a maximum of 3 minutes, then stop the alarm. For example:

* If the Panel alarm length is set more than 3 minutes, after an alarm is activated, instead of waiting panel alarm length to expire, the Bellbox will stop alarming after 3 minutes.
* If the panel is under disarm mode and the Bellbox tamper switch is triggered, the Bellbox will activate alarm for 3 minutes since the panel is under disarm mode and will not activate alarm from tamper trigger.

### Siren Tamper

The Bellbox is protected against any attempt to open the top cover or to detach it from its mounting surface.

If the Bellbox detects a tamper condition, it will activate the siren & strobe light for the programmed alarm period. A tamper signal will be sent to the Control Panel along with regular signal transmissions for the Control Panel to display the status accordingly. If the tamper condition persists, the Bellbox will sound a series of five beeps either every time the system is armed or when the tamper is enabled, to indicate a fault.

Tamper feature can be disabled temporaily from the Control Panel using Siren Tamper control function. The Bellbox will stop tamper detection temporarity for one hour. This function is mainly designed for replacing the battery or changing the installation location. After one hour, The Control Panel will automatically turn the function back ON after the duration. The tamper detection can also be enabled again manually using the Siren Tamper function.

### Audio & Visual Status Indication

While arming / disarming the system, the Bellbox uses different methods to distinguish various statuses for the user, as listed in the table.

| **System Status**    | **Siren Audio**    | **Strobe Light Indication**        |
| -------------------- | ------------------ | ---------------------------------- |
| Arm/Home             | 1 bee&#x70;**\***  | 3 LED groups flash once            |
| Disarm               | 2 beep&#x73;**\*** | Sequentially flashes for 1 cycle   |
| Arm (Low Battery)    | 3 beeps            | 3 LED groups flash for three times |
| Disarm (Low Battery) | 3 beeps            | Sequentially flashes for 3 cycles  |
| Arm (Tamper)         | 5 beeps            | 3 LED groups flash for 5 times     |
| Disarm (Tamper)      | 5 beeps            | Sequentially flashes for 5 cycles  |
| Entry/Exit Sound     | Count-down beeps   |                                    |

**\*** The Siren Audio indication will be affected by the Confirmation ON / OFF setting. When setting Confirmation to OFF, the confirmation sound will not be available. Refer to Control Panel Sound/Siren setting for Confirmation function.

## Getting Started

### Learning

<table data-header-hidden><thead><tr><th width="104"></th><th></th></tr></thead><tbody><tr><td>Step 1</td><td>Loosen the bottom screw of the Bellbox with a Phillips screwdriver and detach the top cover.</td></tr><tr><td>Step 2</td><td>Put the Control Panel into learning mode (refer to Control Panel’s user manual for details).</td></tr><tr><td>Step 3</td><td>Slide the battery switch to ON position to power on the Bellbox. All LEDs will flash once and the buzzer will beep once.</td></tr><tr><td>Step 4</td><td>Press the Learn button once. The Bellbox will emit a short beep and LED 1 &#x26; 3 will turn on briefly. The Bellbox is now in learning mode and will transmit a learning code to the Panel.</td></tr><tr><td>Step 5</td><td>If the Panel did not receive a learning code, press the learn button again (the Bellbox will not sound a beep this time).</td></tr><tr><td></td><td>If the Panel receives the learning code, it will list the device information accordingly (follow Control Panel manual instruction to complete the learning procedure). An acknowledgement will be sent to the Bellbox. When the acknowledgment is received, the Bellbox will sound a short beep and flash LED 2 once to indicate the learning process is successful and then leave learning mode.</td></tr><tr><td>Step 6</td><td>Refer to the Control Panel’s manual and use Edit Device function to check Bellbox settings. You can edit the operation area, zone number, and device name for the Bellbox.</td></tr></tbody></table>

{% hint style="warning" %}
Note:

* If the learning fails, please remove the Bellbox from the Control Panel and repeat Steps 4-7 again.
* If the Bellbox does not receive the confirm code from the Control Panel within one minute, the Bellbox will leave learning mode. Restart learning process from Step 4.
{% endhint %}

### Edit Device Operation Area

Step 1 Use the “Edit Device” function on the Panel’s webpage to change the area setting.

Step 2 For the device communicating directly with the Panel, the setting is completed after clicking OK.

For the device using a Repeater, press the Learn Button once to transmit a learn code after changing the area setting.

## Programming

### **Sound/ Siren Setting**

Use the Control Panel “**Sound/ Siren Setting**” webpage to set Bellbox configuration function: _**Tamper On/ Tamper Off**_

You can enable or disable all RF Bellbox’s tamper protection with this function. Select to turn on or off the Bellbox’s tamper function.

{% hint style="warning" %}
Note:

When turned off, the Bellbox will stop tamper detection temporarity for one hour. After one hour, the Control Panel will automatically turn the function back ON if the tamper function is not turned on manually.
{% endhint %}

### **Individual Bellbox Function**

Edit the device editing page to enter the Bellbox setting and information accordingly.

* **Name:** Enter a name for the Bellbox.
* **Area:** Select the area which the Bellbox belongs to.  **Zone:** Select the Bellbox zone number.

#### **Attribute**

* **Permanently Bypass:** If checked, the Control Panel will completely ignore all signal received from the Bellbox. A bypassed Bellbox will not be able to trigger any response, including alarm or fault from the Control Panel. All other attribute settings will also be ignored.
* **Whole Area:** if checked, all the Volume, Voice and Behavior functions will be simultaneously enabled in all areas.

#### **Volume**

* **Alarm Beep:** set the volume of the alarm sound of the Bellbox when alarming.
* **Full arm confirm beep:** set the volume of the confirm beep sound of the Bellbox when Control Panel is put into Full Arm Mode.
* **Home arm confirm beep:** set the volume of the confirm beep sound of the Bellbox when Control Panel is put into Home Arm Mode.
* **Disarm confirm beep:** set the volume of the confirm beep sound of the Bellbox when Control Panel is put into Disarm Mode.
* **Exit beeps of full arm:** set exit countdown beep volume under Full Arm Mode.
* **Exit beeps of home arm:** set exit countdown beep volume under Home Arm Mode.
* **Entry beeps of full arm:** set entry countdown beep volume under Full Arm Mode.
* **Entry beeps of home arm:** set entry countdown beep volume under Home Arm Mode.
* **Door Chime:** set the volume of the Door Chime sound (Ding-Dong Sound).
* **VDP doorbell:** This function is not supported by BX-32.
* **Arm with Fault:** set the volume of the beep when arming with fault.
* **Outdoor Burglar:** This function is not supported by BX-32.

#### **Behavior**

* **Burglar trigger in home arm:** Enable or Disable whether Bellbox is activated when an alarm is triggered under Home Arm.
* **Burglar trigger in full arm:** Enable or Disable whether Bellbox is activated when an alarm is triggered under Full Arm.
* **Strobe activation:** Enable or Disable the LED strobe light activation.
* **Confirm flash:** Enable or Disable the LED flash when system Armed/Disarmed.  **Exit flash:** Enable or Disable the LED flash during an exit countdown period.
* **Entry flash:** Enable or Disable the LED flash during an entry countdown period.
* **Trigger flash:** Enable or Disable the LED flashing when alarming.
* **Alarm-in-memory sound:** Enable or Disable Alarm in Memory sound.
* **Fault sound:** Enable or Disable system fault sounds.

## Installation

Proceed to installation after complete learning.

<figure><img src=".gitbook/assets/8 (1) (1).jpeg" alt=""><figcaption></figcaption></figure>

Step 1 Disable the tamper function on the Control Panel (please refer to the Control Panel instruction manual). The bellbox will sound a beep to indicate the tamper switch is now disabled.

{% hint style="warning" %}
Note:

The tamper function will only turn OFF for one hour. The Control Panel will automatically turn the function back ON after the duration.
{% endhint %}

Step 2 Find a suitable location to mount the Bellbox.

Step 3 Remove the Top cover by loosening the bottom screw.

Step 4 Hold the Bellbox in the desired location; supply power to Bellbox.

Step 5 Check whether Bellbox has a strong enough signal with the Control Panel by putting the Control Panel into **Walk Test** mode (please refer to the Panel’s manual). Press the **Learn Button to** check whether the signal is strong enough (please refer to the Panel’s manual for signal strength).

Step 6 If you are satisfied with the signal strength, identify the 3 mounting holes and mount the Bellbox on the wall with the large screws and wall plugs provided. Make sure the Tamper Switch is fully depressed against the wall

{% hint style="warning" %}
Note:

The tamper switch protrudes through the back of the unit. When the Bellbox is pulled off the wall, the alarm will be activated. Ensure it is fully depressed when the Bellbox is mounted. If there is a gap, pack with suitable spacing material.
{% endhint %}

Step 7 Re-place the Top cover and tighten the bottom screw.

Step 8 Enable the tamper function from the Control Panel (please refer to the Panel’s manual).

Step 9 Check if the installation is successful by arming and disarming the system from the Control Panel.

Successful arming/disarming is indicated by the table provided in **Audio & Visual Status Indication**.

{% hint style="warning" %}
Note:

If 5 short-beeps are noticed while arming/disarming, it means the tamper is not fully depressed. Check the tamper and ensure it is properly set and test again from Control Panel.
{% endhint %}

Step 10 The installation is now completed.

### Changing the Battery

<table data-header-hidden><thead><tr><th width="115"></th><th></th></tr></thead><tbody><tr><td>Step 1</td><td>Disable the tamper detection from the Control Panel (please refer to the Control Panel’s manual). The Bellbox will sound a beep to indicate the tamper switch is now disabled.</td></tr><tr><td>Step 2</td><td>Loosen the bottom screw and detach the top cover carefully.</td></tr><tr><td>Step 3</td><td>Slide battery switch to the off position.</td></tr><tr><td>Step 4</td><td>The battery compartment has a lid secured by 2 screws. Undo the screws and open the lid.</td></tr><tr><td>Step 5</td><td>Remove the old batteries and press the Tamper Switch a couple times to fully drain the residual energy.</td></tr><tr><td>Step 6</td><td>Insert new batteries into the battery compartment.</td></tr><tr><td>Step 7</td><td>Slide the battery switch to ON position. All LEDs will flash once and the buzzer will emit 1 beep as the Bellbox powers on.</td></tr><tr><td>Step 8</td><td>Re-place and screw the battery compartment lid.</td></tr><tr><td>Step 9</td><td>Re-place and secure the top cover by tightening the bottom screw.</td></tr><tr><td>Step 10</td><td>Enter the Control Panel’s Sound/Siren setting webpage to enable the tamper function. The Bellbox will sound a beep to indicate the tamper switch is now activated.</td></tr></tbody></table>

### Factory Reset

The Bellbox can be reset and memory contents cleared. Whenever the Bellbox is removed from the Control Panel, it should be put to factory reset to clear its Control Panel memory, otherwise the Bellbox will still raise alarm if it receives alarm signal from panel.

<table data-header-hidden><thead><tr><th width="86"></th><th></th></tr></thead><tbody><tr><td>Step 1</td><td>Disable the tamper detection from the Control Panel (please refer to the Panel’s manual). The Bellbox will sound a beep to indicate the tamper switch is now disabled.</td></tr><tr><td>Step 2</td><td>Remove the Bellbox from Control Panel device list (please refer to the Control Panel’s manual).</td></tr><tr><td>Step 3</td><td>Loosen the bottom screw and detach the top cover.</td></tr><tr><td>Step 4</td><td>Slide the battery switch to the OFF position.</td></tr><tr><td>Step 5</td><td>Press and hold the Learn Button and slide the battery switch to ON position. Continue to hold the Learn Button for 7 seconds. Release the Learn Button when you hear 2 short beeps and a long beep. The previous parameters in the Bellbox will be cleared and it will return to normal mode.</td></tr></tbody></table>

{% hint style="warning" %}
Note:

Whenever the Bellbox is removed from the Control Panel, it should be put to factory reset as well to clear its Control Panel memory.
{% endhint %}
