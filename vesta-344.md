# VESTA-344

**WGT-1-Combo**

## WIEGAND 26 CONTROLLER

<figure><img src=".gitbook/assets/image (6) (1) (1) (1) (1) (1).png" alt=""><figcaption></figcaption></figure>

WGT-1-COMBO is a WIEGAND module that can be connected to HIKVISION Card Reader to covert WIEGAND 26 \[W26] Protocol into RF wireless signals or BUS wired signals. When WIEGAND Card Reader reads a tag for arming/disarming request, WGT-1-COMBO will transmit ARM/Disarm signal with the tag number to the Control Panel.

![](<.gitbook/assets/1 (6).png>)

## _**Identifying the parts**_

1. **Pluggable BUS Terminal**
2. **LED Indicator**

&#x20;      The LED flashes for once after powering on.

&#x20;       The LED flashes for 3 times when pressed the learn button and is transmitting RF signal

3. **Learn Button**
4. **Terminal Resistor Jumper Switch**

When the WIEGAND module is connected as the furthest BUS device on a BUS line, please set the WIEGAND module's terminal resistor jumper and the first BUS device’s (usually the Hybrid Panel’s) terminal resistor jumper to ON to serve as terminating resistors. The connected BUS line’s communication ability will be enhanced.

* If the jumper is OFF (if the jumper link is removed or “parked” on one pin), the communication ability is in normal level.
* If the jumper is ON, the communication ability will be enhanced.

5. **DC 12V Input / GND**

Connect to 12V 1A power supply.

6. **DC 12V Output / GND**

Provide 12V DC@150mA to the connected HIKVISION Card Reader.

7. **DATA0**

&#x20;        Connect to W0 of HIKVISION Card Reader.

&#x20;        **DATA1**

&#x20;       Connect to W1 of HIKVISION Card Reader.

8. **Wiring Hole**
9. **Base Screws x 4**
10. **Mounting Holes x 2 (for Mounting Bracket)**
11. **Mounting Bracket**

## _**Power**_

**Powered by Hybrid Panel (For BUS wired application only)**

* When WGT-1-COMBO is in wired mode (hardwired to Hybrid Panel), 13.5V (typical) power supply will be provided by the Hybrid Panel.

**Power Adapter Application (Required for wireless application; Optional for wired application)**

* When WGT-1-COMBO is in wireless mode (NOT wired to Hybrid Panel), please power on the WGT-1-COMBO by connecting the two-wired 12V AC-DC Adaptor to the **DC IN / GND** terminal.
* When WGT-1-COMBO is in wired mode (hardwired to Hybrid Panel), but the panel is connected to loads that require heavier power draw, it is recommended to use two-wired 12V AC-DC Adaptor.

**Power Output:**

* WGT-1-COMBO can supply 12V, 150mA power to connected HIKVISION Card Reader via the power terminal.

## _**Application Diagram**_

* The insertion holes’ wiring specification is AWG 20-28 or Ø 0.518-0.081 (mm²). When connecting wire to terminal, tighten the screw to close the clipper and hold wire in place. Unscrew to open the clipper and remove the wire.
* The WGT-1-COMBO can be connected for either wireless application or wired application according to the diagrams below:

1. **RF Wireless Application (**&#x4E;OT wired to Hybrid Pane&#x6C;**)**

* Before wiring, make sure the power supply has been disconnected.
  * Connect **GND** terminal of WGT-1-COMBO to the Ground terminal of a Power Supply.
  * Connect **DC IN** Input terminal of WGT-1-COMBO to the Power Output terminal of the Power Supply.
  * Connect **DC OUT** terminal of WGT-1-COMBO to the **red cable** of HIKVISION Card Reader.
  * Connect **GND** terminal of WGT-1-COMBO to the **black cable** of HIKVISION Card Reader.
  * Connect **DATA0** terminal of WGT-1-COMBO to the **green cable (W0)** of HIKVISION Card Reader.
  * Connect **DATA1** terminal of WGT-1-COMBO to the **white cable (W1)** of HIKVISION Card Reader.

![](<.gitbook/assets/5 (5).png>)

2. **BUS Wired Application (**&#x68;ardwired to Hybrid Pane&#x6C;**)**

* Before connecting the WIEGAND module to the system bus, please switch the power off.
* To assist with cable connections, the terminal blocks on each BUS system module are color-coded.

![](<.gitbook/assets/6 (1) (1) (1) (1) (1) (1) (1) (1) (1).jpeg>)

| **Red**    | VDD  |
| ---------- | ---- |
| **Black**  | GND  |
| **Yellow** | 485A |
| **Green**  | 485B |

* Connect **DC OUT** terminal of WGT-1-COMBO to the **red cable** of HIKVISION Card Reader.
* Connect **GND** terminal of WGT-1-COMBO to the **black cable** of HIKVISION Card Reader.
* Connect **DATA0** terminal of WGT-1-COMBO to the **green cable (W0)** of HIKVISION Card Reader.
* Connect **DATA1** terminal of WGT-1-COMBO to the **white cable (W1)** of HIKVISION Card Reader.
* Incorrect connections will result in failure or improper operation. Inspect wiring and ensure proper connections before applying power.
* Power on the panel, the WGT-1-COMBO will be powered on as well.

![](<.gitbook/assets/7 (1) (1) (1) (1) (1) (1) (1).jpeg>)

{% hint style="warning" %}
Note:

* The pluggable design of BUS terminal blocks improves upon installation efficiency. Before wiring, you can remove the terminal blocks from the PCB board for ease of use, and plug in again after wiring.
* After unplugging the terminal, when re-installing the terminal back to the board, make sure to install the terminal in the same direction to avoid potential hazards
{% endhint %}

* The WIEGAND module can be connected in series with other BUS devices to the Hybrid Panel. When connected to **VBUS** terminal without connection to **DC IN**, the total length of wiring shall not exceed 300 feet. When connected to **DC IN**, the total length of wiring can be up to 3000 feet.
* For optimal communication of the connected BUS line devices, ensure the terminal resistor jumper switches of the first and the furthest BUS devices on a BUS line are set to ON to serve as terminating resistors. Be sure to only enable the aforementioned 2 jumper switches, and do not set the jumper switches to ON for any other BUS devices in between.

## _**Learning WGT-1-COMBO into the Control Panel**_

**Step 1.** Put Control Panel into Learning Mode.

**Step 2.** **(For Wireless Application)** Press the learn button of the WGT-1-COMBO. The WIEGAND module will transmit a learning signal to the Control Panel. If the Control Panel successfully receives the learning signal, the WGT-1-COMBO will be displayed in the Control Panel as tag reader.

**(For BUS Wired Application)** If the WGT-1-COMBO is properly connected to the Panel, it will be automatically displayed in the Control Panel as tag reader.

**Step 3.** Refer to the Control Panel manual to complete the learn-in process.

**Step 4.** Navigate the Control Panel into “**Walk Test**” mode. Hold the WGT-1-COMBO in the desired location, press the learn button on the WIEGAND module to confirm this location is within signal range of the Control Panel.

![](<.gitbook/assets/9 (5).png>)

## _**Identification (For BUS Wired Application)**_

The “**Identify**” function is used to localize a specific BUS device in the BUS wired system. This function is helpful in distinguishing which device is which especially in a large installation where numerous BUS devices are included.

To locate the WIEGAND module in the BUS system:

**Step 1.** On Hybrid Panel’s webpage, click “Identify” under the device list after the Tag Reader’s device column entry.

**Step 2.** If the tag reader receives the signal from the Hybrid Panel, the webpage will display a success message and WGT-1-COMBO’s LED indicator will flash 10 times to indicate where it is to the user.

{% hint style="warning" %}
Note:

If a timeout message is displayed on the webpage, it means the WIEGAND module did not receive the signal from the Panel. Please check whether the WIEGAND module is connected properly to the Panel with appropriate wiring distance.
{% endhint %}

## _**Walk Test**_

* To make sure the WIEGAND module is able to communicate with the Panel after it is learned-in, place the Control Panel in Walk Test mode and press the learn button on WGT-1-COMBO to transmit a test signal to the Control Panel.
* When the Panel receives the test signal, it will beep once and display the WIEGAND module’s information accordingly on the top of the device list.

{% hint style="warning" %}
Note:

If there is no response from the Panel after the press of learn button, it means the Panel did not receive the test signal from the device. Please check whether WGT-1-COMBO is connected properly to the Panel within appropriate wiring distance.
{% endhint %}

## _**Tag Learning / Removal**_

* Before learning a tag into the Control Panel, make sure the WGT-1-COMBO has been learned into the Control Panel.
* After first power on HIKVISION Card Reader, please wait until the buzzer sound a beep, indicating that the starting up process is completed.

**Tag Learning**

**Step 1.** Disarm the system.

**Step 2.** Go to the **Local webpage** > **PIN Code**. Select the **Area**. Pass tag **two times** through the HIKVISION Card Reader in **less than 4 seconds**, two beeps will be emitted by the card reader, and then WGT-1-COMBO will transmit signal with the tag number to the Control Panel. Click **Load** button on the webpage.

![](<.gitbook/assets/14 (6).png>)

**Step 3.** When the tag ID number is shown on the webpage, enter a 4-digit or a 6- digit User Code and assign a user name for the tag.

![](<.gitbook/assets/15 (6).png>)

**Step 4.** Click **OK** button on the webpage to save.

**Step 5.** Tag learning is complet&#x65;**.**

## **Tag Removal**

**Step 1.** Disarm the system.

**Step 2.** Go to the **Local webpage** > **PIN Code**. Select the **Area**. Pass tag **two times** through the HIKVISION Card Reader in **less than 4 seconds**, two beeps will be emitted by the card reader, and then WGT-1-COMBO will transmit signal with the tag number to the Control Panel. Find a blank tag number row and click Load button to check the tag ID number you are going to delet&#x65;**.**

![](<.gitbook/assets/16 (6).png>)

**Step 3.** According to the newly loaded tag ID number, find the same tag ID number on the list and select **Delete**.

* **Example:** As the picture shown below, No. 1 & No. 2 on the list are the existing learned tags. After you pass tag **two times** through the Card Reader and click **Load** button in the blank No.3 row, the tag ID number will be shown in No. 3. As No.3 is the same as No.2, so No.2 is the tag to be removed. Select **Delete** on the No.2 row to remove the tag.

![](<.gitbook/assets/17 (5).png>)

**Step 4.** Click **OK** on the webpage to save the change.

**Step 5.** The removal of tag is complete.

## _**Supervision Signal**_

* When in wired mode, the WIEGAND module will automatically transmit Supervision Signals to the Control Panel at an interval of 20-30 seconds.
* When in wireless mode, the WIEGAND module will automatically transmit Supervision Signals to the Control Panel at an interval of 30-50 minutes.
* If the Control Panel has not received the signal from the WIEGAND module for a preset period of time, the Control Panel will consider the WIEGAND module out of order and react according to panel setting.
* **To Arm the System:** Pass tag **one time** through the HIKVISION Card Reader, a beep will be emitted by the card reader. After 4 seconds, WGT-1-COMBO will transmit ARM signal with the tag number to the Control Panel. If the Control Panel confirms the tag is attached to the user, it will automatically switch to Arm Mode.
* **To Disarm the System:** Pass tag **two times** through the HIKVISION Card Reader in **less than 4 seconds**, two beeps will be emitted by the card reader, and then WGT-1-COMBO will transmit DISARM signal with the tag number to the Control Panel. If the Control Panel confirms the tag is attached to the user, it will automatically switch to Disarm Mode.

## _**Mounting**_

**Mount the Bracket**

**Step 1.** Secure the Mounting Bracket on the wall at desirable location.

**Step 2.** Use the holes as template, and drill holes into the surface.

**Step 3.** Screws the Mounting Bracket onto the holes drilled.

**Step 4.** Hook the WIEGAND module on the mounting bracket.

**Step 5.** Sliding down the WIEGAND module when hooked to the mounting bracket to tighten and secure the module.

<figure><img src=".gitbook/assets/10 (91).png" alt=""><figcaption></figcaption></figure>



## 🏠 How to Use Your Wiegand Card Reader for Arming/Disarming

Once you've successfully created a user by clicking the **Load** button and setting up your credential (tag/card), here's how to control your security system:

### 🔒 **To ARM Your System**

* **Simply swipe your card/tag ONCE** through the WIEGAND Card Reader
* You'll hear **one beep** 🔊 confirming the read
* After 4 seconds, the system will automatically switch to **ARM mode**
* Your security system is now **active and protecting** your property! ✅

### 🔓 **To DISARM Your System**

* **Swipe your card/tag TWICE** through the WIEGAND Card Reader **within 4 seconds**
* You'll hear **two beeps** 🔊🔊 confirming both reads
* The system will automatically switch to **DISARM mode**
* Your security system is now **disarmed** and you can move freely! ✅

### 💡 **Quick Tips:**

* ⏰ **Timing matters** - For disarming, both swipes must happen within 4 seconds
* 🎵 **Listen for beeps** - They confirm your card was read successfully
* 🏃‍♂️ **Wait a moment** - After arming, give the system 4 seconds to activate
* 🔋 **Keep your card handy** - Make sure it's working properly and not damaged

### ⚠️ **Important Notes:**

* Make sure your card/tag is properly learned into the system before use
* If you don't hear beeps or the system doesn't respond, try swiping again
* The system will only respond to cards that have been properly registered

**That's it! Simple one swipe to arm 🔒, double swipe to disarm 🔓**

Your Wiegand module will handle all the communication with your control panel automatically! 🚀
