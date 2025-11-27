# VESTA-364N

**PWB-1-BUS**

## **BUS Auxiliary Power Supply Module**

<figure><img src=".gitbook/assets/image (22) (1).png" alt=""><figcaption></figcaption></figure>

**Simple guide:**&#x20;

{% hint style="warning" %}
**It is very important** in the **VESTA-364N** power supply, connect the <mark style="color:red;">**positive**</mark> input to the **hybrid control panel**, this will allow greater control over the power supply.
{% endhint %}

<figure><img src=".gitbook/assets/image (129).png" alt=""><figcaption></figcaption></figure>

**Introduction**

The PWB-1-BUS is an auxiliary power supply module designed for integration into the BUS system, providing a maximum of 13.5V, 3A power supply to connected BUS devices.

When connected to the Hybrid Panel, the PWB-1-BUS module is supervised by and communicates to the Panel all the status changes, including AC power status, battery level, tamper status, and energy consumption data. Moreover, the PWB-1-BUS features voltage detection of the Hybrid Panel BUS VDD terminal. Only when the Hybrid Panel operates normally with power supplied at the BUS output will PWB-1-BUS supply power to connected BUS devices.

## **Identifying the Parts**

![](<.gitbook/assets/0 (132).jpeg>)

1. **BUS Connection Terminals to the Hybrid Panel** (4 wire: V, G, A, B)
2. **BUS Connection Terminals to powered BUS device** (4 wire: V, G, A, B)
3. **BUS Connection Terminals to powered BUS device** (4 wire: V, G, A, B)
4. **Battery Switch**

Slide the battery switch to ON position, so that the backup battery will be charged when the AC power is connected and serve as a backup power source when AC power is missing.

5. **Battery Terminal**

For the backup battery (One 12V 7.0Ah or 12V 17.2Ah Sealed Lead-acid battery)

6. **Terminal Resistor Jumper Switch (J3)**

When the power supply module is connected in the BUS line as the furthest BUS device from the Hybrid Panel, please set both the Terminal Resistor Jumpers of the power supply module and the Hybrid Panel to ON. The BUS line’s communication ability will be enhanced

* The Terminal Resistor Jumper of PWB-1-BUS is usually used when the power supply module is first connected to the Hybrid Panel without any powered BUS devices connected.
* You can set he power supply module’s Terminal Resistor Jumper and the Hybrid Panel’s Terminal Resistor Jumper to ON to test if PWB-1-BUS can communicate well with the Panel.
* If communication with the Panel is tested OK, you can start connecting the PWB-1-BUS to the powered devices. Then please set the power supply module’s Terminal Resistor Jumper to off, and set the Terminal Resistor Jumper of the farthest device in the BUS line to ON instead.

If the jumper is OFF (the jumper link is removed or “parked” on one pin), the communication ability is in normal level.

If the jumper is ON (the jumper link rests on both pins), the communication ability is enhanced.

7. **Mounting Holes**
8. **AC Power Terminal and Power Cable**

For 20Vac 50Hz/60Hz, 4A (80VA) power supply

9. **LED Indicator**
10. **Test Button**

Press to send a test signal to the Panel

11. **Tamper Switch Terminal Block 1**

For connecting to the door tamper switch on the enclosure

12. **Tamper Switch Terminal Block 2 (optional)**

For connecting to the wall-mount tamper switch on the enclosure

This terminal block is in a short status, connected with a black wire provided by factory before shipment.

If the enclosure is to be mounted on the wall and you wish to enable the wall tamper protection, please remove the black wire and connect this terminal block to the wall-mount tamper switch.

### **Accessories**

1. Standoff \*4
2. Standoff Nut \*4
3. 12V 7.0Ah Battery cable \*2 (+, -)

## **Power Supply**

_**Power Source**_**:**

* The PWB-1-BUS is connected to 20Vac 50Hz/60Hz, 4A (80VA) power supply.
* When power supply is interrupted and then restore, PWB-1-BUS will transmit an AC failure and an AC restore signal respectively.

_**Rechargeable Battery**_**:**

* A 12V 7.0Ah or 12V 17.2Ah Sealed Lead-acid battery can be connected to serve as a backup in case of a power failure.

{% hint style="warning" %}
Note:

* The Auxiliary Power Supply Module will be activated only when it is powered by the AC power first. If PWB-1-BUS is first powered by the rechargeable battery, it will not be activated.
* During normal operation, the AC power is used to supply power to PWB-1-BUS and at the same time recharge the battery. It takes approximately 48 hours to fully charge a 12V 7.0Ah battery, and 72 hours to fully charge a 12V 17.2Ah battery.
* If the battery switch is set as OFF, the battery will not be charged when the AC power is connected and nor will it serve as a backup power source when the AC power is missing. You need to switch the battery to **ON** for it to be charged when the AC power is connected and serve as a backup power source when the AC power is missing.
* When the battery is low in power, PWB-1-BUS will transmit a low battery signal. When the battery has been charged, PWB-1-BUS will transmit a battery restore signal.
* When the battery is disconnected, battery switch is off, or battery failure is detected, PWB-1-BUS will report battery missing/dead to the Control Panel.
{% endhint %}

## _**Power Output**_**:**

* PWB-1-BUS can supply a maximum of 13.5V, 3A power to the connected BUS devices.
* Through connection to the Hybrid Panel's BUS VDD terminal, PWB-1-BUS can detect if the Panel operates normally with power supplied at the BUS output. Only when PWB-1-BUS is properly connected to the Panel and confirms the Panel’s normal operation will PWB-1-BUS supply power to connected BUS devices.

## **Tamper Protection**

Two Tamper Switch Terminals are provided: one for the door tamper switch and the other for the wall-mount tamper switch on the enclosure.

The Tamper Switches for door and wall-mount are in a normal position when the door is closed and the enclosure is securely mounted on the wall. Tamper violation happens when the door is opened or the enclosure is detached from the wall, causing the Tamper Switch to activate (Tamper Opened). A tamper open/close alert will be reported to the Control Panel.

## **Connecting to Panel and BUS Devices**

{% hint style="danger" %}
**CAUTION**

**Remove all power (AC and battery) before making any connections. Wiring of the Alarm System should only be performed by certified technicians with proper knowledge and training in electric equipment.**
{% endhint %}

* To assist with cable connections, the terminal blocks on each BUS system module are color-coded.

<figure><img src=".gitbook/assets/10 (90).png" alt=""><figcaption></figcaption></figure>

* When connecting the PWB-1-BUS to the Hybrid Panel, connect the four terminals (VDD, GND, 485A, 485B). Please refer to the picture below. Connecting the Red V terminal on PWB-1-BUS to the Hybrid Panel VDD terminal will enable BUS output voltage detection of the Hybrid Panel.
* When connecting the PWB-1-BUS to the devices that are powered by the power supply module, please connect 4 terminals (VDD, GND, 485A, 485B).

Please refer to the BUS device connection examples (VST-892-BUS & DC-23-BUS) below.

![](<.gitbook/assets/3 (90).jpeg>)

{% hint style="warning" %}
Note:

* The pluggable design of BUS terminal blocks improves installation efficiency. Before wiring, you can remove the terminal blocks from the device for ease of use, and plug in again after wiring.
* When re-installing the terminal blocks back to the board, make sure to install the blocks in the same way before it is removed to avoid potential hazards.
* Incorrect connections will result in failure or improper operation. Inspect wiring and ensure proper connections before applying power
{% endhint %}

## **Getting Started**

After connecting the auxiliary power supply module to the Hybrid Panel (Please refer to _**Connecting to Panel and BUS devices**_ section for details), please proceed to learning.

## _**Learning**_

**Step 1.** After the PWB-1-BUS is connected to the Hybrid Panel, power on the Panel.

**Step 2.** On the Control Panel’s webpage, click “**Learning**” to enter learn page.

{% hint style="warning" %}
Note:

The Auxiliary Power Supply Module will be activated only when it is powered by the AC power first. If PWB-1-BUS is first powered by the rechargeable battery, it will not be activated.
{% endhint %}

**Step 3.** Click “**Start**” to enter learning mode.

**Step 4.** Click “**Add**” to include the auxiliary power supply module into panel.

**Step 5.** If the auxiliary power supply module is successfully learnt into the system, the added device will be displayed in the “Learned Device” section. The Device Type will be shown as “PWB”.

## _**Identification**_

The “**Identify**” function is used to localize a specific BUS device in the BUS wired system. This function is helpful in distinguishing which device is which especially in a large installation where numerous BUS devices are included.

To locate PWB-1-BUS in the BUS system:

![](<.gitbook/assets/4 (112).png>)

**Step 1.** On Hybrid Panel’s webpage, click “**Identify**” under the device list after PWB’s device column entry.

**Step 2.** If PWB-1-BUS receives the signal from the Hybrid Panel, the webpage will display a success message and PWB-1-BUS’ LED indicator will flash 10 times to indicate where it is to the user.

{% hint style="warning" %}
Note:

If a timeout message is displayed on the webpage, it means the PWB-1-BUS did not receive the signal from the Panel. Please check whether PWB-1-BUS is connected properly to the Panel within appropriate wiring distance.
{% endhint %}

## _**Walk Test**_

To make sure the auxiliary power supply module is able to communicate with the Panel after it is learned-in, place the Control Panel in Walk Test mode and press the Test button on PWB-1-BUS to transmit a test signal to the Control Panel.

When the Panel receives the test signal, it will beep once and display PWB-1-BUS information accordingly on the top of the device list.

{% hint style="warning" %}
Note:

If there is no response from the Panel after the press of test button, it means the Panel did not receive the test signal from the device. Please check whether PWB-1-BUS is connected properly to the Panel within appropriate wiring distance.
{% endhint %}

## _**Supervisory Signal**_

After being learnt into the Control Panel, the auxiliary power supply module will automatically transmit Supervisory Signals every 75 seconds.

## _**Energy Consumption Monitor**_

After being learnt into the Control Panel, the auxiliary power supply module will automatically transmit power consumption data, including battery level, BUS voltage, and BUS current to the Control Panel every 30-50 minutes.

![](<.gitbook/assets/5 (115).png>)

* When the battery level is below or equal to 20%, a low battery signal will be sent to the Panel.
* When battery level is 0%, it indicates one of the follow situations: battery disconnection, battery switch in off position, or battery failure.

Users can also manually query the power consumption data on **Device Edit** page.

![](<.gitbook/assets/6 (96).png>)

## **Mounting the PWB-1-BUS in the enclosure (AWO978)**

**Step 1.** Locate the **locations for standoffs on the enclosure AWO978** (①– A, B, C, D), and the **mounting holes on the PWB-1-BUS** (② – A, B, C, D).

![](<.gitbook/assets/7 (86).png>)

**Step 2.** Use the provided standoffs and nuts to firmly fix PWB-1-BUS in place.

![](<.gitbook/assets/8 (85).png>)

**Step 3.** Connect the tamper switch terminal block 1 to the door tamper switch on the enclosure.

**Step 4.** (Optional) Connect the terminal block 2 to the wall-mount tamper switch on the enclosure.

Tamper Switch Terminal Block 2 is in a short status, connected with a black wire provided by factory before shipment. If the enclosure is to be mounted on the wall and you wish to enable the wall tamper protection, please remove the black wire and connect Tamper Switch Terminal Block 2 to the wall-mount tamper switch.

{% hint style="warning" %}
Note:

For both Steps 3 and 4, each terminal block contains two individual terminals for connecting to the tamper switch via two wires. It doesn't matter which wire goes to which terminal. They are interchangeable.
{% endhint %}

**Step 5.** Install the backup battery. Follow the steps below:

1. Connect the GND cable (Black) to the negative pole (-) of battery.
2. Connect the power cable (Red) to the positive pole (+) of battery
3. Fix the backup battery to the enclosure.

Battery options: **12V 7.0Ah** or **12V 17.2Ah** Sealed Lead-acid battery.

**Step 6.** Connect the AC power cable to the 20Vac 50Hz/60Hz, 4A (80VA) power supply.

{% hint style="warning" %}
Note:

The two wires of the AC power cable must be connected to the 20V output terminals
{% endhint %}

![](<.gitbook/assets/9 (46).jpeg>)

**Step 7.** Slide the battery switch to ON. The installation is now completed.

![](<.gitbook/assets/10 (82).png>)
