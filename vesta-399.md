# VESTA-399

UIM-1-BUS

## Universal Interface Module

<figure><img src=".gitbook/assets/image (5) (1) (1).png" alt=""><figcaption></figcaption></figure>

Universal Interface Module (UIM-1-BUS) UIM-1-BUS is a Universal Interface Module that is designed to connect any wired detectors with dry contact to the Hybrid Panel and provide the connected detector with the power source. Designed with 3 inputs, UIM-1-BUS is capable of transmitting alarm/tamper/fault signals from the connected wired detector to the hybrid panel, therefore enabling devices without BUS terminals to conveniently and flexibly be integrated with the Alary System.

## Parts Identification



<figure><img src=".gitbook/assets/2025-02-27 14_51_34-UIM-1-BUS_20230804.pdf - Foxit PDF Reader.png" alt=""><figcaption></figcaption></figure>

**1. BUS Terminal**

**2. Terminal Resistor Jumper Switch**

When the Universal Interface Module is connected as the furthest BUS device on a BUS line, please set the terminal resistor jumper switch of UIM-1-BUS and the first BUS device’s (usually Hybrid Panel’s) terminal resistor jumper switch to ON to serve as terminating resistors. The connected BUS line’s communication ability will be enhanced.



**Jumper On:** The jumper link is inserted, connecting the two pins

&#x20;**Jumper Off:** The jumper link is removed or “parked” on one pin.2 &#x20;

\- If the jumper is ON, the communication ability will be enhanced.

**-**&#x49;f the jumper is OFF, the communication ability is in normal level.

**3.   5-wire Connector**

| Wire Color | Function     | Power Supply / Signal                                                            |
| ---------- | ------------ | -------------------------------------------------------------------------------- |
| Black      | GND          | Common wire                                                                      |
| Red        | VCC          |                                                                                  |
| Orange     | Alarm Input  | Reports Alarm Signals                                                            |
| Yellow     | Tamper Input | Reports Tamper Signals                                                           |
| Brown      | Fault Input  | Reports Fault Signals or Masking Signals for detector with Anti-masking function |

**4. LED Indicator (Red)**

\- The Red LED will flash once when UIM-1-BUS is powered.

\- The Red LED will flash once when the Test Button is pressed.

\- The Red LED will flash three times when a signal is transmitted under fault condition or test mode.

\- The Red LED will flash three times whenever the tamper of the connected detector is triggered or restored.

\- The LED will not light up or flash in normal operation mode.

**5. Test Button**

\- Press the Test Button to enter test mode for 3 minutes.

## **Features**

### &#x20;**Power Supply**

&#x20;UIM-1-BUS is powered by the Hybrid Panel through the BUS Terminal, and can provide 6.2V-13.5V, amaximum of 200mA power to the connected detector.

### &#x20;**Signal Transmission**

UIM-1-BUS has 3 inputs that can receive alarm signals (orange wire), tamper signals (yellow wire) and fault/masking signals (brown wire) from the connected detector and report them to the Panel over BUS.

{% hint style="danger" %}
**Caution**

Wiring of the module should only be performed by certified technicians with proper knowledge and training in electric equipment.

&#x20;Before installation or any maintenance work, make sure the power supply has been disconnected. **Wiring the Universal Interface Module**
{% endhint %}

Connect the wires to the desired detector according to FIG. 1 below.

| Black  | GND          |
| ------ | ------------ |
| Red    | VCC          |
| Orange | Alarm Input  |
| Yellow | Tamper Input |
| Brown  | Fault Input  |

&#x20;Before connecting the BUS cable, make sure the power is switched off.

&#x20;To assist with BUS cable connections, the terminal blocks on each BUS system module are color-coded.

| Red    | VDD  |
| ------ | ---- |
| Black  | GND  |
| Yellow | 485A |
| Green  | 485B |

Multiple BUS devices can be connected in series to the Hybrid Panel. For optimal communication of the connected BUS line devices, ensure the terminal resistor jumper switches of the first (usually the HybridPanel) and the furthest BUS devices on a BUS line are set to ON to serve as terminating resistors. Be sure to only enable the aforementioned 2 jumper switches, and do not set the jumper switches to ON for any other BUS devices in between.

Incorrect connections will result in failure or malfunction. Inspect wiring and ensure proper connections before applying the power.

{% hint style="warning" %}
Note:

&#x20;When re-installing the BUS terminal, make sure to install the blocks in the same way and direction as the picture below to avoid potential hazards.
{% endhint %}

\
