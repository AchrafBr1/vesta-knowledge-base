# VESTA-217

RMB-29

## AC Powered Router (wireless F1 signal Extender)

<figure><img src=".gitbook/assets/image (104).png" alt=""><figcaption><p>VESTA-217</p></figcaption></figure>

## **Introduction**

RMB-29 is a wireless AC Powered Router with built-in backup battery. The “plug-n-play” design provides a quick and convenient deployment for your system. This wireless signal extender is designed to make your system more powerful by increasing the maximum possible distance and boosting signal latency into hard-to-reach areas. Moreover, it is also optimal for receiving and transmitting signals from the Control Panel, and vice versa.

## **Parts Identification**

**1. Test Button / LED Indicator**

![](<.gitbook/assets/0 (97).jpeg>)

Test Button Usage:

* Press once to exit current learning process.
* Learning into Control Panel & Learning Sensor into Router _(Please refer to the respective sections for more details.)_

LED Indicator (Green and Red):

<figure><img src=".gitbook/assets/1 (126).png" alt=""><figcaption></figcaption></figure>

## **Features**

### _**One-way/Two-way setting**_

The Router can operate as either a one-way device or two-way device. When programmed as a two-way device, the Router can receive acknowledgement from the Control Panel to ensure successful transmission. Please follow steps below to complete one-way/two-way setting.

**Step 1.** Plug the Router into the power socket. The Router will emit 1 long beep and the Green LED will be turned ON for one second.

**Step 2.** Press and hold the test button for 10 seconds. Release the button when you hear 3 beeps.

**Step 3.** The Router will enter “Setting Mode” for 5 seconds.

**Step 4.** Within 5 seconds press the test button to set the router as one-way or two-way device. The router will emit 2 beeps if setting as two-way device is complete; the router will emit a long beep if setting as one-way device is complete.

* In “Setting Mode”, each test button press will reset the Setting Mode time to another 5 seconds. After 5 seconds of inactivity, the router will emit 2 beeps and return to normal mode.

**Step 5.** After you complete one-way/two-way device setting, please learn in/re-learn in the router into the Panel for the updated setting to take effect.

### _**Learning into Control Panel**_

**Step 1.** To learn the Router into the Control Panel, plug the Router into the power socket. The Router will emit 1 long beep and the Green LED will be turned ON for one second.

**Step 2.** Put the Control Panel into learning mode.

**Step 3.** Press and hold the test button for 5 seconds. Release the button when you hear 2 beeps. **Step 4.** The Router will enter “Learning into Control Panel” process and emit one long beep. The Red

LED will be steady ON.

**Step 5.** If the Router successfully receives the signal within 60 seconds from the Control Panel, it will emit 3 beeps. The Red LED will be OFF and return to normal mode.

{% hint style="warning" %}
Note:

To exit the current “Learning into Control Panel” process, press the test button once and the Router will emit 2 beeps. The Red LED will be OFF and return to normal mode.
{% endhint %}

### _**Learning Router into Router**_

To learn Router A into Router B:

**Step 1.** Press the test button of Router B for 3 seconds. Release the button when Router B emits one beep. Router B will enter “Learning Router/Sensor into Router” process and emit one long beep. The Green LED will begin to flash.

**Step 2.** Press the test button of Router A once to send a learn code to Router B.

**Step 3.** When Router B receives signal sent from Router A, it will emit one long beep to confirm. If Router A has already been added to Router B, Router B will emit 2 beeps to notify the user.

{% hint style="warning" %}
Note:

* To exit the current “Learning Router/Sensor into Router” process, press the test button once and the Router will emit 2 beeps and return to normal mode.
* Please do not cross-learn the Routers, e.g. Learning Router A into Router B and learning Router B into Router A.
* All Routers will have to be learnt into the Control Panel.
{% endhint %}

### _**Learning Sensor into Router**_

**Step 1.** To learn a sensor into the Router, press and hold the test button of the Router for 3 seconds. Release the button when the Router emits one beep. The Router will enter “Learning Router/Sensor into Router” process and emit one long beep. The Green LED will begin to flash.

**Step 2.** Please refer to the device manuals on how to send learn code from the devices.

**For PIR Camera, please press the test button once to send a learn code to the Router.**

**Step 3.** When the Router receives signal sent from sensor, it will emit one long beep to confirm. If the sensor had already been added to the Router, it will emit 2 beeps to notify the user.

**A maximum of 60 devices (including routers) can be learnt into the Router, and up to 8 PIR cameras are supported. If the user attempts to learn in a 61st device, the Router will emit 4 beeps.**

{% hint style="warning" %}
Note:

* To exit the current “Learning Router/Sensor into Router” process, press the test button once and the Router will emit 2 beeps and return to normal mode.
* If multiple routers are used, please only learn devices into the router(s) closest to the operation areas of the devices.
* All the devices learnt into the router must also be learnt into the Control Panel.
{% endhint %}

### _**Operation**_

If the Router receives signal from a device, the Green LED will flash once and retransmit the signal to the Control Panel. The Red LED will flash once in transmission mode.

If the Router receives a signal from the Control Panel, the signal will be retransmitted to the corresponding device(s) from the Router.

{% hint style="warning" %}
Note:

If the user fails to learn a sensor into the Control Panel first, the signal received cannot be retransmitted to the Control Panel. The Green LED will flash once and the device will emit 4 beeps.
{% endhint %}

### _**Power Supply**_

The Router is powered by AC power. Plug the Router into a power socket to activate the Router. There is a rechargeable battery inside the Router that serves as a backup in case of a power failure. It takes approximately 72 hours to fully charge the battery. During normal operation, AC power is used to power the Router and at the same time recharge the battery.

### _**Battery and Low Battery Detection**_

The Router is powered by four AAA 1.2V Ni-MH rechargeable batteries. After AC power failure, the Router will transmit a Low Battery signal to the Control Panel when low battery voltage is detected. To restore battery, re-plug AC power into the power socket.

### _**AC Failure Detection**_

Whenever the Router is removed from the power socket, the Router will transmit an AC Failure signal to the Control Panel to notify the situation. When the Router is re-plugged onto the power socket, it will transmit an AC restoration code.

### _**Supervision**_

After learnt into the Control Panel, the Router will automatically transmit Supervisory Signals every 30 to 50 minutes when working as a one-way device.

The Router will automatically transmit Supervisory Signals every 90 to 120 minutes when working as a two-way device.

### _**Factory Reset**_

Factory Reset function will clear all learnt-in device and Control Panel. To reset the Router, please follow steps below:

**Step 1.** Press and hold the test button for 3 seconds. Release the button when the Router emits one beep.

**Step 2.** The Router will enter “Learning Sensor into Router” process and emit one long beep. The Green LED will begin to flash.

**Step 3.** Press and hold the test button for another 5 seconds. Release the button when you hear 3 beeps.

**Step 4.** Factory reset is complete. All learn-in devices and Control Panel are cleared from the Router.

### _**Recommendations**_

It is strongly suggested to keep a distance between each router and the Control Panel to avoid cross signaling.

If a particular device is within an acceptable range for Control Panel to receive its transmission signal, it is strongly recommended to learn the device into the Control Panel directly instead of into the Router.

When cascading routers to form a transmission relay, it is strongly recommended to link not more than 2 layers of routers.

{% hint style="warning" %}
Note:

* For devices that are directly controlled by the Panel to turn on/turn off, e.g. power switches, power meter switches, valve controllers, Roller Shutter Controls, or Input and Output Switches, please link **only one layer** of router(s).
* For keypad, it is also recommended to link **only one layer** of router(s).
{% endhint %}

### **Multiple Routers**

If multiple routers are used, please follow the guidelines below for the optimum performance:

1. When linking routers to form a transmission replay, it is recommended to link not more than two layers of routers.

From the example below (Device to B to A to Control Panel), Router A, Router B, and the Device all need to be learned into the Control Panel.

The Device needs to be learned into its closest router (Router B). Router B needs to be learned into Router A. (Do not learn Router A into Router B.)

Example:

![](<.gitbook/assets/13 (31).jpeg>)

1. If a device is located between the RF coverage of multiple routers and the Control Panel:&#x20;
   * Example 1:

![](<.gitbook/assets/14 (27).jpeg>)

From the displayed diagram, the device is located between the RF coverage areas of Router B and C. Users can choose to learn the device into Router B only, learn into Router C only, or learn into both Routers B and C.

It is **recommended** to learn the device into Router B only (and not to Router C) to reduce signal traffic.

{% hint style="warning" %}
Note:

For the above system, Router C is also learnt into Router A or B or both so the signals from Router C can be relayed to the Control Panel through Router A or B, or either.
{% endhint %}

Example 2:

![](<.gitbook/assets/16 (17).jpeg>)

From the displayed diagram, the device is located between the RF coverage areas of Router A, B and C. Users can choose to learn the device into Router A only, learn into Router B only, learn into Router C only, or learn into Routers A, B and C.

It is **recommended** to learn the device into Router A only or Router B only (and not to Router to reduce signal traffic).

{% hint style="warning" %}
Note:

For the above system, Router C is also learnt into Router A or B or both so the signals from Router C can be relayed to the Control Panel through Router A or B, or either.
{% endhint %}

Typically, most devices stay in the same RF coverage area. For the exceptions such as a Remote Controller, please learn the device into all Routers (and Control Panel) of the system.



## **Features**

***

* Extends wireless RF communication range into hard-to-reach areas
* Plugs into a standard power outlet for easy deployment
* Multiple regional plugs available
* Provides rechargeable backup battery lasting 24 hours
* AC failure detection
* Compatible with Climax F1 PIR Motion Sensor Camera (such as VST-862 Series / VST-892 Series, etc.)
* Dual-color LED status indicator
* Elegant and compact design for unobtrusive deployment
* Regular supervision signals to check system integrity
* Low battery detection
* Suitable for residential and commercial premises

## **Specifications**

***

* Frequency: 433MHz / 868MHz / 869MHz
* Power Source: 100\~240V, 50/60Hz
* Backup Battery: 600mAH Ni-MH AAA Rechargeable battery x 4
* Backup Battery Life: 10 hours (rechargeable)
* Operating Temperature: -10°C to 45°C (14°F to 113°F)
* Operating Humidity: Up to 85% non-condensing
* Dimensions: 95mm x 63mm x 83mm (power plug included)、95mm x 63mm x 46mm (power plug not included.
