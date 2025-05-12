# VESTA-340

WEPC-1

## **Programmable Output Expansion Module**



{% hint style="warning" %}
Note: If you use it **without battery** backup, you have to **remove the JUMPER J8**, and leave it in parked position without plugging it in.
{% endhint %}

<figure><img src=".gitbook/assets/image (53).png" alt=""><figcaption><p>Remove J8 when using without backup battery</p></figcaption></figure>

## **Introduction**

The WEPC-1 Series Programmable Output Expansion Module is designed to provide programmable output for the Hybrid Panel. Connected to the Hybrid Panel via BUS connection, it includes 4 programmable relay outputs, which can be used in conjunction with compatible panels. The WEPC-1 Series is equipped with its own enclosure case, which has tamper protection and LED status indicators.

**WEPC-1 Series Programmable Output Expansion Module includes the following models:**

**WEPC-1** – Programmable Output Expansion Module

**WEPC-1B** – Programmable Output Expansion Module with rechargeable battery pack

## **Identifying the Parts**

&#x20;                            **Front View**                                                                               **Back View**

![](<.gitbook/assets/0 (27).jpeg>)

&#x20;                                                                                            **Internal View**

![](<.gitbook/assets/1 (23).jpeg>)



1. **Power LED (Red)**

On – Powered by a 12V power adapter or Hybrid Panel.

Off – When the power is off, or when powered by rechargeable battery.

2. **Zone 1\~4 LED (Red)**

The corresponding Zone LED will light up when the dry contact relay output switch is turned on, and the LED light will turn off when the switch is being turned off.

3. **Transmission LED (Red)**

Lights up when connection is normal between the Expansion Module and Control Panel.

4. **Breakaway Area**

When the expansion module is forcibly removed from the mounting location, the area will detach and allow tamper switch to be activated.

5. **Tamper Switch (For Wall Mounting)**

The expansion module is protected by the tamper switch against any unauthorized removal from the mounting location.

6. **Mounting Holes**
7. **Wiring Hole**
8. **Battery Connection Terminal (for WEPC-1B only)**

For connecting the rechargeable battery pack to the PCB.

{% hint style="warning" %}
If you do not wish to install the battery, its monitoring can be disabled by disconnecting jumper switch J8. Before manipulating jumper J8, disconnect the power supply.

* OFF= battery status monitoring disabled
* ON= battery status monitoring enable
{% endhint %}

9. **Terminal Resistor Jumper Switch (J3)**

When the Expansion Module is connected as the furthest BUS device on a BUS line, please set the Expansion Module’ terminal resistor jumper and the first BUS device’s (usually the Hybrid Panel’s) Jumper Switch to ON to serve as terminating resistors. The connected BUS line’s communication ability will be enhanced.

* Turn the jumper to OFF by removing the jumper link or “parking” the jumper link on one pin

<figure><img src=".gitbook/assets/1 (105).png" alt=""><figcaption></figcaption></figure>

* Turn the jumper to ON by resting the jumper link on both pins

<figure><img src=".gitbook/assets/2 (113).png" alt=""><figcaption></figcaption></figure>

10. **Rechargeable Battery Pack (For WEPC-1B only)**
11. **DC Jack**

For DC 12V switching power connection.

To supply stable and sufficient power to charge the rechargeable batteries for WEPC-1B, it is strongly recommended to use a 12V/1A switching power adaptor.**Pluggable BUS Terminal**

12. **Dry Contact Relay PGM Output Terminal**
13. **Tamper Switch (For Case Cover)**

The expansion module is protected by the tamper switch against any unauthorized case opening. Whenever the case cover is opened, the tamper switch will be activated.

15. **Reset Button (Reserved for Internal Use)**
16. **Test Button**

Press the test button to send a test signal to the Control Panel.

## **Power Supply**

* The expansion module is powered by the Hybrid Panel, which can provide 13.5V power source to the expansion module. Additionally, it is recommended to use the external power adaptor (12V) when connected to loads that require heavier power draw.
* When the power supply from the adaptor is interrupted and restored, the expansion module will transmit an AC failure signal and a restore signal respectively to the Control Panel.

## **Rechargeable Battery Pack (for WEPC-1B only)**

* For WEPC-1B, a Ni-MH rechargeable battery pack is pre-installed in the Expansion Module to serve as a backup in case of a power failure.
* Please connect the battery pack to the PCB manually to use it as a backup power source and/or to charge it automatically when power is connected from the adaptor or Hybrid Panel.&#x20;

{% hint style="warning" %}
Before connecting the battery pack, make sure the power of DC Jack and/or BUS terminal is/are switched off. It is strongly recommended to use a 12V/1A switching power adaptor to supply stable and sufficient power to charge the batteries.
{% endhint %}

* When the rechargeable battery pack is low in power, the expansion module will transmit a low battery signal to the Control Panel. When the batteries have been charged, it will also transmit a battery restore signal to the Control Panel.

### **Tamper Protection**

WEPC-1 Series has two Tamper Switches; each comes with a different function.

* The Tamper Switch for case cover is located at the front of the board. It is in normal position when the case is closed. Tamper violation happens when the case is opened where Tamper Switch is released (Tamper Opened).
* The Tamper Switch for wall mounting is located at the back of the board. It is in normal position when the module is well mounted on the wall. Tamper violation happens when the module is forcibly removed from the mounting location, the area will detach and allow tamper switch to be activated.
* The tamper is considered as triggered if any one of the tamper is opened. The tamper is only considered restored when both tampers are in closed state.

### **Supervisory Signal**

* After being learnt in to the Control Panel, the Expansion module will automatically transmit Supervisory Signals every 20 to 30 seconds.

### **Connection to the Hybrid Panel**

* Before connection, make sure the power supply has been disconnected, and the panel battery switch has been slid to OFF position.
* To assist with cable connections, the terminal blocks on each system module are color-coded.

| <mark style="color:red;">**Red**</mark>       | **VDD**  |
| --------------------------------------------- | -------- |
| **Black**                                     | **GND**  |
| <mark style="color:yellow;">**Yellow**</mark> | **485A** |
| <mark style="color:green;">**Green**</mark>   | **485B** |

* For optimal communication of the wired connection between the Control Panel and the connected BUS devices, ensure the furthest BUS device’s Communication Jumper Switch and Control Panel’s J53 Jumper Switch are set to ON to serve as a terminating resistor. Be sure to only enable the aforementioned 2 jumper switches, and do not set the jumper switches to ON for any other BUS devices in between.
* The WEPC-1 series can be connected to and powered by either the Control Panel via the BUS terminal or the external power via the 12V adaptor. If the expansion module is using external power, be sure to bypass the red VDD terminal on the Control Panel using the Wago 221 Splicing Connector.
* Incorrect connections will result in failure or improper operation. Inspect wiring and ensure proper connections before applying power.
* The following diagram shows how WEPC-1 is connected to and powered by the Hybrid Panel.

![](<.gitbook/assets/3 (18).jpeg>)

* The following is the connection of WEPC-1B to the Hybrid Panel, with WEPC-1B being powered by the external power source.

![](<.gitbook/assets/4 (13).jpeg>)

{% hint style="warning" %}
_-Be sure to bypass the red VDD terminal on the Control Panel using the provided Wago 221 Splicing Connector. Connect the VDD terminal to the next BUS device (VST-892-BUS as example) that is powered by Hybrid Panel._

_-The pluggable design of the BUS terminal improves installation efficiency. Before wiring, you can remove the terminal blocks from the device for ease of use, and plug in again after wiring. When re-installing the terminal blocks back to the board, make sure to install them in the same direction to avoid potential hazards._
{% endhint %}

### **Getting Started**

After connecting the expansion board to the Hybrid Panel, and completing device wiring, please proceed to learning and power switch sensor programming.

#### _**\* Learning**_

**Step 1.** Connect the Expansion Module to the Control Panel. Then, power on the Control Pane&#x6C;**.**

**Step 2.** Click on “**Learning**” to enter learn page.

**Step 3.** Click on “**Start**” to enter learning mode.

**Step 4.** Click **“Add”** to include the Expansion Module into panel.

**Step 5.** If the Expansion Module is successfully learnt into the system, the added device will be displayed in the “Learned Device” section. The Device Type will be shown as “Expander”.

#### _**\* Power Switch Sensor Programming**_

After the programmable output expansion module is added, proceed to Power Switch Sensor programming.

**Step 1.** Click Wired Sensor to enter this webpage. You will see the Expanders at the bottom of the page.

**Step 2.** Click “Edit” at end of expander entry.

**Step 3.** Select and assign the output switch for each zone.

* **Type**: Select to activate the power switch for each zone from the Type’s drop down menu. The default setting is “Disabled” and you can choose to assign the dry contact relay output power switch to a zone by selecting “Power Switch”.

**Step 4.** Click “**OK**” to save the changes when finished. Alternatively, click “**Rese**t” to re-enter all the information.

**Step 5.** If the process is successful, the screen will display “**Updated Successfully.**” The power switch will be assigned to specific area and zone.

**Step 6.** Click on “PSS Control” under Device Management, and you will enter **Power Switch Sensor** webpage.

**Step 7.** Under this page, you may switch on or off the power switch of each zone.

**Step 8.** You may also edit your device setting and information. Click “**Edit**” at the end of device entry and click “OK” to save changes when finished.

#### _**\* Identification**_

The “Identify” function is used to localize a specific BUS device in the BUS wired system. This function is helpful in distinguishing which device is which especially in a large installation where numerous BUS devices are included.

To locate the Programmable Output Expansion Module in the BUS system:

**Step 1.** On Hybrid Panel’s webpage, click “Identify” under the device list after the Expander’s device column entry.

![](<.gitbook/assets/5 (34).png>)



**Step 2.** If the Programmable Output Expansion Module receives the signal from the Hybrid Panel, the webpage will display a success message and the WEPC-1(B)’s power LED indicator will flash for 10 times to indicate where it is to the user.

{% hint style="warning" %}
If a timeout message is displayed on the webpage, it means the Programmable Output Expansion Module did not receive the signal from the Panel.
{% endhint %}

Please check whether WEPC-1(B) is connected properly to the Panel within appropriate wiring distance.

#### _**\* Walk Test**_

* To make sure the Programmable Output Expansion Module is able to communicate with the anel after it is learned-in, place the Control Panel in Walk Test mode and press the Test button on WEPC-1(B) to transmit a test signal to the Control Panel.
* When the Panel receives the test signal, it will beep once and display the WEPC-1(B)’s information accordingly on the top of the device list.

{% hint style="warning" %}
If there is no response from the Panel after the press of test button, it means the Panel did not receive the test signal from the device.
{% endhint %}

Please check whether WEPC-1(B) is connected properly to the Panel within appropriate wiring distance.

### **PGM Wiring**

* The PGM port can serve as dry contact relay output.
* By default, the N.C and COM are set as short circuited.
* You may set the N.O. and COM as the short circuit by turning on the power switch through the programming web page.

&#x20;                                          **Default Setting**                          **Setting by Programming Page**

![](<.gitbook/assets/6 (20).jpeg>) ![](<.gitbook/assets/7 (19).jpeg>)

### **How to Mount the Programmable Output Expansion Module**

![](<.gitbook/assets/8 (15).jpeg>)

The Programmable Output Expansion Module can be mounted on the wall as the steps below:

* Loosen the bottom fixing screw and remove the front cover,
* Using the holes of the Programmable Output Expansion Board as a template, mark the drilling holes on the wall.
* Drill holes on the marked location on the wall. Insert wall plugs if required.
* Screw the base onto the mounting location.
* Re-place the front cover, and tighten the bottom fixing screws.

