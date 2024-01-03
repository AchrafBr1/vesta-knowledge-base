# VESTA 206

**Z-Wave Relay Toggle Switch PRL-3ZW-AC**

**Introduction**

PRL-3ZW-AC is a Z-Wave Relay Toggle Switch. The Relay Toggle Switch can be connected to wired device and set to Normal Open (N.O.) status. After joining Z-Wave network, the Relay Toggle Switch can be controlled via Z-Wave network to activate connected devices.

Z-Wave is a wireless communication protocol that uses a low-power RF radio. By taking advantage of the Z-Wave mesh network, commands can be routed to their destination via intermediary “listening” Z-Wave products.

The Relay can control Z-Wave nodes by simply pressing the function button and can also alert you to signal communication problems.

The Z-Wave Relay Toggle Switch series includes the following models:

PRL-3ZW-AC

PRL-3ZW-AC-OTA

**Parts Identification**

![](<.gitbook/assets/0 (84).jpeg>)

**1. LED indicator**

The LED indicator is used to indicate Relay status:

*
  * LED On: Relay On
  * LED Off: Relay Off

1. **Function Button**

Press the button 3 times within 1.5 seconds to send a learn code.

Press and hold the button for 10 seconds to factory reset.

Press the button to switch ON/OFF the Relay.

**Connection Terminals**

Connect the wire into the terminal, tighten the screw to close the clipper and hold wire in place. Unscrew to open the clipper to remove the wire connected to the terminal.

1. **Neutral**
2. **Line (AC input)**

To power up the PRL-3ZW, connect L& N terminals of the Power Supply to L & N terminals.

**5. NO**

For Normal Open connection with the device

**6. Common**

Connect NO & COM terminals of the wired device to NO & COM terminals of the PRL-3ZW.

**Specification**

* Power Source (External Power): 100-240VAC
* Relay Output: Potential-free SPDT relay, Maximum Operation Load: 5A (Resistive) at 24VDC or 240VAC.
* Stranded Wire: 14 \~ 22 AWG
* Operating Temperature: -10°C to 45°C (14°F to 113°F)
* Humidity: Up to 85% non-condensing
* Dimension: 71mm x 49mm x 26mm

![](<.gitbook/assets/1 (73).jpeg>)

**Installation Environment**

* The Relay Toggle Switch should be installed indoors in a dry location.
* It is recommended to install the device in a fire resistant plastic gangbox.
* Do not install the device in a metal gangbox for optimization of Z-Wave range.

1

![](<.gitbook/assets/2 (69).jpeg>)

**Caution**

* All works on the device, including installation and maintenance, must be performed by a qualified and licensed electrician.
* To prevent electrical shock and/or equipment damage, disconnect electrical power at the main fuse or circuit breaker before installation and maintenance.
* Do not connect the device to loads exceeding

![](<.gitbook/assets/3 (62).jpeg>)

supported load current.

**Installation**

Wire the Relay according to the instructions below or refer to the diagram for more information.

1. Please turn off the power supply before connection.
2. Connect the L and N terminals of the power supply to the Line and Neutral terminals of PRL respectively.
3. Depend on the device you wish to control via the Relay, select NO terminal and wire the Relay with the device to establish Normal Open connection with device.
4. After completing the wiring, turn on the power supply to power on the Relay Toggle Switch.

![](<.gitbook/assets/4 (68).png>)

_\<IMPORTANT NOTE>_

* Wiring of the PRL should only be performed by certified technician with proper knowledge and training in electric equipment.

**Features**

![](<.gitbook/assets/5 (70).png>)

* _**Adding Device (Inclusion)**_
  * Connect the power input to the Relay Toggle Switch according to Installation instruction above and power up the Relay Toggle Switch.
  * Put the Z-Wave gateway or control panel into **Inclusion mode** (please refer to the Z-Wave gateway or control panel manual).
  * Within 1.5 seconds, press the Function Button 3 times.
  * Refer to the operation manual of the Z-Wave gateway or control panel to complete the adding process.
  * If the device has already been added (included) into another Z-Wave Gateway/Control Panel, or if the device is unable to be added into the current Z-Wave Gateway/Control Panel, try removing it first (see _**Removing Device**_).
* _**Removing Device (Exclusion)**_

![](<.gitbook/assets/6 (49).png>)

The device must be removed from existing Z-Wave network before being added into another. **Exclusion Mode**

* Put the Z-Wave gateway or control panel into **Exclusion mode** (please refer to the Z-Wave gateway or control panel manual).
* Within 1.5 seconds, press the Function Button 3 times and the device will be removed from the Z-Wave network.

**Factory Reset**

*
  * Factory resetting the device will restore it to factory default settings (i.e. not included into any Z-Wave network). Please only use this procedure if the Z-Wave gateway or control panel is lost or otherwise inoperable.
  * Press and hold the Function Button of the device for 10 seconds to factory reset.
* _**Range Test**_

![](<.gitbook/assets/7 (45).png>)

To test whether the device is able to communicate with the Z-Wave gateway or control panel:

* Put the gateway / panel into range test mode (Walk Test).
* Press the Function Button on the device
* The gateway / panel should display if the device is within the operation range (please refer to the operation manual of the gateway / panel).

2

**Operation**

![](<.gitbook/assets/8 (40).jpeg>)

* _**Relay Control**_
  * After the Relay toggle Switch has successfully added into a Z-Wave network, the gateway/control panel can remotely control the Relay to turn On, Off or toggle between On and Off condition. Please refer to your Z-Wave gateway/control panel for detail.

**Z-Wave Information**

**Device Type:** On/Off Power Switch

**Role Type:** Always On Slave (AOS)

**Command Class Support/Control**

**Mandatory CC Support:** Association CC, v2 or newer

Association Group Information CC

Basic CC

Binary Switch CC

Device Reset Locally CC

Manufacturer Specific CC

Power level CC

Version CC, v2 or newer

Z-Wave Plus Info CC

**Recommended CC Support**: Firmware Update Metadata CC

![](<.gitbook/assets/9 (41).png>)

* _**Z-Wave’s Groups (Association Command Class Version 2)**_

The Switch can be set to send reports to associated Z-Wave devices. It supports one association group with five nodes support for Grouping 1. For grouping 1, the Switch will report its latest status to Z-Wave Gateway/Panel.

Group 1 for “LifeLine”:

Binary Switch CC (SWITCH\_BINARY\_REPORT)

Device Reset Locally CC (COMMAND\_CLASS\_DEVICE\_RESET\_LOCALLY)

* Auto report to Grouping 1 (Maximum Node 5)
* On/Off Event Report

When toggling between On/Off, it will send Binary Switch Report to the nodes of Grouping 1.

3
