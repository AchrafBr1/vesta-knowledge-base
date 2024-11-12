# VESTA-050

**Voice Recognition Alarm (VRA)**

The Voice Recognition Alarm (VRA) recognizes preset vocal commands or keywords and activates a Help alarm. In addition to voice activation, the VRA also features a large button for users to summon help during an emergency.

## **Parts Identification**

&#x20;                      **Front View**                                              **Back View**                                           **Side View**

![](<.gitbook/assets/0 (48).jpeg>)

1. **Help Button (with Blue Backlight)**
   1. Press once to send a learn code or activate a panic alarm
   2. Press and hold the button for 8 seconds to send a Cancel Code to the Control Panel.
   3. Blue backlight will flash when signal is transmitted to the Control Panel.
2. **LED Indicator (Green/Amber)**

* Green LED ON: When external power supply is connected.
* Green LED OFF: When external power supply is removed.
* Amber LED flashes for three times: Low battery status detected when powerd on.
* Amber LED flashes once every 5 seconds: Low battery status detected during operation.

3. **Microphone for VR (Voice Recognition)**
4. **Battery Compartment**
5. **DIP Switches**
6. **Keyhole**
7. **DC Jack (with Locking feature)**

Plug in a DC 5V power adpator and rotate it 90 degrees clockwise to the lock position. To remove the adaptror, rotate it 90 degrees counterclockwise to the original open position and remove it.

## **Power Supply**

* VRA can be powered by connecting to 5V DC power supply or two Type C batteries.
* When VRA is connected to 5V DC power supply, green LED will turn on. When DC power supply is removed, VRA will switch to using batteries (if batteries are already installed and not exhausted) and continue operation; green LED will turn off.
* When powered by Type C batteries, VRA will transmit any detected low battery status along with regular status signal transmissions to the Control Panel for display accordingly.
* When changing batteries, please remove the back cover by unscrewing the bottom fixing screw, and then inserting a flat-head screwdriver to lift the back cover. Remove the old batteries, and then press the Help Button twice to fully discharge before inserting new batteries.

## **Supervision Signal**

* After learned into the Control Panel, VRA will automatically transmit Supervision Signals every 30 to 50 minutes.
* If the Control Panel has not received the supervision signal from VRA for a preset period of time, the Control Panel will indicate that the Voice Recognition Alarm is out-of-signal range or is out of order.

## **Sensitivity**

* The voice recognition function has three sensitivity levels: high, medium, low. When sensitivity level is set to high, VRA will most easily detect keyword/command and trigger alarm.
* Please use a sharp tool to adjust the DIP Switch positions to set sensitivity level.

<table><thead><tr><th width="120">DIP</th><th width="100">DIP</th><th width="265">Search (Sensitivity Level)</th></tr></thead><tbody><tr><td><strong>Switch1</strong> </td><td><strong>Switch2</strong></td><td> </td></tr><tr><td>OFF</td><td>OFF</td><td>Low</td></tr><tr><td>ON</td><td>OFF</td><td>Medium</td></tr><tr><td>OFF</td><td>ON</td><td>High</td></tr><tr><td><strong>DIP</strong></td><td><strong>DIP</strong></td><td><strong>Function</strong></td></tr><tr><td><strong>Switch3</strong></td><td><strong>Switch4</strong></td><td>Reserved</td></tr></tbody></table>

<div align="left">

<figure><img src=".gitbook/assets/image (1).png" alt=""><figcaption></figcaption></figure>

</div>

_\<NOTE>_

* After Dip Switch settings are changed, please disconnect power supply (both external power supply and batteries must be removed) and then re-connect power to VRA. VRA will

work with newly set sensitivity level after re-powered on.

## **Getting Started**

* Remove the back cover by unscrewing the bottom fixing screw, and then inserting a flat-head screwdriver to lift the back cover.
* Based on your needs, set Sensitivity Switch as shown in Dip Switch Position Table.
  * Power on the Voice Recognition Alarm by connecting to 5V DC power supply or two Type C batteries.
  * Put the Control Panel into learning mode
  * Press the button on the Voice Recognition Alarm to transmit a learn code.
  * Refer to your Control Panel’s operation manual to complete the learn-in process.
  * Replace the back cover.

## **Walk Test**

* After VRA is successfully learned in, place the Control Panel in the walk test mode, then press the button on VRA to confirm that this location is within signal range of the Control Panel. Refer to Control Panel manual to complete Walk Test.
* **Operation**
  * After VRA is learned in successfully, pressing the button once will activate a Help Alarm. When the button is pressed, VRA will emit one beep.
  * The User can also speak the specific vocal command to activate a Help Alarm. When trigger words are recognized, VRA will emit one long beep.
  * Trigger words could be “SARA Alarm (German)”, or “Help Me (English)”, depending on firmware version. "SARA Alarm (German)”should be spoken twice within 5 seconds to trigger alarm, while “Help Me (English)”only needs to be spoken once to activate alarm.
* Pressing and holding the Button for 8 seconds or more will send a Cancel Code to the Control Panel to stop the alarm.

&#x20;                                                                      **Ways to Seek Help**

![](<.gitbook/assets/3 (55).png>)

&#x20;                                                                               **OR**

&#x20;           **Speak the trigger Keyword.**                                      **Press the Help Button.**

_\<NOTE>_

* To ensure voice recognition accuracy, please avoid installing VRA in a large or noisy room.
* The ideal environment for voice recognition is silence or partial silence. If you call out the vocal command with normal voice, please speak within 2 meters of VRA to ensure alarm trigger.
* The voice recognition function has three sensitivity levels. You may test with them and select the level that best suits your mounting location.

## **Installation**

After you conduct Walk Test to confirm VRA is within signal range of the Control Panel, and you are satisfied that the selected sensitivity level works in the chosen location, you can proceed with installation. There are two ways to install VRA: Wall Mounting and Surface Deployment.

### **Wall Mounting**

Ensure that VRA is fitted at approximately chest height (around 130cm-150cm above ground) where the button can be easily accessed and operated.

1. Identify the keyhole on the back of VRA, drill one hole on the wall and fit the provided wall plug (Figure 1). Fit the fixing screw and leave the non-threaded part for hanging VRA, as shown in Figure 2.

&#x20;                                                 Figure 1                                                           Figure 2

<figure><img src=".gitbook/assets/Imagen vesta-050.png" alt=""><figcaption></figcaption></figure>

1. Fit the keyhole slot of VRA over the screw head. Gently and firmly push VRA downwards, as shown below. (Figure 5,6)

&#x20;                          Figure 5                                                                                 Figure 6

<figure><img src=".gitbook/assets/image (3).png" alt=""><figcaption></figcaption></figure>

### **Surface Placement**

VRA comes with an Anti-Slip pad on its back. The device can also be deployed on a flat surface without being installed at a fixed location.

![](<.gitbook/assets/9 (37).png>)

