# VESTA-034

**Gdts-1**

## **Garage Tilt Sensor**&#x20;

<figure><img src=".gitbook/assets/image (31) (1) (1).png" alt=""><figcaption></figcaption></figure>

The Garage Tilt Sensor monitors bi-direction tilting of overhead garage door. The Garage Tilt Sensor is fixed to the monitored device frame. When the door is open and the detected surface is tilted less than or equals to 35°(+-10) degrees, or when the door is closed and the detected surface is tilted more than or equals to 55°(+-10) degrees, the Garage Tilt Sensor will transmit alarm signal to the Control Panel. The device also has the capabilities of communicating signal problems along with low battery situations.

The Garage Tilt Sensor design consists of a cover and base. The cover contains all electronics and the base provides a means for fixing the device. An enclosed PCB tamper switch provides tamper protection against unauthorized device opening and/or removal.

## **Parts Identification**

![](<.gitbook/assets/0 (41).jpeg>)

1. **Test Button / LED Indicator**

**Test Button:**

* Press the Test button to transmit a learning code.
* Press the Test button to enter test mode for 3 minutes.

**LED Indicator:**

* The LED will flash for 3 times when it is transmitting a learning code.
* The LED will light up whenever the device is triggered under Test Mode.
* The LED will light up whenever the tamper switch is activated.
* (Door opened) When experiencing device fault or under Test Mode, the LED will flash for 6 times.
* (Door closed) When experiencing device fault or under Test Mode, the LED will flash for 6 times. After 10 seconds, the LED will flash for 3 times.

2. **Mounting Holes**

* Used to fix and screw the Garage Tilt Sensor directly on the top of the garage door.

3. **Tamper Switch**

* When the Garage Tilt Sensor is mounted, the Tamper Switch will be fully compressed against the wall. When the device cover is opened or when it is removed from the mounted surface, the Tamper Switch will be activated. The LED will flash for 6 times and send a tamper open signal to notify user(s) of this condition.

4. **Battery Insulator**
5. **Battery Compartment**

## **Features**

* _**LED Indicator**_
  * In Normal Operation Mode, the LED will light up when the Garage Tilt Sensor is activated (device opened or closed).
  * When the device cover is opened or when the Tamper Switch is triggered, the LED will light up.
  * When the Garage Tilt Sensor is in Test mode, the LED will light up every time it is activated.
  * The LED will light up when the Garage Tilt Sensor is activated under low battery status. When the battery is exhausted, the Garage Tilt Sensor will stop all function, the LED will flash every 4 seconds.
* _**Battery**_
  * The Garage Tilt Sensor is powered by one CR123 3V Lithium battery. Please note: **ALWAYS** replace battery with the correct size and voltage.
  * The Garage Tilt Sensor can detect low battery condition. When the battery voltage is low, a low battery signal will be sent to the Control Panel to notify user(s) of this condition. When the battery is exhausted, the LED will flash every 4 seconds and the device will stop functioning.
  * When replacing a new battery, remove the old battery first. Press the Tamper Switch twice to fully discharge before inserting a new battery.
* _**Getting Started**_
  * Pull out the battery insulator to provide power to the device.
  * Put the Control Panel into Learning Mode (please refer to Control Panel operation manual for detail).
  * Press the Test Button of the Garage Tilt Sensor to send a learning code, the LED will flash for 3 times.
  * Refer to your Control Panel operation manual to complete the learn-in process.
  * After the Garage Tilt Sensor is learned-in, place the Control Panel into Walk Test mode, hold the Garage Tilt Sensor in a desired location, and press the Test button to transmit test signal to Control Panel. If the Control Panel is within Garage Tilt Sensor signal range, the panel will display Garage Tilt Sensor information accordingly.
  * Ensure the Garage Tilt Sensor is within signal range of the Control Panel prior to mounting and installation process.
* _**Test Mode**_
  * The Garage Tilt Sensor can be put into a 3-minute Test Mode by pressing the Test Button (aka LED Indicator) on the front cover.
  * Under Test Mode, the LED will light up whenever the Garage Tilt Sensor is activated.
  * To extend Test Mode timer for another 3 minutes, simply press the Test Button.
* _**Tamper Switch**_
  * The Garage Tilt Sensor will be protected by a tamper switch when it is mounted flush against the mounting surface. When the device is removed from the mounting surface or when the device cover is opened, its tamper switch will be activated. The device will then send a tamper open signal to the Control Panel to notify user(s) of this condition.
* _**Supervisory Signal**_
  * The Garage Tilt Sensor will transmit Supervisory Signal to the Control Panel at random intervals of 30-50 minutes.
  * If the Control Panel fails to receive any supervisory signals from the Garage Tilt Sensor over a preset period of time, an “Out-Of-Order” fault message will be generated.

## **Installation**

* _**Installation Guideline & Recommendations**_

**Guideline:**

* The Garage Tilt Sensor should be installed on garage door. When the door is open and the detected surface is tilted less than or equals to 35°(+-10) degrees, or when the door is closed and the detected surface is tilted more than or equals to 55°(+-10) degrees, the Garage Tilt Sensor will transmit alarm signal to the Control Panel.

![](<.gitbook/assets/2 (30).jpeg>)

* The Garage Tilt Sensor should be mounted on the top panel of the garage door, as shown below.

![](<.gitbook/assets/3 (30).jpeg>)

**Recommendations:**

* The Garage Tilt Sensor is designed to be mounted on overhead garage door, not to be used on roll up garage door. Mount the detector at 1.8 meter height for optimal performance.
* The device shall be mounted vertically with the ground and shall be no greater than +-5 degrees when mounted.
* Mount the device on a dry and clean surface. Ensure the device is mounted with the LED indicator on top.
* _**Mounting the Garage Tilt Sensor**_

There are two ways to mount the Garage Tilt Sensor. Ensure the location is within signal range of the Control Panel and follow steps below to proceed:

**Screw Mounting:**

* Find a suitable location to install the Garage Tilt Sensor. The mounting surface should be clean and dry. Clean the mounting surface thoroughly if needed.
* Use the two mounting holes as a template to mark and drill mounting holes.
* Use the provided wall plugs for plaster/brick installation. Screw the Garage Tilt Sensor into the provided wall plugs. Ensure the wall plugs are flush with the wall.

{% hint style="warning" %}
Note:

Only use this type of mounting method when the garage doors are thicker than the screws
{% endhint %}

**Adhesive Mounting:**

* Find a suitable location to install the Garage Tilt Sensor. The mounting surface should be clean and dry. Clean the mounting surface thoroughly if needed.
* Remove the protective covering from one side of the double-sided adhesive pad. Apply it to the back of the Garage Tilt Sensor and press firmly for 30 seconds to ensure good contact.
* Remove the other side of the adhesive tape and firmly press the Garage Tilt Sensor onto a desired location for another 30 seconds. Please avoid applying the adhesive pad on uneven surface or re-applying it for optimal detection performance.
