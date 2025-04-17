# VESTA-092

**VRCP-DECT**

## &#x20;**Voice Extender**

VRCP-DECT is a Voice Extender that enables users to summon emergency help with voice recognition command or a single button press. VRCP-DECT has built-in voice recognition and can activate an emergency call to CMS by preset vocal commands or keywords. It is suitable for senior and medical care, multi-storied homes, and larger premises.

## _**Identifying the parts:**_

![](<.gitbook/assets/0 (56).jpeg>)

1. **ALARM Button**
   * Press the button for help and to open two-way communication.
   * Press and hold the button for 5 seconds during Two-Way communication to request the Control Panel to terminate communication. The Control Panel will end the communication or not depending on user settings.
2. **Red LED**
   * On: VRCP-DECT has not been learned into the control panel.
   * Flashes every 5 seconds: Low Battery
   * 3 sec On, 3 sec Off: AC Fault
   * Flashes twice: Learning successful
3. **Green LED**
   * On: VRCP-DECT is being learned into control panel VRCP-DECT is under two-way communication
4. **Speaker**
5. **Microphone for VR (Voice Recognition)**
6. **Microphone for two-way communication**
7. **DC jack**
   * DC 9V 1A SPS power adapter connection
8. **Test/Learn-in button**

* Press and hold the button for 3 seconds until VRCP-DECT emits 1 long beep to indicate it has entered learning mode.

9. **Battery switch**
10. **DIP Switches**
11. **Mounting holes**
12. **Triangle mark**
    * The triangle mark should point straight up when the bracket is fixed on the wall.

## _**Power Supply:**_

The Voice Extender can be powered by either AC power or battery.

**AC Power:** A DC 9V 1A SPS power adapter is provided for AC power connection.

* When AC power is disconnected, the Red LED will turn on/off every 3 seconds to indicate AC fault. DECT will be turned off to save battery power.
* After AC power is restored, the Red LED will turn off to indicate AC fault restore. DECT will be turned on again and reconnected to the Control Panel.

**Battery:** When AC power is disconnected, VRCP-DECT will switch to using rechargeable battery pack inside.

* When battery voltage is low, VRCP-DECT will send a low battery signal to the Control Panel to notify the situation.
* Low battery condition will be restored 12 hours after AC Power is supplied to VRCP-DECT. VRCP-DECT will also send a Low Battery Restore signal to the Control Panel.
* If the battery switch is set as OFF, the battery will not be charged when AC power is connected and nor will it serve as a backup power source when AC power is missing. You need to switch the battery to ON for it to be charged when AC power is connected and serve as a backup power source when AC power is missing.

## _**Supervisory Signal**_

* After installation, the VRCP-DECT will automatically transmit Supervisory signal to the Control Panel every 24 hours.

## _**Voice Recognition Sensitivity**_

* The voice recognition function has three sensitivity levels: high, medium, low. When sensitivity level is set to high, VRCP-DECT will most easily detect keyword/command and trigger alarm.
* Please use a sharp tool to adjust the DIP Switch positions to set sensitivity level.

<div align="left"><figure><img src=".gitbook/assets/image (102).png" alt=""><figcaption></figcaption></figure></div>

| DIP      | DIP     | Search (Sensitivity Level) |
| -------- | ------- | -------------------------- |
| Switch1  | Switch2 |                            |
| OFF      | OFF     | Low                        |
| ON       | OFF     | Medium                     |
| OFF      | ON      | High                       |

{% hint style="warning" %}
Note:

After Dip Switch settings are changed, please disconnect power supply (both external power supply and batteries must be removed) and then re-connect power to VRCP-DECT. VRCP-DECT will operate with new sensitivity setting after re-powered on.
{% endhint %}

## _**Learning Procedures:**_

Step 1. Open Panel webpage and start with learning mode. Please refer to the Control Panel manual for details.

Step 2. Press and hold VRCP-DECT’s learning button for 3 seconds until you hear a long beep and release the button. VRCP-DECT will enter learning mode for 30 seconds. The Green LED will be ON during learning mode.

Step 3. When the Control Panel receives the signal from VRCP-DECT, it will display the information accordingly. If the device you wish to learn into already exists in the system, the device information will be displayed in the Learned Device section. If not, the device information will be displayed in the Detected Device section.

Step 4.VRCP-DECT will emit two beeps to indicate successful learning upon receiving acknowledgement from the Control Panel.

Step 5. Click “Add” on webpage to include selected device into panel.

{% hint style="warning" %}
Note:

If VRCP-DECT does not receive acknowledgement from the Control Panel during the 30-second learning mode, it will emit one low-tone beep to indicate that learning has failed and exit learning mode. The Green LED will turn off, and the Red LED will turn on. Please perform the learning steps again.
{% endhint %}

## _**Operation:**_

### **Emergency Report**

* When you press the **ALARM** button or speak the specific vocal command, an emergency report will be sent and a Two-Way communication will be established according to the duration set in your Control Panel. The Green LED will light up during the communication.
* Trigger words could be “SARA Alarm (German)”, “SARA Help (English)”, or “Help Me (English)”, depending on firmware version. "SARA Alarm (German)”should be spoken twice within 5 seconds to trigger alarm, while “SARA Help (English)” or “Help Me (English)” only needs to be spoken once to activate alarm.

&#x20;                                                                         **Ways to Seek Help**

![](<.gitbook/assets/3 (60).png>)

&#x20;                                                                                       **or**

* VRCP-DECT will end the call when the time expires. The Green LED will turn off.
* During Two-Way communication, you can <mark style="background-color:yellow;">press and hold the ALARM button for 5 seconds</mark> to request the Control Panel to terminate communication The Control Panel will terminate two-way communication or not depending on user settings.

![](<.gitbook/assets/4 (57).png>)

{% hint style="warning" %}
Note:

When the Callback option is enabled on the Control Panel, Green LED will stay on, after the call has been terminated. Green LED will turn off when the Callback timer has ended. Please refer to Control Panel manual for more details on Callback feature.

When the VRCP-DECT cancel function is enabled on the Control Panel, pressing the button on VRCP-DECT will end 2-way communication. When the VRCP-DECT cancel function is disabled, pressing the button on VRCP-DECT will not end 2-way communication.

To ensure voice recognition accuracy, please avoid installing VRCP-DECT in a large or noisy room.

The ideal environment for voice recognition is silence or partial silence. If you call out the vocal command with normal voice, please speak within 2 meters of VRCP-DECT to ensure alarm trigger.

The voice recognition function has three sensitivity levels. You may test with them and select the level that best suits your mounting location.
{% endhint %}

## **Alarm Report triggered by other devices**

* When an alarm is triggered by a device learned in the Control Panel, and “808RV” is selected for Two-Way On function on that Device webpage, a Two-Way communication will be automatically started with VRCP-DECT without any button press.

{% hint style="warning" %}
Note:

This function of automatically picking up call and opening two-way communication is only available when AC power is connected to VRCP-DECT.

If AC power is disconnected from VRCP-DECT, DECT will be turned off, VRCP-DECT will not be able to pick up call, and two-way communication will be started with GX instead.
{% endhint %}

![](<.gitbook/assets/5 (58).png>)

### **Incoming Call**

* When there is an incoming call, pressing the ALARM button on VRCP-DECT will pick up the call.

## _**Mounting VRCP-DECT**_

After the VRCP-DECT is successfully learned-in, and you have conducted Walk Test to confirm the device is within signal range of the Control Panel, also you are satisfied that the selected sensitivity level works in the chosen location, you can proceed with installation. The VRCP-DECT can be mounted on the wall or deployed on a flat surface.

### **Wall Mounting**

Ensure VRCP-DECT is fitted at approximately chest height where the button can be easily accessed and operated.

1. Break through the 2 knockouts on the Wall Mounting Bracket.
2. Use the 2 holes as a template to mark off the holes’ positions. Make sure that the triangle symbol on the bracket points straight up.
3. Drill 2 holes and screw the bracket onto the wall.
4. Connect a DC 9V 1A SPS power adapter to DC jack and keep the cable well-placed

![](<.gitbook/assets/6 (40).jpeg>)

5. Fit VRCP-DECT onto the mounting bracket. Make sure the imprinted mark on VRCP-DECT must be aligned with the upper mark on the bracket.
6. Rotate VRCP-DECT clockwise to the lock position.

![](<.gitbook/assets/7 (36).jpeg>)

### **Surface Placement**

The VRCP-DECT can be deployed on a flat surface without being installed at a fixed location.

1. Clean the back of VRCP-DECT with degreaser.
2. Connect DC 9V 1A SPS power adapter to DC jack and keep the cable well-placed to the right or left. (**Picture 1**)
3. Remove the paper backing of Anti-Slip pad and apply to the back of VRCP-DECT. (**Picture 2**)
4. Place VRCP-DECT at desired location. (**Picture 3**)

&#x20;                 **Picture 1**                                                **Picture 2**                                                      **Picture 3**

![](<.gitbook/assets/8 (40).png>)
