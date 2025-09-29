# VESTA-222

**PSM-29-F1**

## **Power Switch Series**

<figure><img src=".gitbook/assets/image (8).png" alt=""><figcaption></figcaption></figure>



## **Introduction**

The Power Switch series is designed for the user to remotely turn on/off an appliance that is attached to it.

The Power Switch series includes the following models:

**PSS-29-F1:** Power Switch

**PSM-29-F1:** Power Switch with Meter

PSM-29-F1 model has a built-in power meter to measure electricity consumption. The collected energy data will be reported to the control panel.

The integration of the Power Switch into your home automation system will allow you to conveniently control home appliances for comfort or energy-saving purposes.

## **Parts Identification**

![](<.gitbook/assets/1 (89).jpeg>)

**1. Test Button aka LED indicator**

The Test Button also doubles as the LED Indicator. The test button is used to control the Power Switch. The LED indicator is used to indicate Power Switch status.

**LED Indication:**

The LED indicator lights up in the following conditions:

* On: The Power Switch is turned on.
* Off: The Power Switch is turned off.
* Flashes twice: When powered on.
* Flashes slowly: Under learning mode.
* Flashes three times: When learning is successful.
* Flashes briefly: RF signal transmitting

**Test Button Usage:**

* Press the button to toggle on/off the Power Switch
* Press and hold the button for 3 seconds to send a learn code.
* Press and hold the button while powering on the Power Switch, then release the button when the LED lights up to factory reset

## **Getting Started**

Step 1: Plug the Power Switch into the power outlet.

Step 2: Put the Control Panel into learning mode.

Step 3: Press and hold the Test button on the Power Switch for 3 seconds to send a learn code.

Step 4: The LED will start to flash slowly, indicating that the Power Switch is in learning mode.

Step 5: If the Control Panel receives the signal from the power

switch, it will display the information accordingly. Refer to the Control Panel manual to complete the learn-in process.

Step 6: When the Power Switch receives the learning code from the Control Panel, the LED of the Power Switch will flash 3 times and then turn off to indicate that learning process is complete.

{% hint style="warning" %}
Note:

* After entering learning mode, the Power Switch will not automatically leave learning mode unlesss it receives acknowledgement from the Control Panel, or unless the Test button is pressed.
* If the Power Switch already exists in a Control Panel system, you will need to first remove the Power Switch from the Control Panel before you can learn it into a different Control Panel.
{% endhint %}

### **Walk Test**

To test whether the Power Switch is able to communicate with the Control Panel:

* Put the Control Panel into Walk Test mode.
* Press the Test Button on the Power Switch.
* The Control Panel should display if the Power Switch is within the operation range (please refer to the operation manual of the Control Panel).

### **Supervision**

* After the Power Switch is successfully learned in to the Control Panel, the device will automatically transmit supervisory signal along with ON/Off status to the Control Panel at random intervals of 30 to 50 minutes.
* If the Control Panel has not received the signal from the Power Switch for the preset period of time, the Control Panel will indicate on its display that the particular Power Switch is experiencing an out-of-signal problem.

## **Operation**

### _**Installation**_

* Plug the Power Switch into a power outlet, then plug the appliance into the socket of the Power Switch. The appliance must be in ON status.

### _**Appliance Control**_

* After the Power Switch is successfully learned in to the Control Panel, the Control Panel can remotely turn on/off the Power Switch to control the appliance. Please refer to your Control Panel manual for details.
* You can also press the button on the Power Switch to toggle its on/off status
* If the Power Switch is removed from power outlet, after re-plugging the Power Switch, its previous on/off status and current energy output data (PSM-29-F1 only) will be transmitted to the Control Panel.

### _**Energy Consumption Monitor (For PSM-29-F1 Only)**_

With a built-in power meter to measure electricity consumption, the PSM-29-F1 Power Meter Switch will transmit power consumption data to the Control Panel when:

* When the Power Meter Switch is turned On/Off.
* Whenever the Power Switch energy output changes by +/- 2W.
* Whenever accumulated power usage increases by 0.2kW/hr.

### _**Maximum Operation Load**_

* For 110V: the maximum operation load is 1760W and 16A.
* For 230V: the maximum operation load is 3680W and 16A.
* If the Power Switch is overheating, it will cut off power automatically as a safety measure. The LED indicator will flash quickly. After cut off, the Power Switch will resume normal operation if temperature drops below the threshold point.

{% hint style="warning" %}
Note:

The maximum operation load of _**Type B**_ is 110V, 1650W, and 15A which is different from the maximum operation load for 110V and 230V stated above.
{% endhint %}

### **Factory Reset**

* Factory resetting the Power Switch will clear its memory and restore it to factory default settings.
* Press and hold the test button while powering on the Power Switch, then release the button when the LED lights up to factory reset.
