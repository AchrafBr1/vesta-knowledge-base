# VESTA-206N

**PRL-3-F1**

## **Relay Controller**

<figure><img src=".gitbook/assets/image (3) (1) (1) (1) (1) (1) (1) (1) (1).png" alt=""><figcaption></figcaption></figure>

## Introduction

PRL-3-AC is a Relay Controller that can be connected to wired device and set to Normal Open (N.O.) status. After learned into the Control Panel, the Relay Controller can be controlled via the Panel webpage to remotely open and close the connected device.

## Parts Identification

### 1. LED indicator

The LED indicator is used to indicate Relay status:

* On: The Relay Controller is turned on.
* Off: The Relay Controller is turned off.
* Flashes twice: When powered on.
* Flashes slowly: Under learning mode.
* Flashes three times: When learning is successful.
* Flashes briefly: RF signal transmitting

### 2. Test Button

* Press and hold the button for 3 seconds to send a learn code.
* Press and hold the button while powering on the Relay Controller, then release the button when the LED lights up to factory reset.
* Press the button to switch ON/OFF the Relay.

<figure><img src=".gitbook/assets/0 (141).jpeg" alt=""><figcaption></figcaption></figure>

### Connection Terminals

Connect the wire into the terminal, tighten the screw to close the clipper and hold wire in place. Unscrew to open the clipper to remove the wire connected to the terminal.

### **3. Neutral**&#x20;

### **4. Line (AC input)**

### &#x20;**5. NO**

&#x20;    For Normal Open connection with the device.

### **6. Common**

## Specification

* Power Source (External Power): 100-240VAC
* Relay Output: Potential-free SPDT relay, Maximum Operation Load: 5A (Resistive) at 24VDC or 240VAC
* Stranded Wire: 14 \~ 22 AWG
* Operating Temperature: -10°C to 45°C (14°F to 113°F)
* Humidity: Up to 85% non-condensing
* Dimension: 71mm x 49mm x 26mm

## Installation Environment&#x20;

* The Relay Controller should be installed indoors in a dry location.
* It is recommended to install the device in a fire resistant plastic gangbox.
* Do not install the device in a metal gangbox for optimization of RF range.

### Caution&#x20;

* All works on the device, including installation and maintenance, must be performed by a qualified and licensed electrician.
* To prevent electrical shock and/or equipment damage, disconnect electrical power at the main fuse or circuit breaker before installation and maintenance.
* Do not connect the device to loads exceeding supported load current.

## Installation

Wire the Relay according to the instructions below or refer to the diagram for more information.

1. Please turn off the power supply before connection.
2. Connect the L and N terminals of the power supply to the Line and Neutral terminals of PRL respectively.
3. Depend on the device you wish to control via the Relay, select NO terminal and wire the Relay with the device to establish Normal Open connection with device.
4. After completing the wiring, turn on the power supply to power on the Relay Toggle Switch.

<figure><img src=".gitbook/assets/3 (98).jpeg" alt=""><figcaption></figcaption></figure>

{% hint style="danger" %}
_IMPORTANT NOTE:_

Wiring of the PRL should only be performed by certified technician with proper knowledge and training in electric equipment.
{% endhint %}

## Getting Started

**Step 1**: Connect power supply to the Relay Controller according to the installation instructions in previous section and power up the Relay Controller.

**Step 2:** Put the Control Panel into learning mode.

**Step 3:** Press and hold the Test button on the Relay Controller for 3 seconds to send a learn code.

**Step 4:** The LED will start to flash slowly, indicating that the Relay Controller is in learning mode.

**Step 5:** If the Control Panel receives the signal from the Relay Controller, it will display the information accordingly. Refer to the Control Panel manual to complete the learn-in process. **Step 6:** When the Relay Controller receives acknowledgement from the Control Panel, the LED of the Relay Controller will flash 3 times and then turn off to indicate that learning process is completed.

{% hint style="warning" %}
Note:

* After entering learning mode, the Relay Controller will not automatically leave learning mode unlesss it receives acknowledgement from the Control Panel, or unless the Test button is pressed.
* If the Relay Controller already exists in a Control Panel system, you will need to first remove the Relay Controller from the Control Panel before you can learn it into a different Control Panel.
{% endhint %}

## Walk Test

To test whether the Relay Controller is able to communicate with the Control Panel:

* Put the Control Panel into Walk Test mode.
* Press the Test Button on the Relay Controller.
* The Control Panel should display if the Relay Controller is within the operation range (please refer to the operation manual of the Control Panel).

## Supervision

* After the Relay Controller is successfully learned in to the Control Panel, the device will automatically transmit supervisory signal along with ON/Off status to the Control Panel at random intervals of 30 to 50 minutes.
* If the Control Panel has not received the signal from the Relay Controller for the preset period of time, the Control Panel will indicate on its display that the particular Relay Controller is experiencing an out-of-signal problem.

## Operation

### _Relay Control_

* After learned into the Control Panel, the Relay Controller can be controlled via the Panel webpage to remotely open and close the connected device or toggle between on and off conditions.
* You can also press the test button on the Relay Controller to switch ON/OFF the Relay.

### Factory Reset

Factory resetting the Relay Controller will clear its memory and restore it to factory default settings.

1. Remove the Relay Controller from the Control Panel. Refer to the operation manual of your Control Panel for details.
2. Remove power supply from the Relay Controller.
3. Press and hold the test button while supplying power to the Relay Controller.
4. Keep holding the button, then release it when LED lights up. Factory reset is complete.
