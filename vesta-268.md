# VESTA-268

EMD-1ZW

<figure><img src=".gitbook/assets/image (465).png" alt=""><figcaption></figcaption></figure>

## Specification:

* Communication protocol: 500 series Z-Wave Plus module
* Frequency: 868.40 MHz
* Accuracy: ±5%.
* Power supply: 2 x 1.5V AA alkaline batteries
* Battery life: 2 years
* Operating Temperature: -10°C \~ +45°C
* Operating Humidity: Up to 85% (non-condensing)
* Dimensions: 46 (W) x 90 (H) x 30 mm

## Introduction

The Energy Meter is a Z-Wave Electricity Power reader designed to be used with a digital watt hour meter supporting LED pulse output port. The E-meter reads the LED pulse from the watt hour meter and transmits the data to a Z-Wave network coordinator.

The Energy Meter is a Z-Wave enabled device and is fully compatible with any Z-Wave enabled network.

Z-Wave is a wireless communication protocol that uses a low-power RF radio. By taking advantage of the Z-Wave mesh network, commands can be routed to their destination via intermediary “listening” Z-Wave products.

***

### Parts Identification

<figure><img src=".gitbook/assets/image (462).png" alt=""><figcaption></figcaption></figure>

#### 1. LED indicator

The LED indicator lights up in the following conditions:

* Flashes once: The Energy Meter is transmitting a signal.
* Flashes twice: The Energy Meter is successfully added into a Z-Wave network.

#### 2. Mounting Holes

#### 3. Battery compartment Cover

Remove the cover to insert 2 Alkaline AA 1.5V batteries to power up the Energy Meter.

#### 4. LED Sensor Jack

Plug the Sensor into this jack to receive LED signal from the watt hour meter.

#### 5. Function Button

* Press the button 3 times within 1.5 seconds to send a learn code.
* Press and hold the button for 10 seconds to factory reset.

#### 6. LED Sensor

Attach the LED sensor to the watt hour meter, and plug into the LED sensor Jack on the E-Meter to read data from the watt hour meter.

***

## Features

### Battery and Low Battery Detection

The Energy Meter uses 2 Alkaline 1.5V batteries as its power source. It features Low Battery Detection: when the battery voltage is low, the Energy Meter will transmit a Low Battery signal to notify the Z-Wave network coordinator.

The Energy Meter reports its battery percentage to the Control Panel at 100%, 75%, 50%, and 25%. If the battery voltage is low (25%), a Low Battery signal will be sent to the Control Panel.

When changing battery, after removing the old batteries, press the function button a couple times to fully discharge before inserting new batteries.

### Adding Device (Inclusion)

This product can be included and operated in any Z-Wave network with other Z-Wave certified devices. All non-battery operated nodes within the network will act as repeaters regardless of vendor to increase reliability.

{% stepper %}
{% step %}
### Prepare

* Insert batteries to power on the E-meter.
* Put the Z-Wave control panel into Inclusion mode (please refer to the Z-Wave control panel manual).
{% endstep %}

{% step %}
### Include

* Within 1.5 seconds, press the Function Button 3 times.
* Refer to operation manual of the Z-Wave Gateway or Control Panel to complete the adding process.
{% endstep %}

{% step %}
### Troubleshooting

If the device has already been included into another Z-Wave Gateway/Control Panel, or if the device is unable to be added into the current Z-Wave Gateway/Control Panel, try removing it first (**see Removing Device**).
{% endstep %}
{% endstepper %}

### Removing Device (Exclusion)

The device must be removed from an existing Z-Wave network before being added into another.

**Exclusion Mode**

* Put the Z-Wave Gateway or Control Panel into Exclusion mode (please refer to the Z-Wave or control panel manual).
* Within 1.5 seconds, press the Function Button 3 times — the device will be removed from the Z-Wave network.

**Factory Reset**

Factory resetting the device will restore it to factory default settings (i.e., not included into any Z-Wave network). Only use this if the Z-Wave Gateway or Control Panel is lost or otherwise inoperable.

* Press and hold the Function Button of the device for 10 seconds to factory reset.

***

## Operation

### Installation

**Watt Hour Meter connection**

A washer with double-side adhesive tape is provided to connect the LED sensor to the watt hour meter.

1. Locate the LED pulse output port on the watt hour meter, remove the double-side adhesive tape cover on the washer and apply the washer around the LED port.

<figure><img src=".gitbook/assets/image (463).png" alt=""><figcaption></figcaption></figure>

2. The LED sensor head has a built-in magnet. Apply the LED sensor head to the washer to attach the sensor to   &#x20;LED port for reading LED pulse from watt hour meter.

<figure><img src=".gitbook/assets/image (464).png" alt=""><figcaption></figcaption></figure>

#### Wall Mounting

The Energy Meter has two mounting holes on the back for wall mounting.

{% stepper %}
{% step %}
Mark the mounting location on the wall according to the mounting hole position.
{% endstep %}

{% step %}
Install two screws at the mounting location.
{% endstep %}

{% step %}
Hook the Energy Meter onto the screws.
{% endstep %}
{% endstepper %}

***

### Energy Consumption Monitor

* The Energy Meter reads LED pulse from the watt hour meter to monitor energy consumption.
* The Energy Meter will transmit current wattage every 5 minutes to the Z-Wave Gateway/Control Panel.
* The Energy Meter transmits power data to the coordinator whenever accumulated power usage increases by 1 kW·hr.

To clear the Energy Meter of its accumulated power consumption data:

{% stepper %}
{% step %}
Remove the batteries to power down.
{% endstep %}

{% step %}
Press and hold the function button and reinsert batteries while still holding the button.
{% endstep %}

{% step %}
Keep holding the button and release after 3 seconds. The accumulated power consumption data will be cleared.
{% endstep %}
{% endstepper %}

***

### Z-Wave Information

**Device Type:** Whole Home Meter - Simple

**Role Type:** Listening Sleeping Slave (LSS)

**Maximum number of devices that can be added to the group:** 3

#### Command Class Support / Control

**Mandatory CC Support:**

* Association CC, v2
* Association Group Information CC
* Battery CC
* Device Reset Locally CC
* Manufacturer Specific CC, v2
* Meter CC, V2
* Version CC, v2
* Z-Wave Plus Info CC, v2
* Power Level CC
* Firmware Update CC, v2
* CRC16 Encap CC

#### Z-Wave Groups (Association Command Class Version 2)

Group 1 — “LifeLine”:

* Battery CC (COMMAND\_CLASS\_BASIC)
* Device Reset Locally CC
* Meter CC

***
