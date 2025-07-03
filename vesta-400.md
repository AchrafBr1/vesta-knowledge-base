# VESTA-400

**OPT-BXS-BUS**

## Bus Transmitter for OPTEX sensors

The transmitter is installed in motion detectors, allowing them to send wired signals through the BUS Terminal to the Control Panel. The transmitter can be mounted in the following 4 motion detector models: QXI-RDT-X5, BXS-RAM, VXS-RDAM, and WXI-RAM.

## _**Identifying the Parts**_

<figure><img src=".gitbook/assets/image (337).png" alt=""><figcaption></figcaption></figure>

1. **LED indicator (Red)**
2. **Test Button**
3. **BUS Terminal**&#x20;
4. **Terminal Resistor Jumper Switch**

On each BUS network, enable the terminal resistor jumpers at both endpoints (the two farthest nodes) to prevent signal reflection and ensure stable communication. If the transmitter is one of the endpoints, set this jumper switch to ON.

**Jumper On** enables the terminal resistor.![](<.gitbook/assets/11 (75).png>)

**Jumper Off d**isables the terminal resistor

\- If the Jumper is OFF, the communication ability is in a normal level.&#x20;

\- If the Jumper is ON, the communication ability is enhanced.

**5. PIR Connector**

### LED Indicator

In Normal operation mode, the LED Indicator remains off except for the following situations:

* When the motion detector is powered on, the Red LED will flash about 12 seconds. When the transmitter is well connected, the Red LED turns off.
* When the Tamper Switch is triggered, the LED will flash to indicate it is transmitting “**Tamper**” signal.
* When the Tamper condition persists, each time it transmits a detected movement, the LED will flash.

### Power Supply

When the transmitter is connected to the PIR detector and hardwired to a Hybrid Panel, 13.5V power supply can be provided by the Hybrid Panel.

### Caution

* Wiring of the transmitter should only be performed by certified technicians with proper knowledge and training in electric equipment.
* Before installation or any maintenance work, make sure the power supply has been disconnected.

### Wiring of Transmitter

* Before connecting the transmitter to the system bus, please switch the power off.
* To assist with cable connections, the terminal blocks on each BUS system module are color-coded.

<figure><img src=".gitbook/assets/image (338).png" alt=""><figcaption></figcaption></figure>

* For optimal communication on the BUS network, enable the Terminal Resistor Jumpers only at both endpoints (the two farthest nodes) to prevent signal reflection and improve communication stability. Do NOT enable jumpers on any intermediate BUS devices – only the two endpoints should have them enabled.

{% hint style="warning" %}
Note:

* The pluggable design of BUS terminal blocks improves upon installation efficiency. Before wiring, you can remove the terminal blocks from the PCB board for ease of use, and plug in again after wiring.
* After unplugging the terminal, when re-installing the terminal back to the board, make sure to install the terminal in the same direction to avoid potential hazards.
{% endhint %}

* The PIR detector should be connected to the transmitter prior to connecting the transmitter to the system bus on the Panel.
* Incorrect connections will result in failure or improper operation. Inspect wiring and ensure proper connections before applying power.

## _**Installation of the Transmitter**_

Apply the double-sided foam tape to the marked rectangle at the back of the transmitter.

Locate a suitable position on the motion detector and install the transmitter at the position.

### _**Learning**_

Please follow the steps below to learn the detector into the Hybrid Panel.

<table data-header-hidden><thead><tr><th width="186"></th><th></th></tr></thead><tbody><tr><td>Step 1</td><td>After installing the transmitter on the motion detector and connecting the detector to the Panel, power the Panel on. The detector will be powered on as well.</td></tr><tr><td>Step 2</td><td>On the Panel’s local webpage, click “<strong>Learning</strong>” to enter learn page.</td></tr><tr><td>Step 3</td><td>Click “<strong>Start</strong>” to enter learning mode. <em>If the transmitter is mounted in BXS-RAM or WXI-RAM, the detector will be recognized as 2 separate devices and occupy 2 zones in the Panel when being learnt in.</em></td></tr><tr><td>Step 4 </td><td>Click “<strong>Add</strong>” to include the detector into the Panel.</td></tr><tr><td>Step 5</td><td> If the detector is successfully learnt into the Panel, it will be displayed in the “Learned Device” section.</td></tr></tbody></table>

### Identification

The “**Identify**” function is used to localize a specific BUS device in the BUS wired system. This function is helpful in distinguishing which device is which especially in a large installation where numerous BUS devices are included.

To locate the detector in the BUS system:

**Step 1** On the Hybrid Panel’s webpage, click “Identify” under the device list after the device column entry.

**Step 2** If the detector receives the signal from the Hybrid Panel, the webpage will display a success message and the detector’s LED indicator will flash 10 times to indicate where it is to the user.

{% hint style="warning" %}
Note:

If a timeout message is displayed on the webpage, it means the detector did not receive the signal from the Panel.

Please check whether the detector is connected properly to the Panel within appropriate wiring distance.
{% endhint %}

### Walk Test

* To make sure the detector is able to communicate with the Panel after it is learned-in, place the Control Panel in Walk Test mode and press the Test button on the detector to transmit a test signal to the Control Panel.
* When the Panel receives the test signal, it will beep once and display the PIR’s information accordingly on the top of the device list.

{% hint style="warning" %}
Note:

If there is no response from the Panel after the press of test button, it means the Panel did not receive the test signal from the device.

Please check whether OPT-BXS-BUS is connected properly to the Panel within appropriate wiring distance.
{% endhint %}

### Supervision

* The detector will conduct a self-test periodically by transmitting a supervisory signal every 75 seconds.
* If the Control Panel has not received the signal from the detector for a preset period time, the Control Panel will indicate that the particular detector is experiencing an out-of-order problem.

### Remote Setting

* After the detector is learnt into the Control Panel, its sensitivity, sleep timer, alarm notification with LED, and anti-masking function can be remotely programmed on the Control Panel.
* Remote settings will overwrite dip switch settings. It is suggested performing remote setting over dip switch setting.
* Please refer to the table below for remote settings:

<figure><img src=".gitbook/assets/image (339).png" alt=""><figcaption></figcaption></figure>

* Example: To configure the following setting

Sensitivity → _Medium_ // Individual → _Off_ // Anti-masking → _Enable_ // Sleep Timer → _5 Seconds_ // LED → _On_

The setting value will be _**0100 0111**_, which has to be converted into _**hex 0x47**_.

**Step 1.** After learning the detector, click “Edit” in the corresponding IR entry.

<figure><img src=".gitbook/assets/image (340).png" alt=""><figcaption></figcaption></figure>

_\<NOTE> For the detector being recognized as 2 devices, select the IR sensor having the ID ending with “**00**” for configuration._

**Step 2.** Enter the hex in the IR configuration and click OK to save the setting.

<figure><img src=".gitbook/assets/image (341).png" alt=""><figcaption></figcaption></figure>
