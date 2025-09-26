# VESTA-191

**PRL-8ZBS(R)-AC-OTA**

## **ZigBee Relay Controller**&#x20;

## **Introduction**

PRL-8ZBS-AC-OTA is a ZigBee Relay Controller that can be connected to wired devices and set to either Normal Open (N.O.) or Normal Close (N.C.) status. After joining ZigBee network, the Relay Controller can be controlled via ZigBee network to activate connected devices.

The Relay Controller utilizes ZigBee technology for wireless signal transmission. ZigBee is a wireless communication protocol that is reliable, has low power consumption and has high transmission efficiency. Based on the IEEE802.15.4 standard, ZigBee allows a large amount of devices to be included in a network and coordinated for data exchange and signal transmission.

The Relay Controller serves as an end device in the ZigBee network. It can be included in the ZigBee network to transmit or receive signal, but cannot permit any other ZigBee device to join the network through the Relay Controller.

Models with router function also serve as a router in the ZigBee network. After being included in the ZigBee network, it allows other ZigBee devices to join the network through the Relay Controller.

## **Parts Identification**

![](<.gitbook/assets/0 (87).jpeg>)

1. **Function Button**

The function button is used to reset the Relay Controller to join an available ZigBee network.

Press and hold the button for 10 seconds then release to reset the Relay Controller.

2. **LED indicator (Red)**

The LED indicator is used to indicate Relay status:

* Flashes once: The Relay has reset.
* Flashes twice: The Relay has successfully joined a ZigBee network.
* Flashes once every 20 minutes:
* The Relay has lost connection to its current ZigBee network.

#### **Connection Terminals**

Connect the wire into the terminal, tighten the screw to close the clipper and hold wire in place. Unscrew to open the clipper to remove the wire connected to the terminal.

3. **Line (AC input)**
4. **Neutral**
5.  **NO**

    For Normal Open connection with the device.
6. **Common**
7.  **NC**

    For Normal Close connection with the device
8. **Strain Relief Clamp**

The clamp is used for securing the wires, and providing strain relief to protect the wires from the metal cutout.

9.  **Wiring Buckle**

    The Wiring Buckle is used for managing wires.

## **Specification**

* Power Source (External Power): 100-240VAC
* Relay Output: Potential-free SPDT relay, Maximum Operation Load: 10A (Resistive) at 24VDC or 240VAC
* Stranded Wire: 14 \~ 22 AWG
* Operating Temperature: -10°C to 45°C (14°F to 113°F)
* Humidity: Up to 85% non-condensing
* Dimension: 86mm x 72mm x 29mm

## **Installation Environment** <img src=".gitbook/assets/image (2) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1).png" alt="" data-size="line">

* The Relay Controller should be installed indoors in a dry location.
* It is recommended to install the device in a fire resistant plastic gangbox.
* Do not install the device in a metal gangbox for optimization of Z-Wave range.

## **Caution** <img src=".gitbook/assets/image (2) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1).png" alt="" data-size="line">

* All works on the device, including installation and maintenance, must be performed by a qualified and licensed electrician.
* To prevent electrical shock and/or equipment damage, disconnect electrical power at the main fuse or circuit breaker before installation and maintenance.

Do not connect the device to loads exceeding supported load current.

**Installation**

![](<.gitbook/assets/3 (63).jpeg>)

Wiring of the PRL should only be performed by certified technician with proper knowledge and training in electric equipment. Wire the Relay according to the instructions below:

1. Turn off the power supply before connection.
2. Remove the top cover and remove the strain relief clamp.
3. Connect the L and N terminals of the power supply to the Line and Neutral terminals of PRL respectively through the wiring hole.
4. Depending on the device you wish to control via the Relay, select NO or NC terminal and wire the Relay with the device to establish Normal Open or Normal Close connection with device.
5. After completing device wiring, replace the strain relief clamp, use the wiring buckle to manage the wires, and place the wiring buckle on the base with its gap (opening) positioned on the left (as in the diagram below).

![](<.gitbook/assets/4 (56).jpeg>)

6. Replace the top cover. Turn on the power supply to power on the Relay Controller.

## **ZigBee Network Setup**

### _**ZigBee Device Guideline**_

ZigBee is a wireless communication protocol that is reliable, has low power consumption and has high transmission efficiency. Based on the IEEE802.15.4 standard, ZigBee allows a large amount of devices to be included in a network and are coordinated for data exchange and signal transmission.

### _**Joining the ZigBee Network**_

As a ZigBee device, the Relay Controller needs to join a ZigBee network to receive commands. Please follow the steps bellow to join the Relay Controller into a ZigBee network.

1. Connect the power input to the Relay Controller according to Installation instruction above and power up the Relay Controller.
2. Press and hold the function button for 10 seconds as the Relay Controller resets and starts searching for existing ZigBee network. Please make sure the permit-to-join feature on the router or coordinator of your ZigBee network is enabled.
3. If the Relay Controller successfully joins a ZigBee network, the LED Indicator will flash twice to confirm.
4. After joining the ZigBee network, the Relay Controller will be registered in the network automatically. Please check the ZigBee network coordinator, system control panel or CIE (Control and Indicating Equipment) to confirm if joining and registration is successful.
5. After joining the ZigBee network, if the Relay Controller loses connection to the current ZigBee network, the LED indicator will flash every 20 minutes. Please check your ZigBee network condition and Relay Controller signal range to correct the condition.

### _**Removing Device from ZigBee Network (Factory Reset)**_

To remove the Relay Controller from current ZigBee network, the device must be put to Factory Reset to complete device removal. Factory Reset function will clear the device of its stored setting and information and prompt it to search for new ZigBee network.

**Before removing device, make sure the Relay Controller is within current ZigBee network signal range**

1. Press and hold the function button for 10 seconds, then release the button to reset Relay Controller.
2. Upon reset, the device will clear current ZigBee network setting and transmit signal to ZigBee coordinator to remove itself from current ZigBee network. It will then actively search for available ZigBee network again and join the network automatically.

### _**OTA Firmware Upgrade (For OTA version only)**_

The Power Controller supports OTA firmware upgrade feature via ZigBee network, which can be initiated from the ZigBee network coordinator. Follow steps below to perform OTA firmware upgrade.

**Step 1.** You have to access your ZigBee Coordinator to perform the firmware upgrade on the air.

**Step 2.** On the configuration webpage, select the device that you wish to upgrade and select the new ZigBee firmware provided. Please refer to ZigBee Coordinator User Manual for details.

**Step 3.** Press“OK”to start upgrading process, and the LED will keep flashing. During the OTA process, please do not perform any other actions, or power down the panel.

**Step 4.** The length of an upgrade will take approximately 20 to 30 minutes. Please note that the duration may vary based on file size or distance between your accessory and coordinator.

**Step 5.** Wait for firmware to complete update. When the progress reaches 100%, the Device will reset automatically. You can also refresh the webpage again to ensure that the Device firmware is successfully updated with the newest version displayed.

### _**ZigBee Router Device Capacity (PRL-8ZBSR-AC Only)**_

The Relay Controller model with Router function allows other ZigBee devices to join the ZigBee Network through the Router. It has maximum capacity of 40 devices/routers.

## **Operation**

#### _**Relay Control**_

When the Relay Controller has successfully joined a ZigBee network, the gateway/control panel will be able to remotely control it to turn On, Off or toggle between On and Off condition. Please refer to your ZigBee gateway/control panel for details.



## **Appendix (For developers only)**

### _**Relay Cluster ID**_

<figure><img src=".gitbook/assets/image (3) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1).png" alt=""><figcaption></figcaption></figure>

### Attribute of Basic Cluster Information

<figure><img src=".gitbook/assets/image (4) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1).png" alt=""><figcaption></figcaption></figure>

### Attribute of Identify Cluster Information

<figure><img src=".gitbook/assets/image (5) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1).png" alt=""><figcaption></figcaption></figure>

### Attribute of On/Off Cluster Information

<figure><img src=".gitbook/assets/image (6) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1).png" alt=""><figcaption></figcaption></figure>

### Attributes of the Groups cluster Information

<figure><img src=".gitbook/assets/image (7) (1) (1) (1) (1) (1) (1) (1) (1).png" alt=""><figcaption></figcaption></figure>
