# VESTA-387

**Auxiliary Power Supply Module (PWB-1-BUS)**

**Introduction**

The PWB-1-BUS is an auxiliary power supply module that can be connected in the data BUS system to provide a maximum of 13.5V, 5A power supply to connected BUS devices. The PWB-1-BUS module is supervised and communicates back to the Panel all the status changes, including AC power status, battery level, tamper status, and energy consumption data.



## Identifying the Parts (VESTA-364N)



<figure><img src=".gitbook/assets/image (2) (1) (1) (1) (1) (1) (1).png" alt=""><figcaption><p>VESTA-364N</p></figcaption></figure>

1. BUS Connection Terminals to the **Hybrid Pane**l (3 wire: G, A, B)
2. BUS Connection Terminals to powered BUS device (4 wire: V, G, A, B)
3. BUS Connection Terminals to powered BUS device (4 wire: V, G, A, B)

{% hint style="warning" %}
#### DEPRECATED ONLY FOR VESTA-364

This drawing is deprecated and applies only to the old **VESTA-364** power supply module. Please refer to updated documentation for current models.



**Identifying the Parts**

<img src=".gitbook/assets/0 (5).jpeg" alt="" data-size="original">

1. **BUS Connection Terminals to powered BUS device** (4 wire: V, G, A, B)
2. **BUS Connection Terminals to powered BUS device** (4 wire: V, G, A, B)
3. **BUS Connection Terminals to the Hybrid Panel** (3 wire: G, A, B)
{% endhint %}



1. **Battery Switch**

Slide the battery switch to ON position, so that the backup battery will be charged when AC power is connected and serve as a backup power source when AC power is missing.

1. **Battery Terminal**

Connects to backup battery (One 12V 7.0Ah or 12V 17.2Ah Sealed Lead-acid battery)

1. **Mounting Holes**
2. **Power Terminal**

Connects to 20Vac 50Hz/60Hz, 4A (80VA) power supply

1. **Terminal Resistor Jumper Switch (J3)**

When the power supply module is connected in the BUS line as the furthest BUS device from the Hybrid Panel, please set both the Terminal Resistor Jumpers of the power supply module and the Hybrid Panel to ON. The BUS line’s communication ability will be enhanced.

*
  * The Terminal Resistor Jumper of PWB-1-BUS is usually used when the power supply module is first connected to the Hybrid Panel without any powered BUS devices connected.

You can set he power supply module’s Terminal Resistor Jumper and the Hybrid Panel’s Terminal Resistor Jumper to ON to test if PWB-1-BUS can communicate well with the Panel.

If communication with the Panel is tested OK, you can start connecting the PWB-1-BUS to the powered devices. Then please set the power supply module’s Terminal Resistor Jumper to off, and set the Terminal Resistor Jumper of the farthest device in the BUS line to ON instead.

![](<.gitbook/assets/1 (7).jpeg>)

If the jumper is OFF (the jumper link is removed or “parked” on one pin), the communication ability is in normal level.

![](<.gitbook/assets/2 (6).jpeg>)

If the jumper is ON (the jumper link rests on both pins), the communication ability is enhanced.

1

1. **LED Indicator**
2. **Tamper Switch Terminal** Connects to the lid tamper switch.

**Accessories**

1. Standoff \*4
2. Standoff Nut \*4
3. 12V 7.0Ah Battery cable \*2 (+, -)

**Power Supply**

**Power Source:**

* The PWB-1-BUS is connected to 20Vac 50Hz/60Hz, 4A (80VA) power supply.
* When power supply is interrupted and restore, PWB-1-BUS will transmit AC failure and restore signal respectively.

**Rechargeable Battery:**

* A 12V 7.0Ah or 12V 17.2Ah Sealed Lead-acid battery can to connected to serve as a backup in case of a power failure.
* During normal operation, the AC power is used to supply power to PWB-1-BUS and at the same time recharge the battery. It takes approximately 48 hours to fully charge a 12V 7.0Ah battery, and 72 hours to fully charge a 12V 17.2Ah battery.
* If the battery switch is set as OFF, the battery will not be charged when AC power is connected and nor will it serve as a backup power source when AC power is missing. You need to switch the battery to **ON** for it to be charged when AC power is connected and serve as a backup power source when AC power is missing.
* When the battery is low on power, PWB-1-BUS will transmit low battery signal. When the battery has been charged, PWB-1-BUS will transmit battery restore signal.
* When the battery is disconnected, battery switch is off, or battery failure is detected, PWB-1-BUS will report battery missing/dead to the Control Panel.

**Power Output:**

* PWB-1-BUS can supply a maximum of 13.5V, 5A power to connected BUS devices.

**Tamper Protection**

* The Tamper Switch for enclosure door is in normal position when the door is closed. Tamper violation happens when the door is opened where Tamper Switch is released (Tamper Opened). A tamper open signal will be reported to the Control Panel.

**Connecting to Panel and BUS devices**

**CAUTION:**

**Remove all power (AC and battery) before making any connections. Wiring of the Alarm System should only be performed by certified technician with proper knowledge and training in electric equipment.**

* To assist with cable connections, the terminal blocks on each BUS system module are color-coded.

**Terminal block color codes**

| **Red**    | VDD  |
| ---------- | ---- |
| **Black**  | GND  |
| **Yellow** | 485A |
| **Green**  | 485B |

* When connecting the PWB-1-BUS to the Hybrid Panel, connect the three terminals only (GND, 485A, 485B). Please refer to the picture below.
* When connecting the PWB-1-BUS to the devices that are powered by the power supply module, please connect 4 terminals. (VDD, GND, 485A, 485B).

Please refer to the BUS device connection examples (VST-892-BUS & DC-23-BUS) below.

<figure><img src=".gitbook/assets/image (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1).png" alt=""><figcaption><p>VESTA-364N</p></figcaption></figure>

{% hint style="warning" %}
**DEPRECATED**&#x20;

Only VESTA-364

<img src=".gitbook/assets/3 (6).jpeg" alt="" data-size="original">
{% endhint %}



* The pluggable design of BUS terminal blocks improves upon installation efficiency. Before wiring, you can remove the terminal blocks from the device for ease of use, and plug in again after wiring.

When re-installing the terminal blocks back to the board, make sure to install in the same direction to avoid potential hazards.

* Incorrect connections will result in failure or improper operation. Inspect wiring and ensure proper connections before applying power.

**Getting Started**

After connecting the auxiliary power supply module to the Hybrid Panel (Please refer to _**Connecting to Panel and BUS devices**_ section for details), please proceed to learning.

* _**Learning**_

**Step 1.** After the PWB-1-BUS is connected to the Hybrid Panel, power on the Control Panel.

**Step 2.** On the Control Panel webpage, click on “**Learning**” to enter learn page.

**Step 3.** Click on “**Start**” to enter learning mode.

**Step 4.** Click **“Add”** to include the auxiliary power supply module into panel.

**Step 5.** If the auxiliary power supply module is successfully learnt into the system, the added device will be displayed in the “Learned Device” section. The Device Type will be shown as “PWB”.

* _**Identification**_

The “**Identify**” function is used to localize a specific BUS device in the BUS wired system. This function is helpful in distinguishing which device is which especially in a large installation where numerous BUS devices are included.

To locate PWB-1-BUS in the BUS system:

![](<.gitbook/assets/4 (9).png>)

**Step 1.** On Hybrid Panel’s webpage, click “Identify” under the device list after PWB’s device column entry.

**Step 2.** If PWB-1- BUS receives the signal from the Hybrid Panel, the webpage will display a success message and PWB-1-BUS’ LED indicator will flash 10 times to indicate where it is to the user.

_\<NOTE>_

* If a timeout message is displayed on the webpage, it means the PWB-1-BUS did not receive the signal from the Panel.

3

Please check whether PWB-1-BUS is connected properly to the Panel within appropriate wiring distance.

**Supervisory Signal**

* After being learnt into the Control Panel, the Power Supply module will automatically transmit Supervisory Signals every 20 to 30 seconds.

**Energy Consumption Monitor**

* After being learnt into the Control Panel, the Power Supply module will automatically transmit power consumption data, including battery level, BUS voltage, and BUS current to the Control Panel every 30-50 minutes.

![](<.gitbook/assets/5 (11).png>)





When the battery level is below or equal to 20%, a low battery signal will be sent to the Panel.

When battery level is 0%, it indicates one of the follow situations: battery disconnection, battery switch in off position, or battery failure.

User can also manually query the power consumption data on **Device Edit** page.

![](<.gitbook/assets/6 (9).png>)

**Mounting the PWB-1-BUS in the enclosure (AWO300)**

* Locate the **standoff locations on the enclosure AWO300** (○1 – A, B, C, D), and the **mounting holes on the PWB-1-BUS** (○2 – A, B, C, D).

![](<.gitbook/assets/7 (10).png>)

4

* Use the provided standoffs to securely mount the PWB-1-BUS in the enclosure.

![](<.gitbook/assets/8 (9).png>)

* After all wiring is completed, install the backup battery. Battery options include: A 12V 7.0Ah or 12V 17.2Ah Sealed Lead-acid battery.

To Install the battery, follow the steps below:

*
  1. Connect the GND cable (Black) to the negative pole (-) of battery.
  2. Connect the power cable (Red) to the positive pole (+) of battery
  3. Fix the backup battery to the enclosure.
* Connect the enclosure door tamper switch to the tamper terminal.
* Connect the power terminal to 20Vac 50Hz/60Hz, 4A (80VA) power supply. Slide the battery switch to ON.

![](<.gitbook/assets/9 (11).png>)

5
