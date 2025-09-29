# VESTA-130

**WEZ-12/24/36/48-BUS Expansion Module**

## 12-zone module Expansion for Vesta hybrid control panels

<figure><img src=".gitbook/assets/image (19) (1) (1).png" alt=""><figcaption></figcaption></figure>

## Introduction

This installation guide shall be used in conjunction with the Hybrid Panel’s user’s manual, to which the WEZ model is connected to.

The WEZ-12/24/36/48-BUS Expansion Module is designed to support expansion for the Hybrid Panel. Through BUS connection, it can provide the expansion of additional 12, 24, 36, and 48 wired zones on the compatible panels.

## Identifying the Parts

WEZ-12-BUS WEZ-24-BUS

![](<.gitbook/assets/0 (1) (1) (1) (1) (1) (1) (1).jpeg>) ![](<.gitbook/assets/1 (1) (1) (1) (1) (1).jpeg>)

WEZ-36-BUS WEZ-48-BUS

![](<.gitbook/assets/2 (1) (1) (1).jpeg>) ![](<.gitbook/assets/3 (1) (1) (1).jpeg>)

1. **DC Jack:** DC 12V 1A switching power connection.
2. **Pluggable BUS Panel Connection Terminal**
3. **Terminal Resistor Jumper Switch**

When the Expansion Module is connected as the furthest BUS device on a BUS line, please set the Expansion Module's terminal resistor jumper and the first BUS device’s Jumper Switch to ON to serve as terminating resistors. The connected BUS line’s communication ability will be enhanced.

* **Jumper On:** If the jumper is ON, the communication ability will be enhanced.
* **Jumper Off:** If the jumper is OFF, the communication ability is in normal level.



4. **Screw Holes**
5. **Zone Terminal & 13.5V Auxiliary Voltage Output Terminal & GND Terminal**

&#x20;      The typical voltage is 13.5V, and it might vary depending on the output voltage of the terminal.

6. **Test Button**

&#x20;       Press the test button to send a test signal to the Control Panel.

7. **LED Indicator**

&#x20;       Click “Identify” on panel webpage to cause the corresponding WEZ device’s LED indicator to flash for 10 times.

### Power Supply

The expansion module is powered by the Hybrid Panel, which can provide 13.5V power source to the expansion module. Additionally, it is recommended to use the external 12V power adaptor when connected to loads that require heavier power draw.

### Caution&#x20;

* Wiring of the expansion module should only be performed by certified technicians with proper knowledge and training in electric equipment.
* Before installation or any maintenance work, make sure the power supply has been disconnected.

### Installation and Connection

<figure><img src=".gitbook/assets/10 (90).png" alt=""><figcaption></figcaption></figure>

* To assist with cable connections, the terminal blocks on each BUS system module are color-coded.
* For optimal communication of the wired connection between the Control Panel and the connected BUS devices, ensure the furthest BUS device’s Communication Jumper Switch and Control Panel’s J53 Jumper Switch are set to ON to serve as a terminating resistor. Be sure to only enable the aforementioned 2 jumper switches, and do not set the jumper switches to ON for any other BUS devices in between.
* Thread the four screws through the holes on the Expansion Module, and fasten the screws to secure.

<figure><img src=".gitbook/assets/7 (1) (1).jpeg" alt="" width="246"><figcaption></figcaption></figure>

* Connect the cables to the four terminals labeled as **VDD, GND, 485A, 485B** on the Hybrid Panel.

{% hint style="warning" %}
Note:

* _**The pluggable design of BUS terminal blocks improves installation efficiency. Before wiring, you can remove the terminal blocks from the device for ease of use, and plug in again after wiring. When re-installing the terminal blocks back to the board, make sure to install them in the same direction to avoid potential hazards.**_
* _**Incorrect connections will result in failure or improper operation. Inspect wiring and ensure proper connections before applying power.**_
{% endhint %}

### Zone Wiring

* The 12/24/36/48 zones can be wired by supervising NC (normally close) or NO (normally open) devices, e.g. PIR sensor, door contact, smoke detector, water sensor, fire sensor, CO sensor, gas detector, heat detector, and glass break detector, etc.
* Wire gauge: Minimum 22 AWG, maximum 18 AWG.
* The hardwired zones support Single-End-of-Line (SEOL), Double-End-of-Line (DEOL) loop configuration, with selectable resistor values of 1KΩ, 2.2KΩ, 3.74KΩ, 4.7KΩ, 5.6KΩ, 6.8KΩ, 8.2KΩ, 10KΩ ohms.
* Triple end-of-line (TEOL) loop can be configured in different combinations: 4.7KΩ, 6.8KΩ, 12KΩ (resistor value selection: 6.8K), 4.7KΩ/5.6KΩ, 4.7KΩ, 2.2KΩ/3KΩ (resistor value selection: 4.7K), or 4.7KΩ/5.6KΩ, 5.6KΩ, 2.2KΩ/3KΩ (resistor value selection: 5.6K).
* For an NO loop, please have an EOL resistor in parallel (across) the loop.
* For an NC loop, please have an EOL resistor in series with the loop.
* If a zone wiring method is changed, turn the system power off and back on again to avoid triggering the alarm.

### NO/NC Wiring

![1](<.gitbook/assets/9 (2).jpeg>) ![2](<.gitbook/assets/10 (1).jpeg>)

### **Single-End-of-Line Resistor Wiring**

![3](<.gitbook/assets/11 (1) (1) (1) (1).png>) ![4](<.gitbook/assets/12 (1) (1) (1) (1) (1) (1) (1).png>)

![5](<.gitbook/assets/13 (1) (1) (1) (1) (1) (1) (1).png>) ![6](<.gitbook/assets/14 (1) (1) (1) (1) (1) (1) (1).png>)

### **Double-End-of-Line Resistor Wiring**

![7](<.gitbook/assets/15 (1) (1) (1) (1) (1).png>) ![8](<.gitbook/assets/16 (1) (1) (1) (1) (1).png>)

### Triple-EOL Wiring

<figure><img src=".gitbook/assets/17 (1) (1) (1).jpeg" alt=""><figcaption><p>9</p></figcaption></figure>



<figure><img src=".gitbook/assets/18 (1) (1) (1).jpeg" alt=""><figcaption><p>10</p></figcaption></figure>



## Getting Started

After connecting the expansion board to the Hybrid Panel, and completing device wiring, please proceed to learning and zone programming.

### Learning

**Step 1.** Power on the Control Panel, the expansion module will be powered on as well.

**Step 2.** On the Panel’s webpage, click on “**Learning**” to enter learn page.

**Step 3.** Click on “**Start**” to enter learning mode.

**Step 4.** Click **“Add”** to include the Expansion Module into panel.

**Step 5.** If the Expansion Module is successfully learnt into the system, the added device will be displayed in the “Learned Device” section. The Device Type will be shown as “Expander”.

### Identification

The “**Identify**” function is used to localize a specific BUS device in the BUS wired system. This function is helpful in distinguishing which device is which especially in a large installation where numerous BUS devices are included.

To locate the expansion module in the BUS system:

**Step 1.** On Hybrid Panel’s webpage, click “Identify” under the device list after the Expander’s device column entry.

![](<.gitbook/assets/19 (1) (1).jpeg>)

**Step 2.** If the expansion module receives the signal from the Hybrid Panel, the webpage will display a success message and expansion module’s LED indicator will flash 10 times to indicate where it is to the user.

{% hint style="warning" %}
Note:

If a timeout message is displayed on the webpage, it means the expansion module did not receive the signal from the Panel. Please check whether the expansion module is connected properly to the Panel within appropriate wiring distance.
{% endhint %}

### Walk Test

* To make sure the expansion module is able to communicate with the Panel after it is learned-in, place the Control Panel in Walk Test mode and press the Test button on the expansion module to transmit a test signal to the Control Panel.
* When the Panel receives the test signal, it will beep once and display the expansion module’s information accordingly on the top of the device list.

{% hint style="warning" %}
Note:

If there is no response from the Panel after the press of test button, it means the Panel did not receive the test signal from the device.

Please check whether expansion module is connected properly to the Panel within appropriate wiring distance.
{% endhint %}

### _Wired Zone Programming_

After the expansion module is added, proceed to wired zone programming.

**Step 1.** Click Wired Sensor to enter this webpage. You will see the Expanders at the bottom of the page.

**Step 2.** Click “Edit” at end of expander entry.

**Step 3.** Edit the type of the wired sensor, zone wiring, and the EOL resistance for each zone.

* **Type**: Select the type of the wired sensor for each zone from the drop down menu.
* **Loop**: Select the number to correspond to the zone wiring for each zone from the drop down menu. On this web page, there are wiring diagrams below for your reference.
* **Resistor**: Select the resistance for the zone wiring.
* **Status**: The status of each zone—Restore, Tamper, or Trigger—will be shown in this

**Step 4.** Click “**OK**” to save changes when finished. Alternatively, click “**Reset**” to re-enter all the information.

**Step 5.** If the process is successful, the screen will display “**Updated Successfully.**” The sensor will be assigned to specific area and zone. To edit the device setting or information, click “**Edit**” at the end of device entry.

**Step 6.** You will enter **Device Edit** webpage.

**Step 7.** Edit your device setting and information. Click “OK” to save changes when finished.

### Supervisory Signal

After being learnt into the Control Panel, the expansion module will automatically transmit Supervisory Signals every 20 to 30 seconds.
