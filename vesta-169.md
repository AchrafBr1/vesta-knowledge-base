# VESTA-169

**PRL1-ZW-AC**

## **Z-Wave Relay Controller**&#x20;

## **Introduction**

PRL1-ZW-AC is a Z-Wave Relay Controller that can be connected to wired devices and set to either Normal Open (N.O.) or Normal Close (N.C.) status. After joining Z-Wave network, the Relay Controller can be controlled via Z-Wave network to activate connected devices. Z-Wave is a wireless communication protocol that uses a low-power RF radio.

## **Parts Identification**

<div align="left"><img src=".gitbook/assets/0 (71).jpeg" alt="" width="214"></div>

1. **LED indicator**

The LED indicator is used to indicate Relay status:

* LED On: Relay On
* LED Off: Relay Off

2. **Function Button**

Press the button 3 times within 1.5 seconds to send a learn code.

Press and hold the button for 10 seconds to factory reset.

Press the button to switch ON/OFF the Relay.

### **Connection Terminals**

<div align="left"><img src=".gitbook/assets/1 (66).jpeg" alt="" width="218"></div>

To make wire connection, push the wire into the terminal and hold the wire in place. To remove connected wire, press the button above the terminal, and then remove wire.

3. **Reserved**
4. **Line (AC input)**
5. **Neutral**
6. **NO:**  For Normal Open connection with the device.
7. **Common**
8. **NC:**  For Normal Close connection with the device

## **Specification**

* Power Source (External Power): 100-240VAC
* Relay Output: Potential-free SPDT relay, Maximum Operation Load: 5A (Resistive) at 24VDC or 240VAC
* Stranded Wire: 16-26 AWG
* Operating Temperature: -10°C to 45°C (14°F to 113°F)
* Humidity: Up to 85% non-condensing
* Dimension: 71.1mm x 49mm x 26mm

## <img src=".gitbook/assets/image (3) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1).png" alt="" data-size="line">**Installation Environment**&#x20;

* The Relay Controller should be installed indoors in a dry location.
* It is recommended to install the device in a fire resistant plastic gangbox.
* Do not install the device in a metal gangbox for optimization of RF range.

## <img src=".gitbook/assets/image (2) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1).png" alt="" data-size="line">**Caution** <img src=".gitbook/assets/image (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1).png" alt="" data-size="line">

* All works on the device, including installation and maintenance, must be performed by a qualified and licensed electrician.
* To prevent electrical shock and/or equipment damage, disconnect electrical power at the main fuse or circuit breaker before installation and maintenance.
* Do not connect the device to loads exceeding supported load current.

## **Installation**

The insertion holes’ wiring specification is AWG 16-26 or Ø 1.31-0.129 (mm²).

Wire the Relay according to the instructions below:

![](<.gitbook/assets/4 (46).jpeg>)

1. Turn off the power supply before connection.
2. Connect the L and N terminals of the power supply to the Line and Neutral terminals of PRL respectively.
3. Depending on the device you wish to control via the Relay, select NO or NC terminal and wire the Relay with the device to establish Normal Open or Normal Close connection with device.
4. After completing device wiring, turn on the power supply to power on the Relay Controller.

{% hint style="danger" %}
_IMPORTANT NOTE:_

Wiring of the PRL should only be performed by certifiedtechnician with proper knowledge and training in electric equipment.
{% endhint %}

## **Z-Wave Network**

### _**Adding Device (Inclusion)**_

* Connect the power supply to the Relay Controller according to the installation instruction in previous section and power up the Relay Controller.
* Put the Z-Wave gateway or control panel into **Inclusion mode** (please refer to the Z-Wave gateway or control panel manual).
* Within 1.5 seconds, press the Function Button 3 times.
* Refer to the operation manual of the Z-Wave gateway or control panel to complete the adding process.
* If the device has already been added (included) into another Z-Wave Gateway/Control Panel, or if the device is unable to be added into the current Z-Wave Gateway/Control Panel, try removing it first (see _**Removing Device**_).

### _**Removing Device (Exclusion)**_

The device must be removed from existing Z-Wave network before being added into another.

#### &#x20;**Exclusion Mode**

* Put the Z-Wave gateway or control panel into **Exclusion mode** (please refer to the Z-Wave gateway or control panel manual).
* Within 1.5 seconds, press the Function Button 3 times and the device will be removed from the Z-Wave network.

#### **Factory Reset**

* Factory resetting the device will restore it to factory default settings (i.e. not included into any Z-Wave network). Please only use this procedure if the Z-Wave gateway or control panel is lost or otherwise inoperable.
* Press and hold the Function Button of the device for 10 seconds to factory reset.

### _**Range Test**_

To test whether the device is able to communicate with the Z-Wave gateway or control panel:

* Put the gateway / panel into range test mode (Walk Test).
* Press the Function Button on the device.
* The gateway / panel should display if the device is within the operation range (please refer to the operation manual of the gateway / panel).

## **Operation**

### _**Relay Control**_

When the Relay Controller has successfully joined a Z-Wave network, the gateway/control panel will be able to remotely control the Relay to turn On, Off or toggle between On and Off condition. Please refer to your Z-Wave gateway/control panel for details.

### **Z-Wave Information**

**Device Type:** On/Off Power Switch

**Role Type:** Always On Slave (AOS)

**Command Class Support/Control**

**Mandatory CC Support:**&#x20;

* Association CC, v2 or newer
* Association Group Information CC
* Basic CC
* Binary Switch CC
* Device Reset Locally CC
* Manufacturer Specific CC
* Power level CC
* Version CC, v2 or newer
* Z-Wave Plus Info CC

**Recommended CC Support**: Firmware Update Metadata CC

#### _**Z-Wave’s Groups (Association Command Class Version 2)**_

The Switch can be set to send reports to associated Z-Wave devices. It supports one association group with five nodes support for Grouping 1. For grouping 1, the Switch will report its latest status to Z-Wave Gateway/Panel.

Group 1 for “LifeLine”:

* Binary Switch CC (SWITCH\_BINARY\_REPORT)
* Device Reset Locally CC (COMMAND\_CLASS\_DEVICE\_RESET\_LOCALLY)
  * Auto report to Grouping 1 (Maximum Node 5)
  * On/Off Event Report

When toggling between On/Off, it will send Binary Switch Report to the nodes of Grouping 1.

