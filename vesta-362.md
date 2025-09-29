# VESTA-362

**SR-35-BUS**

## **BUS Wired Indoor Siren**

<figure><img src=".gitbook/assets/image (20).png" alt=""><figcaption></figcaption></figure>

SR-35-BUS is a hardwired Indoor Siren that is used for system alarm indication. When an alarm signal is received from the Control Panel, the Wired Indoor Siren will activate to attract attention. The device can also work with the Control Panel to emit entry and exit delay sounds, and also alert you to tamper violation.

## **Identifying the Parts**

![](<.gitbook/assets/1 (5).jpeg>)

1. **Learn Button**
2. **Terminal Resistor Jumper Switch**

When the Wired Indoor Siren is connected as the furthest BUS device on a BUS line, please set the Wired Indoor Siren's terminal resistor jumper and the first BUS device’s (usually the Hybrid Panel’s) Jumper Switch to ON to serve as terminating resistors. The connected BUS line’s communication ability will be enhanced.

**Jumper On:** The jumper link is inserted, connecting the two pins.

**Jumper OfF:** The jumper link is removed or “**parked**” on one pin.

* If the jumper is OFF, the communication ability is in normal level.
* If the jumper is ON, the communication ability is enhanced.

3. **BUS Terminal**
4. **Bottom Fixing Screw**
5. **Tamper Switch**

The tamper switch will be activated when the Siren is removed from the mounting bracket.

6. **Breakaway Area for BUS Wiring**
7. **Mounting Bracket**

## **Power Supply**

* When SR-35-BUS is hardwired to a Hybrid Panel, 13.5V power supply can be provided by the Hybrid Panel.

## **Supervision**

The Wired Indoor Siren will transmit a supervisory signal every 20-30 seconds in normal operation mode.

If this signal is not received, the Control Panel will indicate that the particular Siren is experiencing an out-of-order problem.

## **Function Overview**

* **Alarm Memory**

If an alarm was triggered in your absence and the system was not disarmed before the alarm length expiry, the Wired Indoor Siren will sound a short alarm when the system is disarmed to warn the user that an alarm had been triggered when he is away. This suggests that the intruder could still be within the premises.

* **Alarm Length**

When an alarm is activated by the Control Panel, the Panel will notify the Wired Indoor Siren to start alarming according to the Panel’s alarm length. When the Panel’s alarm length expires, the Panel will notify the device to stop the alarm.

If the Wired Indoor Siren does not receive the Control Panel’s signal to stop the alarm, it will alarm for a maximum of 15 minutes, then stop the alarm.

For example:

* If the Panel’s alarm length is set to more than 15 minutes, after an alarm is activated, instead of waiting the panel’s alarm length to expire, the alarm will stop after 15 minutes.
* If the Panel is under disarmed mode and the Siren’s tamper switch is triggered, the Wired Indoor Siren will not activate the alarm since the Panel is under disarmed mode and will activate the alarm for 15 minutes due to tamper triggering.
* **Siren Tamper**

The Wired Indoor Siren is protected against any attempts to open the lid or to detach the device from its mounting surface.

If the device detects a tamper condition, it will activate the siren for the programmed alarm length. A tamper signal will be sent to the Control Panel along with regular signal transmissions for the Control Panel to display the status accordingly. If the tamper condition continues, the device will sound a series of five beeps to indicate a fault either every time the system is armed or when the tamper is enabled.

* **Audio Status Indication**

While arming / disarming the system, different methods are used to distinguish various statuses for the user, as listed in the table below.

<figure><img src=".gitbook/assets/image (270).png" alt=""><figcaption></figcaption></figure>



{% hint style="danger" %}
**Caution**



* Wiring of the Wired Indoor Siren should only be performed by certified technicians with proper knowledge and training in electric equipment.
* Before installation or any maintenance work, make sure the power supply has been disconnected
{% endhint %}

## **Siren Wiring**

* Before connecting the Wired Indoor Siren to the system bus, please switch the power off.
* To assist with cable connections, the terminal blocks on each BUS system module are color-coded.

![](<.gitbook/assets/14 (2) (1).jpeg>)

* Multiple BUS devices can be connected in series to the Hybrid Panel. For optimal communication of the connected BUS line devices, ensure the terminal resistor jumper switches of the first (usually the Hybrid Panel) and the furthest BUS devices on a BUS line are set to ON to serve as terminating resistors. Be sure to only enable the aforementioned 2 jumper switches, and do not set the jumper switches to ON for any other BUS devices in between.

{% hint style="warning" %}
Note:

* The pluggable design of BUS terminal blocks improves upon installation efficiency. Before wiring, you can remove the terminal blocks from the PCB board for ease of use, and plug in again after wiring.
* After unplugging the terminal, when re-installing the terminal back to the board, make sure to install the terminal in the same direction to avoid potential hazards.
{% endhint %}

* Incorrect connections will result in failure or improper operation. Inspect wiring and ensure proper connections before applying power.

![](<.gitbook/assets/16 (12).png>)

## **Learning**

Please follow the steps below to learn the Wired Indoor Siren into the Hybrid Panel.

Step 1. Connect the device to the Panel. Then, power the Panel on.

Step 2. On the Panel’s webpage, click “**Learning**” to enter learn page.

Step 3. Click “**Start**” to enter learning mode.

Step 4. Click “**Add**” to include the device into the Panel.

Step 5. If the device is successfully learnt into the Panel, it will be displayed in the “Learned Device” section.

## **Identification**

The “**Identify**” function is used to localize a specific BUS device in the BUS wired system. This function is helpful in distinguishing which device is which especially in a large installation where numerous BUS devices are included.

To locate the Wired Indoor Siren in the BUS system:

**Step 1.** On Hybrid Panel’s webpage, click “Identify” under the device list after the Siren’s device column entry.

**Step 2.** If SR-35-BUS receives the signal from the Hybrid Panel, the webpage will display a success message and the Wired Indoor Siren will emit 10 beeps to indicate where it is to the user.

{% hint style="warning" %}
Note:

If a timeout message is displayed on the webpage, it means the Wired Indoor Siren did not receive the signal from the Panel. Please check whether SR-35-BUS is connected properly to the Panel within appropriate wiring distance.
{% endhint %}

## **Walk Test**

* To make sure the Wired Indoor Siren is able to communicate with the Panel after it is learned-in, place the Control Panel in Walk Test mode and press the learn button on SR-35-BUS to transmit a test signal to the Control Panel.
* When the Panel receives the test signal, it will beep once and display the siren’s information accordingly on the top of the device list.

{% hint style="warning" %}
Note:

If there is no response from the Panel after the press of learn button, it means the Panel did not receive the test signal from the device.Please check whether SR-35-BUS is connected properly to the Panel within appropriate wiring distance.
{% endhint %}

## **Installation**

Step 1. Find the location where the Wired Indoor Siren is to be mounted.

Step 2. Use the mounting bracket as a template to drill 3 holes on the wall for plugs.

Step 3. Push in the plugs and screw the mounting bracket on the wall with 3 screws.

Step 4. Hook the Siren onto the mounting bracket and then push downwards until you hear a click sound.

{% hint style="warning" %}
Note:

* Please make sure the device is properly hooked onto the mounting bracket, so that the tamper switch is fully depressed.
{% endhint %}

Step 5. Check if the installation is successful by testing from the Control Panel with arming and disarming function.

Successful arming/disarming will be indicated by the table provided above in **Audio Status Indication** section.

{% hint style="warning" %}
Note:

If 5 short beeps are noticed while arming/disarming, it means the tamper is not fully depressed. Check to ensure that tamper is properly set and test from Control Panel again.
{% endhint %}

Step 6. The installation is now complete.
