# VESTA-480

PSS-29-R2

## Power Switch&#x20;

<figure><img src=".gitbook/assets/image (1380).png" alt=""><figcaption></figcaption></figure>

## Introduction

The Power Switch is designed for the user to remotely turn on/off an appliance that is attached to it.

The integration of the Power Switch into your home automation system will allow you to control home appliances with ease.

## Parts Identification

### Test Button aka LED indicator

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

* Press the button to toggle on/off the Power Switch.
* Press and hold the button for 3 seconds to send a learn code.
* Press and hold the button while powering on the Power Switch, then release the button when the LED lights up to factory reset.

## Getting Started

{% stepper %}
{% step %}
### Plug in the Power Switch

Plug the Power Switch into the power outlet.
{% endstep %}

{% step %}
### Enable learning mode on the Control Panel

Put the Control Panel into learning mode.
{% endstep %}

{% step %}
### Send a learn code

Press and hold the Test button on the Power Switch for 3 seconds to send a learn code.
{% endstep %}

{% step %}
### Confirm learning mode

The LED will start to flash slowly, indicating that the Power Switch is in learning mode.
{% endstep %}

{% step %}
### Confirm the signal on the Control Panel

If the Control Panel receives the signal from the power switch, it will display the information accordingly. Refer to the Control Panel manual to complete the learn-in process.
{% endstep %}

{% step %}
### Complete the learning process

When the Power Switch receives the learning code from the Control Panel, the LED of the Power Switch will flash 3 times and then turn off to indicate that learning process is complete.
{% endstep %}
{% endstepper %}

{% hint style="info" %}
* After entering learning mode, the Power Switch will not automatically leave learning mode unlesss it receives acknowledgement from the Control Panel, or unless the Test button is pressed.
* If the Power Switch already exists in a Control Panel system, you will need to first remove the Power Switch from the Control Panel before you can learn it into a different Control Panel.
{% endhint %}

## Walk Test

To test whether the Power Switch is able to communicate with the Control Panel:

{% stepper %}
{% step %}
### Enable Walk Test mode

Put the Control Panel into Walk Test mode.
{% endstep %}

{% step %}
### Press the Test Button

Press the Test Button on the Power Switch. The Control Panel should display if the Power Switch is within the operation range (please refer to the operation manual of the Control Panel).
{% endstep %}
{% endstepper %}

## Supervision

* After the Power Switch is successfully learned in to the Control Panel, the device will automatically transmit supervisory signal along with ON/Off status to the Control Panel at random intervals of 30 to 50 minutes.
* If the Control Panel has not received the signal from the Power Switch for the preset period of time, the Control Panel will indicate on its display that the particular Power Switch is experiencing an out-of-signal problem.

## Operation

### Installation

Plug the Power Switch into a power outlet, then plug the appliance into the socket of the Power Switch. The appliance must be in ON status.

### Appliance Control

* After the Power Switch is successfully learned in to the Control Panel, the Control Panel can remotely turn on/off the Power Switch to control the appliance. Please refer to your Control Panel manual for details.
* You can also press the button on the Power Switch to toggle its on/off status
* If the Power Switch is removed from power outlet, after re-plugging the Power Switch, its previous on/off status will be transmitted to the Control Panel.

### Maximum Operation Load

* For 110V: the maximum operation load is 1760W and 16A.
* For 230V: the maximum operation load is 3680W and 16A.
* If the Power Switch is overheating, it will cut off power automatically as a safety measure. The LED indicator will flash quickly. After cut off, the Power Switch will resume normal operation if temperature drops below the threshold point.

{% hint style="warning" %}
**CAUTION**: Always switch off the power to the socket before plugging in or unplugging any electrical device to avoid electric shock or equipment damage.
{% endhint %}

## Factory Reset

Factory resetting the Power Switch will clear its memory and restore it to factory default settings.

To factory reset, press and hold the test button while powering on the Power Switch, then release the button when the LED lights up.
