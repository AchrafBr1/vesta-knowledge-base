# VESTA-060N

**Door Contact / Shock Sensor (DCSV-29-2W)**

DCSV-29-2W is a Door Contact / Shock Sensor that is capable of sending wireless signals to the Control Panel upon detection of door/window opening or window glass break & shock detection.

The Door Contact / Shock Sensor design consists of a cover and base. The cover contains all electronics and the base provides a means for fixing the device. An enclosed PCB tamper switch provides tamper protection against unauthorized device opening and/or removal.

![](<.gitbook/assets/0 (52).jpeg>)

<figure><img src=".gitbook/assets/image.png" alt=""><figcaption></figcaption></figure>

## **Parts Identification**

1. **LED Indicator / Test Button**
   * Press the button once to send a learn code or enter test mode for 3 minutes.
2. **Cover Fixing Screw**
3. **Mounting Holes**
4. **Tamper Switch**
   * Provides tamper protection against unauthorized device opening and/or removal from mounting surface.
5. **Battery Insulator**
6. **Battery Compartment**
7. **Magnet**
8. **Magnet Screw hole**
9. **Magnet Spacer**

**Features**

## _**LED Indicator**_

* In Normal Operation Mode, the LED will not light up when the device is activated.
* When the device battery voltage is low, the LED will flash quickly when the device is triggered.
* When the tamper switch is triggered, the LED will flash quickly. When a tamper condition persists, the LED will flash quickly whenever the device is triggered. (For Door Contact activation only).
* When under Test mode, the LED will flash quickly every time the device is triggered.
* When the battery is exhausted, the LED will flash every 4 seconds.
* The LED will not flash if the device tamper and battery are normal and is not under test mode.
* If the LED flashes to indicate signal transmission, it will flash twice rapidly upon receiving acknowledgement from panel.
* When the programming command from the Control Panel is successfully received, the LED will turn brighter and then turn dark.

## _**Door Opening Detection & Shock Detection**_

The device is triggered by door/window opening or a shock detection which exceeds detection threshold.

## _**Materials of Mounting Surface**_

The device supports shock detection on various materials including glass, wood, metal, and concrete. After installation, you can select the material of mounted surface on the Control Panel. <mark style="color:blue;">The default is set as Wood.</mark>

## _**Sensitivity**_

* The sensitivity required to activate the Door Contact / Shock Sensor is determined from the Control Panel.
* Three sensitivity levels are selectable: **Low**, **Medium**, and **High**. <mark style="color:blue;">The default is set as</mark> <mark style="color:blue;"></mark><mark style="color:blue;">**Medium**</mark><mark style="color:blue;">.</mark>

## _**Battery**_

* The Door Contact / Shock Sensor uses one CR123 3V Lithium battery as its power source. The battery is installed in the battery compartment with a battery insulator inserted. To activate the battery, simply pull out the battery insulator.
* The Door Contact / Shock Sensor can detect low battery condition. When the battery voltage is low, a low battery signal will be sent to the Control Panel to notify the condition. The LED will light up when the Door Contact / Shock Sensor is activated under low battery status. When the battery is exhausted, the Door Contact / Shock Sensor will stop all function, the LED will flash every 4 seconds.
* When changing batteries, after removing the old batteries, press the Tamper Switch twice to fully discharge before inserting new batteries.

## _**Tamper Protection**_

* The Door Contact / Shock Sensor is protected by a tamper switch which is compressed against the mounting surface when the Door Contact / Shock Sensor is mounted. Whenever the Door Contact / Shock Sensor is removed from mounted surface or cover is opened, the tamper switch will be activated and the device will send a tamper open signal to remind the user of the condition.
* The tamper open signal will be transmitted with the Door Contact to the Control Panel. The tamper fault status will be displayed only in the DC device zone in the Control Panel.

## _**Supervision**_

* When in normal operation, the Door Contact and Shock Sensor will send a supervision signal to the Control Panel separately at random intervals of 90-110 minutes.
* If the Control Panel has not received the supervision signal from the Door Contact / Shock Sensor for a preset period time, the Control Panel will indicate the particular Door Contact / Shock Sensor is experiencing an out-of-signal problem.

## _**Test Mode**_

* Under Normal Mode, press the Test Button to transmit a test signal and learning code to the Control Panel. The Door Contact / Shock Sensor will also enter the Test Mode for 3 minutes.
* Under Test Mode, the LED will light up whenever the Door Contact / Shock Sensor is activated.
* Each additional Test Button press will reset Test Mode time to 3 minutes.

## _**Getting Started**_

* Remove the battery insulator on the Door Contact / Shock Sensor to power on.
* Put the Control Panel into Learning Mode (Please refer to panel operation manual)
* Press the Test Button on the Door Contact / Shock Sensor.
* Refer to your Control Panel operation manual to complete the learn-in process.
* When learnt into the Control Panel, the DCSV-29-2W will be recognized as 2 separate devices (Door Contact & Shock Sensor) and will occupy 2 zones in the Panel.
* Set the Material & Sensitivity Level:

1. Press the Test Button on DCSV-29 for more than 3 seconds. The LED will turn on, indicating that the device is now under programming mode. (If no action within a 10-second timeout, DCSV-29 will automatically exit programming mode and return to Test Mode.)
2. Select the material and sensitivity level from the Control Panel webpage (Sensor Stting page).

<figure><img src=".gitbook/assets/image (1).png" alt=""><figcaption></figcaption></figure>

3. When DCSV-29 receives programming command from the Control Panel, the LED will first turn off, and then turn brighter and turn dark. Material & Sensitivity level setting are now complete.

## _**Walk Test**_

* After the Door Contact / Shock Sensor is learned-in, place the Control Panel into (**Walk Test**) mode, hold the Door Contact / Shock Sensor in the desired location, and press the Test Button to transmit test signal to Control Panel. If the Control Panel is within Door Contact / Shock Sensor signal range, the panel will display Door Contact / Shock Sensor information accordingly.
* Proceed with mounting and installation once you are satisfied that the Door Contact / Shock Sensor functions properly in the desired location.

## **Installation**

_**Mounting the Door Contact / Shock Sensor**_

### **Mounting as Door Contact:**

* The Door Contact / Shock Sensor should be installed with the rib-marked side facing the magnet.
* The distance between Door Contact / Shock Sensor and the magnet should be no more than 15 mm when the door is closed.
* Mount the device as high as possible.

![](<.gitbook/assets/15 (12).jpeg>)

### **Mounting as Shock Sensor:**

Refer to the table below for information about installation location and the thickness of different materials:

<table data-header-hidden><thead><tr><th></th><th></th><th></th><th width="169"></th><th></th></tr></thead><tbody><tr><td></td><td></td><td><strong>Glass Window</strong> </td><td><strong>Wood/Metal Door</strong> </td><td><strong>Concrete Wall</strong></td></tr><tr><td></td><td><mark style="color:green;"><strong>Thickness</strong></mark></td><td><mark style="color:green;">>5mm</mark> </td><td><mark style="color:green;">&#x3C;40mm</mark></td><td><mark style="color:green;">x</mark></td></tr><tr><td></td><td><mark style="color:orange;"><strong>Installation Location</strong></mark></td><td><mark style="color:orange;">Window Frame</mark> </td><td><mark style="color:orange;">Door</mark> </td><td><mark style="color:orange;">Wall</mark></td></tr><tr><td>Shock Detection Radius</td><td>Low Sensitivity</td><td>0.5M </td><td>0.5M </td><td>0.25M</td></tr><tr><td>Shock Detection Radius</td><td>Medium Sensitivity</td><td>1M </td><td>1M </td><td>0.5M</td></tr><tr><td>Shock Detection Radius</td><td>High Sensitivity</td><td>1.5M </td><td>2M </td><td>1M</td></tr></tbody></table>

![](<.gitbook/assets/16 (10).jpeg>)

### _**Mounting Procedure**_

1. Use the 2 mounting holes on back cover as template for positioning.
2. Use the provided wall plugs for window frames / concrete wall installation.
3. Screw the Door Contact / Shock Sensor into the wall plugs. (Drilling is recommended when mounting on steel, or you can also use the provided sticker in the package).
4. Fit magnet on the door using small piece of double sided adhesive tape or with provided screws.
5.  To mount the Magnet, use the 2 Magnet Screw holes as a template for appropriate hole positioning.

    _\<NOTE >_

    * The magnet must align with the rib-mark side of the Door Contact. If required, apply the magnet spacer to the back of the magnet to better align the magnet to the rib marks.
6. Screw the magnet and insert the two white caps into the magnet screw holes for aesthetic integrity.
7. Installation is now complete.

