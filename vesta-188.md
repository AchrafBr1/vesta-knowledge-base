# VESTA-188

## **UPIC-5ZBS Infrared Universal Remote Control**

## **Introduction**

UPIC5-ZBS is a ZigBee Infrared Remote Control. It is designed to operate your home appliances by transmitting IR signal. The IR Remote Control is capable of learning IR signal transmitted from the appliance’s remote control. After learning the signal, you can remotely control the IR Remote Control via ZigBee network to send signal to appliance without using the remote control manually and support Over-the-Air (OTA) firmware update capability. The IR Remote Control utilizes ZigBee technology for wireless signal transmission. ZigBee is a wireless communication protocol that is reliable and has low power consumption and high transmission efficiency. Based on the IEEE802.15.4 standard, ZigBee allows a large amount of devices to be included in a network and coordinated for data exchange and signal transmission.

The IR Remote Control serves as an end device in the ZigBee network. It can be included in the ZigBee network to transmit signal upon activation, but cannot permit any other ZigBee device to join the network through the device itself.

## **Parts Identification**

![](<.gitbook/assets/0 (85).jpeg>)

1.  **IR Eye**

    Transmits IR signal to appliances.
2. **ZigBee Button**
3. **IR Button**
4.  **ZigBeeLED**

    Flashes twice –IR Remote Control successfully joins ZigBee network&#x20;

    Flashes every 20 minutes – IR Remote Control has lost connection to its current ZigBee network.
5.  **IR Indicator LED**

    Slow Flash –IR Remote Control under IR learning mode.

    Quick Flash–IR Remote Control receives IR signal under learning mode or is transmitting IR signal

    Flash every half second – IR data cleared

    Off :&#x20;

    1. &#x20;IR Remote Control is storing received IR signal under learning mode.
    2. &#x20;IR Remote Control is in idle mode.
6. **IR Signal Receiver**
7. **Low IR Transmission Power Jumper (JP1)**

**Jumper On** :The jumper link is inserted connecting the two pins

IR Transmission power set to Low. **(Factory Default)**

<div align="left"><figure><img src=".gitbook/assets/image (210).png" alt="" width="71"><figcaption></figcaption></figure></div>

**Jumper Off:** if the jumper link is removed or “**parked**” on one pin.

Jumper OFF – Deselected.

<div align="left"><figure><img src=".gitbook/assets/image (211).png" alt="" width="67"><figcaption></figcaption></figure></div>

8. **High IR Transmission Power Jumper (JP2)**

Jumper ON –IR Transmission power set to High.

Jumper OFF – Deselected.

{% hint style="info" %}
**IMPORTANT NOTE:**&#x20;

**JP1 and JP2 jumper CANNOT be set to ON at the same time**
{% endhint %}

9.  **Dip Switch Set 1**

    For setting appliance type
10. **Dip Switch Set 2**

    For learning and testing IR signal
11. **Battery Compartment**
12. **Wall Mounting Rotational Bracket (Optional)**

## **Features**

### _**Battery and Low Battery Detection**_

The IR Remote Control uses two 1.5V Lithium batteries as its power source. It features Low Battery Detection function. When low battery voltage is detected, the IR Remote Control will transmit Low Battery signal to the coordinator in ZigBee network.

### _**Supervision**_

The IR Remote Control will transmit a supervision signal to report its condition regularly according to user setting. The factory default interval is 30 minutes. The user can also press the ZigBee Button once to transmit a supervision signal manually.

## **ZigBee Network Setup**

### _**ZigBee Device Guideline**_

The IR Remote Control is a wireless communication protocol that is reliable and has low power consumption and high transmission efficiency. Based on the IEEE802.15.4 standard, ZigBee allows a large amount of devices to be included in a network and coordinated for data exchange and signal transmission.

Due to the fundamental structure of ZigBee network, ZigBee device will actively seek and join network after powering on. Since performing a task in connecting network may consume some power, it is required to follow the instructions to avoid draining battery of a ZigBee device.

* Ensure the ZigBee network router/coordinator is powered on before inserting battery into ZigBee device.
* Ensure the ZigBee network router/coordinator is powered on and in range while ZigBee device is in use.

-Do not remove a ZigBee device from the ZigBee network router or coordinator without removing the battery from a ZigBee device.

### _**Joining the ZigBee Network**_

As a ZigBee device, the IR Remote Control needs to join a ZigBee network to receive command from ZigBee network coordinator to transmit IR signal. Please follow the steps bellow to join the IR Remote Control into the ZigBee network.

1. Insert batteries to power on the IR Remote Control.
2. **P**ress and hold the ZigBee button for 10 seconds, then release it to join the network. Please make sure the permit-join feature on the router or coordinator of your ZigBee network is enabled.
3. After joining the ZigBee network, the IR Remote Control will be registered in the security system in the network automatically. Please check the security system control panel or CIE (Control and Indicating Equipment) to confirm if joining and registration is successful.
4. If the IR Remote Control successfully joins the ZigBee network, the ZigBee LED will flash twice to indicate.
5. After joining the ZigBee network, if the IR Remote Control loses connection to current ZigBee network, the ZigBee LED indicator will flash every 20 minutes. Please check the ZigBee network condition and the IR Remote Control signal range to correct the situation.

### _**Removing Device from ZigBee Network (Factory Reset)**_

To remove the device from current ZigBee network, the IR Remote Control must be put to Factory Reset to complete device removal. Factory Reset function will clear the IR Remote Control of its stored setting information and prompt the device to search for new ZigBee network.

**Before removing device, make sure the device is within current ZigBee network signal range**

1. Delete the IR Remote Control from current control panel / CIE.
2. Press and hold the function button for 10 seconds, then release the button to reset device.
3. Upon reset, the IR Remote Control will clear current ZigBee network setting and transmit signal to ZigBee coordinator to remove itself from current ZigBee network. It will then actively search for available ZigBee network again and join the network automatically.

### _**OTA Firmware Upgrade**_

* The device supports OTA firmware upgrade feature via ZigBee network, which can be initiated from the ZigBee network coordinator.
* Follow steps below to perform OTA firmware upgrade.

1. You have to access your ZigBee Coordinator to perform the firmware upgrade on the air.
2. On the configuration webpage, select the device that you wish to upgrade and select the new ZigBee firmware provided. Please refer to ZigBee Coordinator User Manual for detail.
3. Press OK to start upgrading process, please do not perform any other actions, or power down the panel.
4. The length of an upgrade will take approximately 20 to 30 minutes. Please note that the duration may vary based on file size or distance between your accessory and coordinator.
5. Wait for firmware to complete update. When the progress reaches 100%, the Device will reset automatically. You can also refresh the webpage again to ensure if the Device firmware is successfully updated with the newest version displayed.

## **IR Signal Learning and Testing**

In order to use the IR Remote Control to control your home appliance, , the IR Remote Control must first learn in the IR signal sent from the appliance’s remote control. Follow instruction below to complete the learning process.

**Please keep the IR Receiver away from direct lighting or sunlight during learning process to avoid interference.**

### _**Learning**_

**Step 1. Enter IR Learn Mode**

1. Follow instruction in **ZigBee Network Setup** section to join IR Remote Control into your ZigBee network.
2. Make sure all switches on the DIP Switch Block are set to **OFF** position.
3. Press and hold the IR button for 10 seconds and release when IR LED begins to flash.
4. The IR LED will begin flashing slowly to indicate the IR Remote Control is now enter ing IR Learn Mode.

![](<.gitbook/assets/6 (55).png>)

**Step 2. Select Appliance Type**

The IR transmitter can learn up to 5 sets of IR signal for 5 different appliances.

Before starting learning, select the appliance number with Dip Switch Set 1 before proceed to learning the signals. The IR signal learnt in will be assigned to selected appliance number.

Select the appliancetype according to following Dip Switch Set 1 table. For ease of recognition and operation from Climax ZigBee Control Panel, each device type has been given a display name on the Control Panel interface, we suggest you to learn in IR signals according to appliance types displayed.

<figure><img src=".gitbook/assets/image (212).png" alt=""><figcaption></figcaption></figure>

“X” means the location of this switch has no effect on appliance selection.

**Example:**

1. To select Air Conditioner, slide Switch 1 to ON, and Switch 2-6 to OFF.
2. To select Television, slide Switch 2 to ON, and Switch 3-6 to OFF, ignore Switch 1 position.

**Step 3. Learn IR Data**

Each appliance type can learn up to 8 IR signals, selected with Dip Switch Set 2.

<figure><img src=".gitbook/assets/image (218).png" alt=""><figcaption></figcaption></figure>

**Example:**

* To select IR Signal 1, slide Switch 1 to ON, and Switch 2-8 to OFF.
* To select IR Signal 2, slide Switch 2 to ON, and Switch 3-8 to OFF, ignore Switch 1 position.

1. Select the IR Signal desired by adjusting dip switch. We suggest to be begin from IR Signal 1 by sliding Switch 1 to ON position to select IR Signal 1.
2. Point your appliance’s IR remote control at opposite direction of the IR receiver to prevent the IR Receiver from receiving unwanted IR signal.
3. Adjust the IR remote control to the setting you desired, then point the remote control at the IR Receiver, then press remote control button to transmit the IR Signal

**Example:**

* For air conditioner remote control, if you set the remote control to “Cool Mode, 18°C, Fan Speed Auto” and turn off the remote control, then point the remote control at IR Receiver and press “ON.” The IR Receiver will learn in “Cool Mode, 18°C, Fan Speed Auto” signal for the air conditioner
* For television remote control, if you point the remote control at IR receiver and press ON/Off. The IR Receiver will learn in ON/OFF signal for the television.

4. If the signal is received successfully, the IR LED will flash quickly, then turn off to indicating that IR Remote Control is storing IR Signal data, then flash slowly again. If you accidently sent the wrong IR signal, point the remote control away to adjust setting, the point it at the IR Receiver to retransmit signal again. The new IR signal will overwrite the old one.
5. After finish learning, change dip switch setting to learn another IR Signal, the repeat procedure from 2 to 4. We suggest to proceed from IR Signal 1 to 8 by sliding dip switch 1 to 8 to ON position one by one.
6. Repeat the process to learn in maximum of 8 signals for each appliance type.
7. You can adjust your Dip Switch set 2 setting to select another appliance type.

**Step 4. Exit IR Learn Mode**

1. After finish learning all IR signals, press IR button once to exit learning mode, then slide all switches to OFF position.

### _**Testing**_

After complete learning the IR signals, follow instruction below to test transmitting IR signals.

1. Do not enter IR Learn mode, adjust the Dip Switch setting accordingly to select the Appliance type and IR signal number as previously learnt it.
2. Press the IR button once, the IR LED will flash quickly to indicate it is transmitting signal. If no signal is learnt in, the IR Remote Control will not send any signal and IR LED will stay turned off.
3. Repeat procedure from 1 to 2 to test all learnt in IR signals.
4. After finish all settings, slide all switch to OFF position.

### _**Clearing IR Data**_

To remove all IR signal learnt in for an appliance type, follow instruction below:

1. Remove batteries to power down IR Remote Control.
2. Select the appliance type you want to remove using Dip Switch set 1 according to following table

<figure><img src=".gitbook/assets/image (219).png" alt=""><figcaption></figcaption></figure>

Slide more than one switch to ON will select multiple appliance type,

**Example:**

* Slide Switch 1,2,3,4,5 to ON will select all 5 appliance types.
* Slide Switch 1 and 3 to ON to select Air Conditioner and Home Audio.

3. Press and hold both IR and ZigBee buttons and insert batteries to power up IR transmitter, do not release the buttons yet.
4. Keep holding both IR and ZigBee buttons until IR LED turns on, then release the buttons
5. The IR transmitter will clear stored IR signal for selected appliance types, the IR LED will flash continuously.
6. Slide all switches to OFF position to return to normal operation. The IR LED will turn off.

## **Installation**

The IR Remote Control is designed to be mounted on wall. It can be mounted by either directly screwing the back cover onto the wall, or by installing the rotational bracket first, then install the main body on the bracket. Please refer to the **IR Signal Coverage & IR LED Selection** section below for information on IR signal transmission before selecting the IR Remote Control’s mounting location.

### _**Mounting the IR Remote Control**_

![](<.gitbook/assets/7 (49).jpeg>)

The IR Remote Control is designed to be mounted on wall. It can be mounted by either directly screwing the back cover onto the wall, or by installing the rotational bracket first, then install the main body on the bracket. The IR Eye should be pointed to the home appliance you want to control when the IR Remote Control is installed.

{% hint style="info" %}
**The Rotational Bracket is not included in standard shipping and is available upon request.**
{% endhint %}

#### Direct Wall Mounting:

1. Open the cover and break through the 4 knockouts on the back cover.
2. Use the holes as template to drill holes in the wall, insert wall plugs if required.
3. Screw the back cover onto the wall.
4. Replace the front cover on the back cover.

#### Rotational Bracket mounting.

The Rotational Bracket has an adjustable head which can be attached to the IR Remote Control. After installing the bracket on the wall, the user can adjust the angle of the head to change the direction IR Remote Controlis facing.

1. The Rotational Bracket base has 2 mounting holes, Use the holes as template to drill holes in the wall, insert wall plugs if required.
2. Screw the bracket onto the wall.
3. Hook the IR Remote Control onto the brackets using the holes on the back.
4. After completing installation, you can use a Philip screw driver to loosen the screw on top of the bracket, then adjust the IR transmitter angle and tighten the screw to lock the bracket angle.



![](<.gitbook/assets/8 (42).jpeg>)

## **Operation**

### _**Control via ZigBee Control Panel**_

The IR Remote Control can be controlled via Climax ZigBee Control Panels remotely to transmit IR signal. Selecting the appliance type and IR signal number from the Control Panel will control the IR Remote Control to send IR signal accordingly.

**Example:**

Select “Air Conditioner Function 1” will control the IR Remote Control to send IR signal 1 learnt in Air Conditioner appliance type.

### _**IR Signal Coverage & IR LED Selection**_

![](<.gitbook/assets/9 (30).jpeg>)

The IR Eye of the IR Remote Control includes 6 LEDs which are used to transmit IR signals, with 1 central LED and 5 surrounding LEDs. The 5 surrounding LEDs are positioned at 45° angle to the PCB board. **LED Signal Coverage:**

Each LED transmits IR signal in cone coverage in front of the LED. The LEDs can be selected to transmit signal for each appliance type by using your Gateway.

**Example:**

* If you select LED 1 for Air Conditioner, the IR Remote Control will transmit signal with LED 1 when it transmits an Air Conditioner appliance type IR Signal.
* If you select LED 2 and LED 3 for Home Audio, the IR Remote Control will transmit signal with both LED 2 and LED 3 when it transmits a Home Audio appliance type IR Signal.

When installing the IR Remote Control, select the IR LED used via your Control Panel according to the IR Remote Control mounting location to allow IR transmitter to send signal to all appliance in your home. Please refer to your Climax Control Panel manual for more information on IR Remote Control setting and control.

Please refer to diagram below for IR signal coverage:

![](<.gitbook/assets/10 (22).jpeg>)

### _**IR Transmission Power**_

Use the jumper switches (JP2 and JP3) to adjust the IR signal transmission power. Factory default is set to Low transmission power(JP1 ON).&#x20;

Setting the jumper to JP2 will increase the IR signal transmission range.



## **Appendix(For developers only)**

### _**UPIC Cluster ID**_

<figure><img src=".gitbook/assets/image (220).png" alt=""><figcaption></figcaption></figure>

### Attribute of Basic Cluster Information

<figure><img src=".gitbook/assets/image (222).png" alt=""><figcaption></figcaption></figure>

### _**Attribute of Power CFG Cluster Information**_

<figure><img src=".gitbook/assets/image (223).png" alt=""><figcaption></figcaption></figure>

### _**Attribute of Identify Cluster Information**_

<figure><img src=".gitbook/assets/image (224).png" alt=""><figcaption></figcaption></figure>

### _**Attribute of Thermostat Cluster Information**_

<figure><img src=".gitbook/assets/image (225).png" alt=""><figcaption></figcaption></figure>

**System Mode (0x001C):**

This attribute determines which IR signal to transmit when UPIC receives command from panel, according to the learnt in IR signal Type and Function.

UPIC can learn in up to 5 sets of IR Type, 8 signals for each type. When transmitting signal, the IR signal must be

specified with this attribute.

The format is 0&#x78;_**XY**_



X = Appliance Type (1\~5)

Y = IR signal Number (1\~8)

For example, if the UPIC has learnt in an IR signal at Appliance Type 1, IR signal 8, the panel should send command with attribute setting 0&#x78;_**18**_ for UPIC to transmit this signal.

**Select Send IR LED (0x1011):**

UPIC can control up to 5 types of appliances (Type 1 \~ 5) with its 6 IR LEDs. It can be configured to send IR signal with different LEDs using this attribute.

The Format should be read as following, using default value 0x2020202020 as example

<figure><img src=".gitbook/assets/image (226).png" alt=""><figcaption></figcaption></figure>

For each appliance type value , the value should be read in Bit0\~5, in following format:

<figure><img src=".gitbook/assets/image (227).png" alt=""><figcaption></figcaption></figure>

For example: 0x20 = 0010 0000 in Bit number, meaning that only LED 6 (The central LED) will be activated when UPIC transmit IR signal in this appliance type.

If you want to set the IR signal to be transmitted with both LED 2 and LED 6, the value in bit number will be 0010 0010 = 0x22

<figure><img src=".gitbook/assets/image (228).png" alt=""><figcaption></figcaption></figure>

0010 0010 in Bit number = 0x22 in Hexadecimal number, if you wish to apply this setting to Appliance Type 1 only and leave the other appliance type unchanged, the final attribute setting will be: 0x**22**20202020

<figure><img src=".gitbook/assets/image (229).png" alt=""><figcaption></figcaption></figure>

You can use this attribute to program which LEDs should be activated for different IR Appliance Type&#x20;

_**IMPORTANT NOTE:**_

{% hint style="info" %}
Although it is possible to set multiple LED transmission when sending IR Signal, please set **NO MORE THAN 2** LEDs to be activated. The reason for such limitation is that for each extra LED activated, the power consumption will increase dramatically. If you activate more than 2 LEDs, the battery will be depleted in a much shorter time than is ideal.
{% endhint %}



