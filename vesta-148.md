# VESTA-148

## **GEN-TX Learn in Instructions**

GEN-TX is a transmitter module that allows to send wireless signals in F1 to the control panel.

This module is intended to be installed in any Optex wireless detector with universal dry contact output. The main purpose is to transmit the alarm, tamper and anti-masking signals of any detector and to get the third party detector fully integrated into the control panel.

The antennas of GEN-TX are different according to the frequency 433 and 868.



<div data-full-width="true"><figure><img src=".gitbook/assets/1 (106).png" alt=""><figcaption></figcaption></figure> <figure><img src=".gitbook/assets/2 (114).png" alt=""><figcaption></figcaption></figure></div>

{% hint style="info" %}
For connection, use the cable and connector provided on the Optex detector.
{% endhint %}

## _**Identifying the Parts**_

<div align="center" data-full-width="true"><figure><img src=".gitbook/assets/3 (1) (1).png" alt="" width="215"><figcaption></figcaption></figure></div>

1. **Learn/Test Button**
2. **Battery (CR2)**
3. **Supervision Jumper Switch (JP2)**
4. **LED indicator (Red)**

## _**LED Indicator**_

In Normal operation mode, the LED Indicator remains off except:

* When the motion detector is in low battery condition, each time it transmits a detected movement, the LED will flash for 6 times.
* When the Tamper Switch is triggered, the LED will flash for 6 times to indicate it is transmitting “**Tamper**” signal.
* When the Tamper condition persists, each time it transmits a detected movement, the LED will flash for 6 times.
* When the battery is exhausted, the LED will flash every 4 seconds.

## _Learning_

* Pull out the battery insulator to activate battery.
* Put the Control Panel into learning mode, refer to Control Panel manual for details.
* Press the Learn button.
* Refer to Control Panel manual to complete the learn-in process.

## _Walk Test_

* After the detector is learnt-in, put the Control Panel into “Walk Test” mode, hold the detector in the desired location, and press the Test button to confirm this location is within signal range of the Control Panel, refer to Control Panel manual to complete Walk Test.
* When you are satisfied that the detector works in the chosen location, you can proceed to mounting.

## _**Battery**_

* The detector uses one “CR2”, 3V Lithium battery as its power source.
* When low battery is detected, a low battery signal will be sent to the Control Panel along with regular signal transmissions for the Control Panel to display the status accordingly.
* When the battery is exhausted, the detector will stop all function, the LED will flash every 4 seconds.
* When changing battery, after removing the old battery, press the Learn button twice to fully discharge before inserting new battery.

## _**Supervision**_

* After installation, the detector will automatically transmit Supervisory signals periodically to the Control Panel at random intervals of 30 to 50 minutes.
* If the Control Panel has not received the signal from the detector for the preset period of time, the Control Panel will indicate on its display that the particular detector is experiencing an out-of-signal problem.

#### **Jumper OFF (Factory default)**&#x20;

<div align="left"><figure><img src=".gitbook/assets/5 (1).png" alt="" width="49"><figcaption></figcaption></figure></div>

\- When the jumper (JP2) is set as OFF, the Supervision is enabled.

#### **Jumper ON**

<div align="left"><figure><img src=".gitbook/assets/6 (1).png" alt="" width="37"><figcaption></figcaption></figure></div>

-When the jumper (JP2) is set as ON, the Supervision is disabled.

