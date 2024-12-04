# VESTA 140

## **Z-Wave Relay Controller PRL-8-ZW-AC**

**Introduction**

PRL-8-ZW-AC is a Z-Wave Relay Controller that can be connected to wired devices and set to either Normal Open (N.O.) or Normal Close (N.C.) status. After joining Z-Wave network, the Relay Controller can be controlled via Z-Wave network to activate connected devices. Z-Wave is a wireless communication protocol that uses a low-power RF radio. The Z-Wave Relay Controller allows access to the “S2 Unauthenticated” class.

**Parts Identification**

<div align="center" data-full-width="false"><img src=".gitbook/assets/0 (62).jpeg" alt=""></div>

1. **Function Button**

Press the button 3 times within 1.5 seconds to send a learn code.

Press and hold the button for 10 seconds to factory reset.

Press the button to switch ON/OFF the Relay.

2. **LED indicator (Red)**

The LED indicator is used to indicate Relay status:

* LED On: Relay On
* LED Off: Relay Off

{% hint style="info" %}
[**Connection Terminals**](#user-content-fn-1)[^1]

Connect the wire into the terminal, tighten the screw to close the clipper and hold wire in place. Unscrew to open the clipper to remove the wire connected to the terminal.
{% endhint %}



3. **Line (AC input)**
4. **Neutral**
5. **NO**                                                                                                                                                                                     For Normal Open connection with the device.
6. **Common**
7. **NC**                                                                                                                                                                                               For Normal Close connection with the device&#x20;
8. **Strain Relief Clamp**                                                                                                                                                         The clamp is used for securing the wires, and providing strain relief to protect the wires from the        metal cut out.
9. &#x20;**Wiring Buckle**                                                                                                                                                               The Wiring Buckle is used for managing wires.

## **Specification**

* Power Source (External Power): 100-240VAC
* Relay Output: Potential-free SPDT relay, Maximum Operation Load: 10A (Resistive) at 24VDC or 240VAC
* Stranded Wire: 14 \~ 22 AWG
* Operating Temperature: -10°C to 45°C (14°F to 113°F)
* Humidity: Up to 85% non-condensing
* Dimension: 86mm x 72mm x 29mm

<div align="left" data-full-width="false"><figure><img src=".gitbook/assets/1 (56).jpeg" alt="dsfsfs" width="52"><figcaption><p><strong>INSTALLATION ENVIROMENT</strong></p></figcaption></figure></div>

* The Relay Controller should be installed indoors in a dry location.
* It is recommended to install the device in a fire resistant plastic gangbox.
* Do not install the device in a metal gangbox for optimization of Z-Wave range.

<div align="left"><figure><img src=".gitbook/assets/2 (46).jpeg" alt="CAUTION" width="52"><figcaption><p><strong>CAUT</strong><del><strong>I</strong></del><strong>ON</strong></p></figcaption></figure></div>

* All works on the device, including installation and maintenance, must be performed by a qualified and licensed electrician.
* To prevent electrical shock and/or equipment damage, disconnect electrical power at the main fuse or circuit breaker before installation and maintenance.
* Do not connect the device to loads exceeding supported load current.

## **Installation**

<div data-full-width="true"><img src=".gitbook/assets/3 (45).jpeg" alt="" width="256"></div>

Wiring of the PRL should only be performed by certified technician with proper knowledge and training in electric equipment. Wire the Relay according to the instructions below:

1. Turn off the power supply before connection.
2. Remove the top cover and remove the strain relief clamp.
3. Connect the L and N terminals of the power supply to the Line and Neutral terminals of PRL respectively through the wiring hole.
4. Depending on the device you wish to control via the Relay, select NO or NC terminal and wire the Relay with the device to establish Normal Open or Normal Close connection with device.
5. After completing device wiring, replace the strain relief clamp, use the wiring buckle to manage the wires, and place the wiring buckle on the base with its gap (opening) positioned on the left (as in the diagram below).

![](<.gitbook/assets/4 (41).jpeg>)

6. Replace the top cover. Turn on the power supply to power on the Relay Controller.

## **Z-Wave Network**

#### _**Adding Device (Inclusion)**_

* Connect the power supply to the Relay Controller according to the installation instruction in previous section and power up the Relay Controller.
* Put the Z-Wave gateway or control panel into **Inclusion mode** (please refer to the Z-Wave gateway or control panel manual).
* Within 1.5 seconds, press the Function Button 3 times.
* Refer to the operation manual of the Z-Wave gateway or control panel to complete the adding process.
* If the device has already been added (included) into another Z-Wave Gateway/Control Panel, or if the device is unable to be added into the current Z-Wave Gateway/Control Panel, try removing it first (see _**Removing Device**_).

#### _**Removing Device (Exclusion)**_

The device must be removed from existing Z-Wave network before being added into another.&#x20;

* **Exclusion Mode**
  * Put the Z-Wave gateway or control panel into **Exclusion mode** (please refer to the Z-Wave gateway or control panel manual).
  * Within 1.5 seconds, press the Function Button 3 times and the device will be removed from the Z-Wave network.
*   **Factory Reset**

    Factory resetting the device will restore it to factory default settings (i.e. not included into any Z-Wave network). Please only use this procedure if the Z-Wave gateway or control panel is lost or otherwise inoperable.

&#x20;      Press and hold the Function Button of the device for 10 seconds to factory reset.

#### _**Range Test**_

To test whether the device is able to communicate with the Z-Wave gateway or control panel:

* Put the gateway / panel into range test mode (Walk Test).
* Press the Function Button on the device.
* The gateway / panel should display if the device is within the operation range (please refer to the operation manual of the gateway / panel).

## **Operation**

#### _**Relay Control**_

* When the Relay Controller has successfully joined a Z-Wave network, the gateway/control panel will be able to remotely control the Relay to turn On, Off or toggle between On and Off condition. Please refer to your Z-Wave gateway/control panel for details.

## **Z-Wave Information**

* [ ] **Device Type:** On/Off Power Switch
* [ ] **Role Type:** Always On Slave (AOS)
* [ ] **Command Class Support/Control**
* [ ] **Mandatory CC Support:**
  * [ ] &#x20;Z-Wave Plus Info CC&#x20;
  * [ ] Association CC, (S2)
  * [ ] Multi Channel Association CC, (S2)
  * [ ] Association Group Information CC, (S2)
  * [ ] Transport Service CC
  * [ ] Version CC, (S2)
  * [ ] Manufacturer Specific CC, (S2)
  * [ ] Device Reset Locally CC, (S2)
  * [ ] Powerlevel CC, (S2)
  * [ ] Switch Binary CC
  * [ ] Supervision CC, (S2)
  * [ ] Firmware Update Md CC, (S2)

- _**Z-Wave’s Groups (Association Command Class Version 2)**_

The Switch can be set to send reports to associated Z-Wave devices. It supports one association group with five node support for Grouping 1. For grouping 1, the Switch will report its latest status to Z-Wave Gateway/Panel.

Grouping 1 for “LifeLine”: (max node: 5)

Switch Binary CC (COMMAND\_CLASS\_SWITCH\_BINARY)

Device Reset Locally CC (COMMAND\_CLASS\_DEVICE\_RESET\_LOCALLY)

When toggling between On/Off, it will send Binary Switch Report to the nodes of Grouping 1.



[^1]: 
