# VESTA-224

**WEZC-8**

## &#x20;**Series Expansion Module**

<figure><img src=".gitbook/assets/image (10) (1).png" alt=""><figcaption></figcaption></figure>

## **Introduction**

This installation guide shall be used in conjunction with the Hybrid Panel’s user’s manual, to which the WEZC-8 Series model is connected to.

The WEZC-8 Series Expansion Module is designed to support expansion for the Hybrid Panel. Connected to the Hybrid Panel via BUS connection, it can provide the expansion of up to 8 zones on the compatible panels. The WEZC-8 Series is equipped with its own enclosure case, which has tamper protection and LED status indicators.

**WEZC-8 Series Expansion Module includes the following models:**

**WEZC-8** – Expansion Module with 8 wired zones

**WEZC-8B** – Expansion Module with 8 wired zones and rechargeable battery pack

## **Identifying the Parts**



![Front View Back View](<.gitbook/assets/0 (7).jpeg>)



![Internal View](<.gitbook/assets/1 (9).jpeg>)

1. **Power LED (Red)**

&#x20;     On – Powered by a 12V power adapter or Hybrid Panel.

&#x20;     Off – When the power is off, or when powered by rechargeable battery.

2. **Zone 1\~8 LED (Red)**

The corresponding Zone LED will light up when certain zone(s) is/are triggered or has/have tamper or masking condition.

3. **Transmission LED (Red)**

Lights up when connection or signal transmission is normal between the Expansion Module and Control Panel.

4. **Breakaway Area**

When the expansion module is forcibly removed from the mounting location, the area will be detached, causing the tamper switch to be activated.

5. **Tamper Switch (For Wall Mounting)**

The expansion module is protected by the tamper switch against any unauthorized removal from the mounting location.

6. **Mounting Holes**
7. **Wiring Hole**
8. **Battery Connection Terminal (for WEZC-8B only)**

For connecting the rechargeable battery pack to the PCB.

9. **Rechargeable Battery Pack (for WEZC-8B only)**
10. **Terminal Resistor Jumper Switch (J3)**

When the Expansion Module is connected as the furthest BUS device on a BUS line, please set the Expansion Module’ terminal resistor jumper and the first BUS device’s (usually the Hybrid Panel’s) Jumper Switch to ON to serve as terminating resistors. The connected BUS line’s communication ability will be enhanced.

Turn the jumper to OFF by removing the jumper link or ―parking‖ the jumper link on one pin.

![](<.gitbook/assets/2 (10).jpeg>)

Turn the jumper to ON by resting the jumper link on both pins.

![](<.gitbook/assets/3 (9).jpeg>)

**11. DC Jack**

For DC 12V switching power connection.

To supply stable and sufficient power to charge the rechargeable batteries for WEZC-8B, it is strongly recommended to use a 12V/1A switching power adaptor.

12. **Pluggable BUS Terminal**
13. **Zone Terminal & 13.5V Auxiliary Voltage Output Terminal & GND Terminal**

The typical voltage is 13.5V, and it might vary depending on the output voltage of the terminal.

**14. Test Button**

Press the test button to send a test signal to the Control Panel.

15. **Reset Button (Reserved for Internal Use)**
16. **Tamper Switch (For Case Cover)**

The expansion module is protected by the tamper switch against any unauthorized case opening. Whenever the case cover is opened, the tamper switch will be activated.

## **Power Supply**

* The expansion module is powered by the Hybrid Panel, which can provide 13.5V power source to the expansion module. Additionally, it is recommended to use the external power adaptor (12V) when connected to loads that require heavier power draw.
* When the power supply from the adaptor is interrupted and restored, the expansion module will transmit an AC failure signal and a restore signal respectively to the Control Panel.

### **Rechargeable Battery Pack (for WEZC-8B only)**

* For WEZC-8B, a Ni-MH rechargeable battery pack is pre-installed in the Expansion Module to serve as a backup in case of a power failure.
* Please connect the battery pack to the PCB manually to use it as a backup power source and/or to charge it automatically when power is connected from the adaptor or Hybrid Panel. \<Note> Before connecting the battery pack, make sure the power of DC Jack and/or BUS terminal is/are switched off.

It is strongly recommended to use a 12V/1A switching power adaptor to supply stable and sufficient power to charge the batteries.

* When the rechargeable battery pack is low in power, the expansion module will transmit a low battery signal to the Control Panel. When the batteries have been charged, it will also transmit a battery restore signal to the Control Panel.

## **Tamper Protection**

WEZC-8 Series has two Tamper Switches; each comes with a different function.

* The Tamper Switch for case cover is located at the front of the board. It is in normal position when the case is closed. Tamper violation happens when the case is opened where Tamper Switch is released (Tamper Opened).
* The Tamper Switch for wall mounting is located at the back of the board. It is in normal position when the module is well mounted on the wall. Tamper violation happens when the module is forcibly removed from the mounting location; the breakaway area will be detached, causing the tamper switch to be activated.
* The tamper is considered as triggered if any one of the tamper is opened. The Tamper is only considered restored when both tampers are in closed state.

## **Supervisory Signal**

* After being learnt in to the Control Panel, the Expansion module will automatically transmit Supervisory Signals every 20 to 30 seconds.

## **Connection to the Hybrid Panel**

* Before connection, make sure the power supply has been disconnected, and the panel battery switch has been slid to OFF position.
* To assist with cable connections, the terminal blocks on each system module are color-coded.

<figure><img src=".gitbook/assets/1 (135).png" alt=""><figcaption></figcaption></figure>

* For optimal communication of the connected BUS devices, ensure the furthest BUS device’s

Terminal Resistor Jumper Switch and Control Panel’s J53 Jumper Switch are set to ON to serve as terminating resistors. Be sure to only enable the aforementioned 2 jumper switches, and do not set the jumper switches to ON for any other BUS devices in between.

* The WEZC-8 series can be connected to and powered by either the Control Panel via the BUS terminal or the external power via the 12V adaptor. If the expansion module is using external power, be sure to bypass the red VDD terminal on the Control Panel using the Wago 221 Splicing Connector.
* The following is WEZC-8 connected to and being powered by the Hybrid Panel:

![](<.gitbook/assets/4 (8).jpeg>)

* The following is the connection of WEZC-8B to the Hybrid Panel, with WEZC-8B being powered by external power source.

![](<.gitbook/assets/5 (7).jpeg>)

{% hint style="warning" %}
Note:

* _Be sure to bypass the red VDD terminal on the Control Panel using the provided Wago 221 Splicing Connector. Connect the VDD terminal to the next BUS device (VST-892-BUS as example) that is powered by Hybrid Panel._
* _The pluggable design of BUS terminal blocks improves installation efficiency. Before wiring, you can remove the terminal blocks from the device for ease of use, and plug in again after wiring. When re-installing the terminal blocks back to the board, make sure to install them in the same direction to avoid potential hazards._
* _Incorrect connections will result in failure or improper operation. Inspect wiring and ensure proper connections before applying power._
{% endhint %}

## **Zone Wiring**

* The 8 zones can be wired to supervise NC (normally close) or NO (normally open) devices, e.g., PIR sensors, door contacts, smoke detectors, water sensors, fire sensors, CO sensors, gas detectors, heat detectors, and glass break detectors, etc.
* Connect hardwired devices into any Zone terminal.
* Wire gauge: Minimum 22 AWG, maximum 19 AWG. Do not use shielded wire.
* The hardwired zones support Single-End-of-Line (SEOL), Double-End-of-Line (DEOL) loop configuration, with selectable resistor values of 1KΩ, 2.2KΩ, 3.74KΩ, 4.7KΩ, 5.6KΩ, 6.8K Ω, 8.2KΩ, 10KΩ ohms.
* Triple end-of-line (TEOL) loop can be configured in different combinations: 4.7KΩ, 6.8KΩ,

12KΩ (resistor value selection: 6.8K), 4.7KΩ/5.6KΩ, 4.7KΩ, 2.2KΩ/3KΩ (resistor value

selection: 4.7K), or 4.7KΩ/5.6KΩ, 5.6KΩ, 2.2KΩ/3KΩ (resistor value selection: 5.6K).

* Please install the resistor(s) at the end of each zone loop far away from the Control Panel. The Panel will detect if the circuit is secure, open, or short.
* For an NC loop, please have an EOL resistor in series with the loop.
* For an NO loop, please have an EOL resister in parallel (across) the loop. Please refer to the following diagrams for wiring examples.
* If a zone wiring method is changed, be sure to turn the system power off and back on again to avoid triggering the alarm.

Please refer to the following diagrams of loops 1 to 10 for wiring examples.

### **NO/NC Wiring**

The panel can detect alarm for corresponding NO or NC devices via the open, secure or shorted circuits.

{% hint style="warning" %}
Note:

There is no EOL resistor in loop 1 and loop 2
{% endhint %}

**NO/NC Wiring**

![1](<.gitbook/assets/6 (7).jpeg>) ![2](<.gitbook/assets/7 (7).jpeg>)

#### **Single-End-of-Line Resistor Wiring**



![3                                                                                                                                             4](<.gitbook/assets/8 (10).png>)

![5                                                                                                                                        6](<.gitbook/assets/9 (14).png>)

#### **Double-End-of-Line Resistor Wiring**

![7                                                                                                                                               8](<.gitbook/assets/10 (15).png>)

#### **Triple-EOL Wiring**

![9                                                                                                                            10](<.gitbook/assets/11 (11).png>)

## **Getting Started**

After connecting the expansion board to the Hybrid Panel, and completing device wiring, please proceed to learning and zone programming.

### _**Learning**_

**Step 1.** Connect the Expansion Module to the Control Panel. Then, power on the Control Pane&#x6C;**.**

**Step 2.** Click on ―**Learning**‖ to enter learn page.

**Step 3.** Click on ―**Start**‖ to enter learning mode.

**Step 4.** Click **“Add”** to include the Expansion Module into panel.

**Step 5.** If the Expansion Module is successfully learnt into the system, the added device will be displayed in the ―Learned Device‖ section. The Device Type will be shown as ―Expander‖.

### _**Wired Zone Programming**_

After the expansion module is added, proceed to wired zone programming.

**Step 1.** Click Wired Sensor to enter this webpage. You will see the Expanders at the bottom of the page.

**Step 2.** Click ―Edit‖ at end of expander entry.

**Step 3.** Edit the type of the wired sensor, zone wiring, and the EOL resistance for each zone.

* **Type**: Select the type of the wired sensor for each zone from the drop down menu.
* **Loop**: Select the number to correspond to the zone wiring for each zone from the drop down menu. On this web page, there are wiring diagrams below for your reference.
* **Resistor**: Select the resistance for the zone wiring.
* **Status**: The status of each zone — Restore, Tamper, or Trigger — will be shown here.

**Step 4.** Click ―**OK**‖ to save changes when finished. Alternatively, click ―**Rese**t‖ to re-enter all the information.

**Step 5.** If the process is successful, the screen will display ―**Updated Successfully.**‖ The sensor will be assigned to specific area and zone. To edit the device setting or information, click ―**Edit**‖ at the end of device entry.

**Step 6.** You will enter **Device Edit** webpage.

**Step 7.** Edit your device setting and information. Click ―OK‖ to save changes when finished.

### _**Identification**_

The ―Identify‖ function is used to localize a specific BUS device in the BUS wired system. This function is helpful in distinguishing which device is which especially in a large installation where numerous BUS devices are included.

To locate the Expansion Module in the BUS system:

**Step 1.** On Hybrid Panel’s webpage, click ―Identify‖ under the device list after the Expander’s device column entry.

![](<.gitbook/assets/12 (13).png>)

**Step 2.** If the Expansion Module receives the signal from the Hybrid Panel, the webpage will display a success message and the Expansion Module’s power LED indicator will flash for 10 times to indicate where it is to the user.

{% hint style="warning" %}
Note:

If a timeout message is displayed on the webpage, it means the Expansion Module did not receive the signal from the Panel.

Please check whether the Expansion Module is connected properly to the Panel within appropriate wiring distance.
{% endhint %}

### _**Walk Test**_

* To make sure the Expansion Module is able to communicate with the Panel after it is

learned-in, place the Control Panel in Walk Test mode and press the Test button on WEZC-8 to transmit a test signal to the Control Panel.

* When the Panel receives the test signal, it will beep once and display the Expansion Module’s information accordingly on the top of the device list.

{% hint style="warning" %}
Note:

If there is no response from the Panel after the press of test button, it means the Panel did not receive the test signal from the device.

Please check whether the Expansion Module is connected properly to the Panel within appropriate wiring distance.
{% endhint %}

### **How to Mount the Expansion Module**

The Expansion Module can be mounted on the wall. Follow the steps below to mount it:

* Loosen the bottom fixing screw and remove the front cover.
* Using the holes of the Expansion Module as a template, mark the drilling holes on the wall.
* Drill holes on the marked location on the wall. Insert wall plugs if required.
* Screw the base onto the mounting location.
* Re-place the front cover and tighten the bottom fixing screws.

![](<.gitbook/assets/13 (3).jpeg>)
