# VESTA-182

**PRLM-CH3-AC-ZBS(R)**

## **ZigBee Relay Switch**

**Introduction**

PRLM-CH3-AC-ZBS(R) is a ZigBee 3-channel Relay Switch that can be connected to wired devices and set to Normal Open (N.O.) status. After joining ZigBee network, the Relay Switch can be controlled via ZigBee network to activate connected devices.

The Relay Switch utilizes ZigBee technology for wireless signal transmission. ZigBee is a wireless communication protocol that is reliable, has low power consumption and has high transmission efficiency. Based on the IEEE802.15.4 standard, ZigBee allows a large amount of devices to be included in a network and coordinated for data exchange and signal transmission.

The Relay Switch also features router function. It serves as a router in the ZigBee network. After being included in the ZigBee network, it allows other ZigBee devices to join the network through the Relay Switch.

## **Parts Identification**



![Top Cover                                                                                                                Base](<.gitbook/assets/0 (80).jpeg>)

1. **Switch Button 1/Function Button**
   * The function button is used for resetting the Relay Switch to join an available ZigBee network.
   * Press and hold the button for 10 seconds then release to reset the Relay Switch.
   * Press the button to switch ON/OFF the Relay Channel 1.
2. **Switch Button 2**
   * Press the button to switch ON/OFF the Relay Channel 2.
3. **Switch Button 3**
   * Press the button to switch ON/OFF the Relay Channel 3.

{% hint style="warning" %}
Note:

When Switch Button 2/3 is pressed, the Relay Channel 2/3 will instantly switch to ON/OFF.

When Switch Button 1 is pressed, the Relay Channel 1 will switch to ON/OFF after 0.5 second, because the device needs to identify whether the button press is for switch on/off or for resetting the Relay.
{% endhint %}

4. **LED indicator 1**
5. **LED indicator 2**
6. **LED indicator 3**

The LED indicator 1/2/3 are used to indicate Relay Channel 1/2/3 status:

* LED 1 On/Off: Relay Channel 1 On/Off
* LED 2 On/Off: Relay Channel 2 On/Off
* LED 3 On/Off: Relay Channel 3 On/Off

When powered on, all LEDs will sequentially flash for 1 cycle.

All LEDs will flash every second after the Relay has reset, indicating that it is under learning mode.

All LEDs will flash three times when the Relay has successfully joined a ZigBee network.

**7. Mounting Holes**

### **Connection Terminals**

Connect the wire into the terminal, tighten the screw to close the clipper and hold wire in place. Unscrew to open the clipper to remove the wire connected to the terminal.

8. **Line (AC input)**
9. **Neutral**
10. **NO (Channel 1)**

&#x20;     For Normal Open connection with the device

11. **Common (Channel 1)**
12. **NO (Channel 2)**

&#x20;       For Normal Open connection with the device

13. **Common (Channel 2)**
14. **NO (Channel 3)**

&#x20;      For Normal Open connection with the device

15. **Common (Channel 3)**
16. **Strain Relief Clamp**

&#x20;      The clamps are used for securing the wires, and providing strain relief to protect the wires from the metal cutout.

**17. Wiring Holes**

## **Specification**

* Power Supply: 100 - 240V AC
* Supported Load Current (for each relay channel): 5A, 250VAC or 5A, 30VDC
* Stranded Wire: 14–22 AWG

**Caution**

* All works on the device, including installation and maintenance, must be performed by a qualified and licensed electrician.
* Before installation or any maintenance work, make sure the power supply has been disconnected.
* Do not connect the device to loads exceeding supported load current.

**Installation**

Wire the Relay according to the instructions below.

1. Please turn off the power supply before connection.
2. Remove the top cover and remove the strain relief clamps.
3. Connect the L and N terminals of the power supply to the Line and Neutral terminals of PRLM respectively through the wiring hole.
4. Depending on the device you wish to control via Relay Channel 1, select NO terminal and wire Relay Channel 1 with the device through the wiring hole to establish Normal Open connection with device.
5. In the same way as step 4, connect Relay Channel 2/3 to other wired devices.
6. After completing the wiring, replace the strain relief clamps and the top cover. Turn on the power supply to power on the Relay Switch.

![](<.gitbook/assets/2 (61).jpeg>)

## **ZigBee Network Setup**

* _**ZigBee Device Guideline**_

ZigBee is a wireless communication protocol that is reliable, has low power consumption and has high transmission efficiency. Based on the IEEE802.15.4 standard, ZigBee allows a large amount of devices to be included in a network and are coordinated for data exchange and signal transmission.

* _**Joining the ZigBee Network**_

As a ZigBee device, the Relay needs to join a ZigBee network to receive commands. Please follow the steps below to add the Relay into a ZigBee network.

*
  1. Connect the power input to the Relay according to Installation instruction above, and power up the Relay Switch.
  2. Press and hold the function button for 10 seconds as the Relay resets and starts searching for existing ZigBee network. Please make sure the permit-to-join feature on the router or coordinator of your ZigBee network is enabled.
  3. If the Relay successfully joins a ZigBee network, the LED Indicator will flash three times to confirm.
  4. After joining the ZigBee network, the Relay will be registered in the network automatically. Please check the ZigBee network coordinator, system control panel or CIE (Control and Indicating Equipment) to confirm if joining and registration is successful.
* _**Removing Device from ZigBee Network (Factory Reset)**_

To remove the device from current ZigBee network, the Relay Switch must be put to Factory Reset to complete device removal. Factory Reset function will clear the device of its stored setting information and prompt the device to search for new ZigBee network.

**Before removing device, make sure the Relay Switch is within current ZigBee network signal range**

1. Delete the device from current control panel / CIE.
2. Press and hold the function button for 10 seconds, then release the button to reset the device.
3. Upon reset, the device will clear current ZigBee network setting and transmit signal to ZigBee coordinator to remove itself from current ZigBee network. It will then actively search for available ZigBee network again and join the network automatically.

* _**Range Test**_

To test whether the device is able to communicate with the ZigBee network coordinator or control panel:

* Put the gateway/panel into range test mode (Walk Test).
* Press the Function Button on the device
* The gateway/panel should display if the device is within the operation range (please refer to the operation manual of the gateway/panel).
* _**ZigBee Router Device Capacity**_

The Relay Switch features Router function that allows other ZigBee devices to join the ZigBee Network through the Router. It has maximum capacity of 40 devices/routers.

### **Supervision**

The Relay Switch will transmit a supervision signal to report the ON/OFF status of Relay Channel 1/2/3 regularly according to user setting. The factory default interval is 30 minutes.

## **Mounting**

* After you have finished the range test, and you are satisfied that the device is able to communicate with the Control Panel in the chosen location, proceed to mounting.
* Disconnect the main power supply.
* Loosen the bottom fixing screw and remove the top cover of the Relay Switch.
* Use the holes on the base to mark mounting location on the wall.
* Drill holes into marked location and insert wall plugs if required, screw the base onto the mounting location.
* Replace the top cover and tighten the bottom fixing screw.

![](<.gitbook/assets/8 (39).jpeg>)

## **Operation**

* _**Relay Control**_
  * After the Relay Switch has successfully joined a ZigBee network, the gateway/control panel can remotely control the Relay Channel 1/2/3 to turn On/Off. Please refer to your ZigBee gateway/control panel for detail.
  * The user can also manually press the Switch Button 1/2/3 to switch ON/OFF the Relay Channel 1/2/3.
* _**OTA Firmware Upgrade**_

The Relay Switch supports OTA firmware upgrade feature via ZigBee network, which can be initiated from the ZigBee network coordinator.

Follow steps below to perform OTA firmware upgrade.

**Step 1.** You have to access your ZigBee Coordinator to perform the firmware upgrade on the air. **Step 2.** On the configuration webpage, select the device that you wish to upgrade and select the

new ZigBee firmware provided. Please refer to ZigBee Coordinator User Manual for detail.

**Step 3.** Press “OK” to start upgrading process. During the OTA process, please do not perform any other actions, or power down the panel.

**Step 4.**&#x54;he length of an upgrade will take approximately 20 to 30 minutes. Please note that the duration may vary based on file size or distance between your accessory and coordinator.

**Step 5.**&#x57;ait for firmware to complete update. When the progress reaches 100%, the Device will reset automatically. You can also refresh the webpage again to ensure if the Device firmware is successfully updated with the newest version displayed.

**Appendix (For developers only)**

* _**Relay Cluster ID**_

<figure><img src=".gitbook/assets/2 (2) (1).png" alt=""><figcaption></figcaption></figure>

<figure><img src=".gitbook/assets/3 (1) (1) (1) (1) (1) (1).png" alt=""><figcaption></figcaption></figure>
