# VESTA-294

**SCM-6-AS-ZW**

## **Shutter Control**

## **Introduction**

SCM-6-AS-ZW is a Z-Wave™ Shutter Control. The user can control the SCM via Z-Wave network at a remote distance or manually by linking a switch to the SCM.

Automatically or remotely roll up, down or stop mid-way, the SCM-6-AS-ZW is directly connected to and controls motorized window treatments, interior and exterior shades and blinds, projection screen, and garage door or driveway gate of your home.

The Shutter Control is compatible only with Z-Wave Gateway/Control Panel. Z-Wave is a wireless communication protocol that uses a low-power RF radio. By taking advantage of the Z-Wave mesh network, commands can be routed to their destination via intermediary “listening” Z-Wave products.

The Z-Wave Shutter Control allows access to the “S2 Unauthenticated” class and support Z-Wave SmartStart inclusion as well as classic inclusion.

## **Parts Identification**

![](<.gitbook/assets/0 (110).jpeg>)

1. **LED indicator**
   * Power ON: LED flashes twice.
   * In auto calibration mode: LED flashes once every second.
   * Factory Reset: LED flashes twice.
   * When pressing Local Switch S1/S2: LED ON.
2. **Function Button**
   * Press the function button and the Shutter Control will send a multilevel report.
   * Press the function button 3 times within 1 second to include or exclude the Shutter Control in/from Z-Wave network.
   * Press and Hold Function button for 10 seconds to reset.
   * Press and hold the Function button for 3 seconds, and then release it to enter Auto Calibration mode.
3. **Power input N (Neutral Lead) connection cable (Blue)**
4. **Power Input L (Live Lead) connection cable (Brown)**
5. **Local Switch S2 (Down Direction) connection cable (Orange)**

If SCM is connected according to _**Installation**_ below, the shutter will roll down for 4 minutes after the switch is activated.

Activating this switch when the shutter is rolling up will stop the shutter.

**6. Local Switch S1 (Up Direction) connection cable (Red)**

If SCM is connected according to _**Installation**_ below, the shutter will roll up for 4 minutes after the switch is activated.

Activating this switch when the shutter is rolling down will stop the shutter.

**7. Motor Output O1 (Up Direction) connection cable (Yellow)**

Connect to the Up terminal of the Shutter Motor.

**8. Motor Output O2 (Down Direction) connection cable (Green)**

Connect to the Down terminal of the Shutter Motor.

## **Specification**

* Power Supply: 110 - 230VAC, 50/60Hz
* Supported Load Current: 3Amps for motors with compensated power factor (inductive loads)
* Communication Protocol: Z-Wave Plus 700 series module

## **Caution**

* All works on the device, including installation and maintenance, must be performed by a qualified and licensed electrician.
* Before installation or any maintenance work, make sure the power supply has been disconnected.
* Do not connect the device to loads exceeding supported load current.
* Please connect the device to AC powered motor only.

## **Features**

### _**Adding Device (Inclusion)**_

This product can be included and operated in any Z-Wave network with other Z-Wave certified devices from other manufactures and/or other applications. All non-battery operated nodes within the network will act as repeaters regardless of vendor to increase reliability of the network. The device supports both classic inclusion process and SmartStart inclusion process.

#### **Classic Inclusion**

* Connect power to the Shutter Control (see manual’s **Installation**).
* Put the Z-wave gateway or control panel into **Inclusion mode** (please refer to the Z-wave gateway or control panel manual).
* Within 1 second, press the Function Button 3 times.
* Refer to the operation manual of the Z-wave gateway or control panel to complete the adding process.
* If the device has already been added (included) into another Z-wave Gateway/Control Panel, or if the device is unable to be added into the current Z-wave Gateway/Control Panel, try removing it first (see _**Removing Device**_).

#### **SmartStart Inclusion**

![](<.gitbook/assets/2 (77).jpeg>)

Z-Wave SmartStart utilizes the DSK of the device to enhance and simplify the inclusion process. DSK is Device Specific Key used for authentication. The DSK information is stored in the QR code format that is printed on a sticker and attached to the device.

* Scan the QR Code sticker on the right hand side of the Shutter Control to obtain DSK and transfer to the Z-Wave gateway.
* Connect power to the Shutter Control, a SmartStart inclusion request will be automatically sent to the gateway.
* The gateway will automatically include the device upon recognition of the device by matching the inclusion request with the DSK obtained.

{% hint style="warning" %}
Note:

* The DSK of the device is used only during inclusion.
* The DSK can be read without the Shutter Control powered ON, so it is possible to prepare the gateway to include the device prior to powering up the Shutter Control.
* Before you remove or factory reset the Shutter Control, please ensure that the device DSK information has been removed or does not exist in the gateway. If you remove or factory reset the device, but its DSK still exists in the gateway, the gateway will automatically include the device again.
{% endhint %}

## _**Removing Device (Exclusion)**_

The device must be removed from existing Z-wave network before being added into another.

### **Exclusion Mode**

* Put the Z-wave gateway or control panel into **Exclusion mode** (please refer to the Z-wave gateway or control panel manual).
* Within 1 second, press the Function Button 3 times and the device will be removed from the Z-wave network.

### **Factory Reset**

_(Only use factory reset when network Control Panel/Gateway is missing or inoperable)._

Factory resetting the device will restore it to factory default settings (i.e. not included into any Z-wave network).

* Press and hold the Function Button of the device for 10 seconds to factory reset.

## _**Range Test**_

To test whether the device is able to communicate with the Z-wave gateway or control panel:

* Put the gateway/panel into range test mode (Walk Test).
* Press the Function Button on the device.
* The gateway/panel should display if the device is within the operation range (please refer to the operation manual of the gateway / panel).

## **Installation**

### _**Wiring with Splicing Connector**_

* SCM-6 comes with embedded terminal wires and clamps (Wago 221 Splicing Connectors).
* The 2-wire connectors accommodate solid and stranded wires from 0.2 to 4 mm² (24–12 AWG).
* Please connect SCM-6 to AC power, local switches, and shutter motor with the connectors.
* Before wiring, please make sure the power is off. To connect the wires:

1. Lift the lever and insert the wire. **(Picture 1, 2)**

![Picture 1                                                                                                                                      Picture 2](<.gitbook/assets/3 (86).png>)

2. Push the lever back down. The transparent housing allows you to check if the wire is connected properly. Make sure the wire is held in place tightly and won't come off. **(Picture 3, 4)**



![Picture 3                                                                                                                   Picture 4](<.gitbook/assets/4 (92).png>)

3. In the same way as step 1 & 2, connect the other wires with connectors.

* SCM-6 should be connected according to the diagram below:

![](<.gitbook/assets/5 (48).jpeg>)

* Connect N terminal of SCM to the N terminal of Power Supply.
* Connect L terminal of SCM to the L terminal of Power Supply.
* Connect O1 terminal of SCM to the Open terminal of the Shutter Motor.
* Connect O2 terminal of SCM to the Close terminal of the Shutter Motor.
* **(Optional local switch)** Connect S2 and S1 terminals of SCM to the L terminal of Power Supply.

## **Operation**

### _**Shutter Control**_

#### **Manual Control**

If an optional Local Switch is connected, the user can press and hold the button on the up/down Local Switch (S1 up; S2 down) for 1 second to control the shutter. When activated, the shutter will roll up/down. When the shutter is rolling, the user can stop the shutter by pressing the opposite direction button.

* **Z-Wave Network**

After the Shutter Control has been successfully included in a Z-Wave network, the Z-Wave controller can control the shutter with Z-wave command Switch Binary Set or Switch Multilevel Set, using parameters below:

* Value: 0x00\~0x63 (0%\~99%, 0% = Full Close, 99% = Full Open)
* Dimming Duration : 0x00

## _**Calibration**_

* The Shutter Control default activation time is **4** minutes.

When the Up/Down button is pressed, it will activate the shutter motor for 4 minutes.

When a Z-Wave command is received from Z-Wave controller, it will determine the shutter travel percentage using 4 minutes as basis for calculation.

*   For the Shutter Control to work properly, its activation time must be calibrated according to actual shutter travel distance. There are two ways to adjust the activation time:

    * **Auto Calibration:** Calibrate the activation according to procedure below:
      1. Press and hold the Function Button for 3 seconds and then release it to enter Auto Calibration mode. The LED will start to flash once every second; the Shutter Motor will roll up to the top.
      2. When the Shutter Motor rolls up to the top and stops, it will then automatically roll down and record the time it takes to roll from open (top) to closed (bottom) position as the new “**close time**”.
      3. When the Shutter Motor rolls down to the bottom, it will roll up and record the time it takes to roll from closed (bottom) to open (top) position as the new “**open time**”.
      4. When all actions are completed, the Shutter Control will send a MULTILEVEL\_REPORT: 0x63 to the controller indicating that the current position is at the top. The LED will turn off as the Shutter Motor exits auto calibration mode.
      5. After calibration, the Shutter Motor will operate according to newly recorded rolling up and down times.
    * For Example, if it takes the shutter 30 seconds to move from “Up” to “Down” position, its new close time will be 30 seconds. After calibration, whenever the “Down” button is pressed, the shutter will roll down for 30 seconds.
    * If it takes the shutter 40 seconds to move from “Down” to “Up” position, its new open time will be 40 seconds. After calibration, whenever the “Up” button is pressed, the shutter will roll up for 40 seconds.
    * **Z-Wave Command:** Besides auto calibration, users can also adjust the activation time by sending command from the Z-Wave Controller with Configuration CC command, using parameters below:



<figure><img src=".gitbook/assets/10 (13).png" alt=""><figcaption></figcaption></figure>

*   Parameter Number : 0x01\~0x04

    * For parameter 1, users can set the open time (from down to up) to a value that ranges from 0 to 240 seconds.
    * For parameter 2, users can set the close time (from up to down) to a value that ranges from 0 to 240 seconds.
    * For parameter 3, users can set the current position to a value that ranges from %0 to %99.
    * For parameter 4, users can set value to force the device to execute calibration or check the calibration status by value. Set value to 2 to make device execute calibration. If value is 0, it represents the device is not calibrated. If value is 1, it represents the device is calibrated.
    * Size: 0x02. This is used to specify the size of the actual value.
    * Configuration Value : 0x0000\~0x0960 (0.1 second)

    The shutter control will start movement upon receiving Z-wave command Switch Binary Set or Switch Multilevel Set, and the movement will be executed based on current position setting. Example for Configuration Setting:

<figure><img src=".gitbook/assets/11 (7).png" alt=""><figcaption></figcaption></figure>

SWITCH\_MULTILEVEL\_SET: 0x00 (0%)\
SCM will roll down (from up to down) for 50 seconds: (1000/1000)\*(100-50)

* The activation time will be reset to 4 minutes whenever the Shutter Control is included in Z-Wave  \
  network, or when it is factory reset.

{% hint style="warning" %}
Note:

The Shutter Control’s default Current Position is set to 99% (Full Open). It is recommended to fully open the shutter before calibrating with Z-Wave command, otherwise please also re-adjust the Current Position setting with command.
{% endhint %}

## _**Z-Wave Information**_

**Device Type :** GENERIC\_TYPE\_SWITCH\_MULTILEVEL

**Specific Type :** SPECIFIC\_TYPE\_CLASS\_C\_MOTOR\_CONTROL

**Role Type :** Always On Slave (AOS)

**Manufacturer ID :** 0x018E

**Product Type ID :** 0x0004

**Product ID:** 0x0105

**Supported Command Class**&#x20;

<figure><img src=".gitbook/assets/10 (1) (1) (1).png" alt=""><figcaption></figcaption></figure>
