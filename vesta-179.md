# VESTA-179

**SCM-5ZBS**

## **Shutter Control  (Zigbee)**

<figure><img src=".gitbook/assets/image (390).png" alt=""><figcaption></figcaption></figure>

**Introduction**

SCM-5ZBS is a ZigBee Shutter Control. The user can control the SCM via ZigBee network at a remote distance or manually by linking a switch to the Shutter Control.

The Shutter Control utilizes ZigBee technology for wireless signal transmission. ZigBee is a wireless communication protocol that is reliable, has low power consumption and has high transmission efficiency. Based on the IEEE802.15.4 standard, ZigBee allows a large number of devices to be included in a network and coordinated for data exchange and signal transmission.

The Shutter Control serves as an end device in the ZigBee network. It can be included in the ZigBee network to transmit or receive signal, but cannot permit any other ZigBee device to join the network through the Shutter Control.

The SCM-5 ZigBee Shutter Control series includes the following models:

SCM-5ZBS

SCM-5ZBS-OTA

![](<.gitbook/assets/0 (77).jpeg>)

**Parts Identification**

**1. LED indicator**

The LED indicator is used to indicate Shutter Control status:

*
  * Flashes once: The Shutter Control has reset.
  * Flashes twice: The Shutter Control has successfully joined a ZigBee network.
  * Flashes 5 times: successful manual calibration.
  * Flashes once every 20 minutes:

The Shutter Control has lost connection to its current ZigBee network.

1. **Function Button**
   * Press once: Transmit a supervision signal.
   * Press and hold for 3\~9 seconds: Enter calibration mode.
   * Press and hold for 10 seconds: Reset the Shutter Control to join ZigBee network.
2. **Power input N (Neutral Lead) connection cable (Blue)**
3. **Power Input L (Live Lead) connection cable (Brown)**
4. **Local Switch S2 (Close Direction) connection cable (Orange)**

Connect an external switch to the cable. Activate this switch to control the shutter to roll toward “Close” direction by activating the Motor Output O2

Activating this switch when the shutter is rolling towards the open direction will stop the shutter.

**6. Local Switch S1 (Open Direction) connection cable (Red)**

Connect an external switch to the cable. Activate this switch to control the shutter to roll toward “Open” direction by activating the Motor Output O1 Activating this switch when the shutter is rolling towards the “Close” direction will stop the shutter.

**7. Motor Output O1 (Open Direction) connection cable (Yellow)**

Connect to the Open terminal of the Shutter Motor.

**8. Motor Output O2 (Close Direction) connection cable (Green)**

Connect to the Close terminal of the Shutter Motor.

**Specification**

* Power Supply: 110 - 230VAC, 50/60Hz
* Supported Load Current: 1/4 HP (Horse power); 1.8Amps for motors with compensated power factor (inductive loads)
* Communication Protocol: ZigBee Pro Home Automation 1.2, 2.4GHz

**Caution**

* All works on the device, including installation and maintenance, must be performed by a qualified and licensed electrician.
* Before installation or any maintenance work, make sure the power supply has been disconnected.
* Do not connect the device to loads exceeding supported load current.
* Please connect the device to AC powered motor only.

**ZigBee Network Setup**

* _**ZigBee Device Guideline**_

ZigBee is a wireless communication protocol that is reliable, has low power consumption and has high transmission efficiency. Based on the IEEE802.15.4 standard, ZigBee allows a number of devices to be included in a network and are coordinated for data exchange and signal transmission.

* _**Joining the ZigBee Network**_

As a ZigBee device, the Shutter Control needs to join a ZigBee network to receive commands. Please follow the steps below to join the Shutter Control into a ZigBee network.

*
  1. Connect the power cable to the power input connection cable (blue and brown) on the Shutter Control with the provided connector.
  2. Press and hold the function button for 10 seconds as the Shutter Control resets and starts searching for existing ZigBee network. Please make sure the permit-to-join feature on the router or coordinator of your ZigBee network is enabled.
  3. If the Shutter Control successfully joins a ZigBee network, the LED Indicator will flash twice to confirm.
  4. After joining the ZigBee network, the Shutter Control will be registered in the network automatically. Please check the ZigBee network coordinator, system control panel or CIE (Control and Indicating Equipment) to confirm if joining and registration is successful.
  5. After joining the ZigBee network, if the Shutter Control loses connection to the current ZigBee network, the LED indicator will flash every 20 minutes. Please check your ZigBee network condition and Shutter Control signal range to correct the condition.
* _**Removing Device from ZigBee Network (Factory Reset)**_

To remove the Shutter Control from current ZigBee network, the Shutter Control must be put to Factory Reset to complete device removal. Factory Reset function will clear the Shutter Control of its stored setting information and prompt the device to search for new ZigBee network.

**Before removing device, make sure the Shutter Control is within current ZigBee network signal range**

1. Press and hold the function button for 10 seconds, then release the button to reset Shutter Control.
2. Upon reset, the Shutter Control will clear current ZigBee network setting and transmit signal to ZigBee coordinator to remove itself from current ZigBee network. It will then actively search for available ZigBee network again and join the network automatically.

**Supervision**

The Shutter Control will transmit a supervision signal to report its condition regularly according to user setting. The factory default interval is 30 minutes. The user can also press the Function Button once to transmit a supervision signal manually.

**Installation**

* _**Wiring with Splicing Connector**_
  * SCM-5 comes with embedded terminal wires and clamps (Wago 221 Splicing Connectors).
  * The 2-wire connectors accommodate solid and stranded wires from 0.2 to 4 mm² (24–12 AWG).
  * Please connect SCM-5 to AC power, local switches, and shutter motor with the connectors.
  * Before wiring, please make sure the power is off. To connect the wires:
    1. Lift the lever and insert the wire. **(Picture 1, 2)**

![Picture1                                                                   Picture 2](<.gitbook/assets/2 (72).png>)

2. Push the lever back down. The transparent housing allows you to check if the wire is connected properly. Make sure the wire is held in place tightly and won't come off. **(Picture 3, 4)**

![Picture 3                                                                                   Picture 4](<.gitbook/assets/3 (72).png>)

3. In the same way as step 1 & 2, connect the other wires with connectors.

* SCM-5 should be connected according to the diagram below:

![](<.gitbook/assets/4 (49).jpeg>)

* Connect N terminal of SCM to the N terminal of Power Supply.
* Connect L terminal of SCM to the L terminal of Power Supply.
* Connect O1 terminal of SCM to the Open terminal of the Shutter Motor.
* Connect O2 terminal of SCM to the Close terminal of the Shutter Motor.
* **(Optional local switch)** Connect S2 and S1 terminals of SCM to the L terminal of Power Supply.

**Operation**

* _**Calibration**_
  * The Shutter Control default activation time is **4** minutes. When the Up/Down button is pressed or the ZigBee network coordinator transmits Up/Down command, it will activate the Shutter Motor for 4 minutes.
  * For the Shutter Control to work properly, its activation time must be calibrated. There are two ways to adjust the activation time:
    * **ZigBee Command:** The activation time can be adjusted by sending command from the ZigBee network coordinator. (See Appendix – Level Cluster Attribute – OnTransitionTime / OffTransitionTime, minimum adjustable unit 100ms)
    * **Manual Calibration:** Calibrate the activation according to procedure below:
      1. Before calibration, the external local switches must be connected to the Shutter Control.
      2. Press and hold the Function button for 3\~9 seconds and release to enter Calibration mode. The Shutter Control will roll toward the “Open” direction for 4 minutes upon entering Calibration mode.
      3. Wait for 4 minutes for Shutter Control to stop rolling to “Open” direction, then activate the connected external local “Close” switch to close the shutter.
      4. Activate the “Open” external local switch the moment the shutter is fully closed. The Shutter control will record the time it took between step 3 and 4 as the new “**close time**”.
      5. The Shutter Control will roll toward open direction after step 4.
      6. Activate the “Close” external local switch the moment the shutter is fully opened. The Shutter control will record the time it took between step 5 and 6 as the new “**open time**”.

Example

If it takes 30 seconds for the shutter to move from Open to Close, and 40 seconds to move from Close to Open, the new **close time** will be **30** seconds and new **open time** will be **40** seconds.

After calibration, whenever the Shutter Control receives close command, it will roll toward close direction for 30 seconds. When it receives open command, it will roll toward open for 40 seconds.

* The activation time will be reset to **4** minutes whenever the Shutter Control joins a ZigBee network.
* If the manual calibration process is successful, the LED will flash 5 times to indicate.
* _**Shutter Control**_

**ZigBee Network**

* After the Shutter Control has successfully joined a ZigBee network, the coordinator can remotely control the shutter to open, close or stop by transmitting command though ZigBee network.
* When the Shutter Control receives open/close signal from coordinator, it will roll toward open/close direction according to calibrated activation time to fully open/close the shutter.
* The Shutter status can also be adjusted by percentage from 0%, 10%, 20%... to 100% through ZigBee Coordinator.
* The current open percentage is also transmitted to ZigBee coordinator.

**Local Switch**

* If an optional Local Switch is connected, users can also press the switch button to open/close the shutter.
* Press and release the switch for less than 1 second will control the shutter to fully open or close.
* Press and hold the switch for more than 1 second will control the shutter to open and close until the switch is released. When the switch is released, the shutter will stop.
* Pressing the switch when the shutter is moving to opposite direction will stop the shutter. Press the switch again to open/close the shutter.

For example, pressing the down switch when the shutter is opening will stop the shutter, press down switch again to start closing the shutter.

* _**OTA Firmware Upgrade (For OTA version only)**_

The Shutter Control supports OTA firmware upgrade feature via ZigBee network, which can be initiated from the ZigBee network coordinator.

Follow steps below to perform OTA firmware upgrade.

**Step 1.** You have to access your ZigBee Coordinator to perform the firmware upgrade on the air. **Step 2.** On the configuration webpage, select the device that you wish to upgrade and select the new

ZigBee firmware provided. Please refer to ZigBee Coordinator User Manual for detail.

**Step 3.**&#x50;ress“OK”to start upgrading process, and the LED will keep flashing. During the OTA process,

please do not perform any other actions, or power down the panel.

**Step 4.**&#x54;he length of an upgrade will take approximately 20 to 30 minutes. Please note that the duration may vary based on file size or distance between your accessory and coordinator.

**Step 5.**&#x57;ait for firmware to complete update. When the progress reaches 100%, the Device will reset

automatically. You can also refresh the webpage again to ensure if the Device firmware is successfully updated with the newest version displayed.

## **Appendix (For developers only)**

* _**Power Relay Shutter Control with Meter Cluster ID**_

<figure><img src=".gitbook/assets/1 (2) (1).png" alt=""><figcaption></figcaption></figure>
