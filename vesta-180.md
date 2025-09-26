# VESTA-180

**SCS-1-ZBS**&#x20;

## **Shutter Control Switch (Zigbee)**

<figure><img src=".gitbook/assets/image (392).png" alt=""><figcaption></figcaption></figure>

## **Introduction**

SCS-1-ZBS is a ZigBee Three-Button Shutter Control Switch designed to control a group of pre-programmed home automation devices by simply pressing the scenario buttons. Through setting the shutter control scenario on the ZigBee network coordinator/ control panel, the Shutter Control Switch will be able to control shutter movement by simply pressing its buttons.

The Shutter Switch utilizes ZigBee technology for wireless signal transmission. ZigBee is a wireless communication protocol that is reliable and has low power consumption and high transmission efficiency. Based on the IEEE802.15.4 standard, ZigBee allows a large amount of devices to be included in a network and coordinated for data exchange and signal transmission.

The Shutter Switch serves as an end device in the ZigBee network. It can be included in the ZigBee network to transmit signal upon activation, and can control any ZigBee device, but cannot permit any other ZigBee device to join the network through the Shutter Switch.

The SCS-1 ZigBee Shutter Control Switch includes the following models:

SCS-1-ZBS

SCS-1-ZBS-OTA

![](<.gitbook/assets/0 (78).jpeg>)

## **Device Introduction**

1.  **Scenario LED**

    When any of the 3 scenario buttons are pressed, the LED will light up briefly
2.  &#x20;**Scenario Buttons**

    The Shutter Control Switch has 3 scenario buttons
3. **Battery Compartment**
4. **Function Button**
   * Press and hold for 10 seconds to reset.
5.  **ZigBee LED (Red)**

    Red LED lights up in the following situations:

    1. Flashes once: When sending control signal/ resetting/ learning.
    2. Flashes twice: The Shutter Control Switch has successfully joined a ZigBee network.
6. **Function Button Hole**

## **Features**

### _**Battery and Low Battery Detection**_

The Shutter Control Switch uses two 1.5V AA Alkaline batteries as its power source. The switch feature Low Battery Detection function. When the battery voltage is low, the Shutter Control Switch will transmit Low Battery signal to the ZigBee network coordinator.

### _**Supervision**_

The Shutter Control Switch will transmit a supervision signal to report its condition regularly according to user set interval time. The factory default interval is 30 minutes.

### _**Scenario and Shutter Control**_

When a Scenario Button is pressed, the Shutter Control Switch will send a signal to the Control Panel to activate the correspondent scenario (see Control Panel for details). Set the scenario in the Control Panel to control the open/close/stop function of the shutter to operate the shutter through the Scenario Control Switch. The switch will emit a beep as indication when the button is pressed.

## **ZigBee Network Setup**

### _**ZigBee Device Guideline**_

ZigBee is a wireless communication protocol that is reliable and has low power consumption and high transmission efficiency. Based on IEEE802.15.4 standard, ZigBee allows a large amount of devices to be included in a network and coordinated for data exchange and signal transmission.

Due to the fundamental structure of ZigBee network, ZigBee device will actively seek and join network after powering on. Since performing a task in connecting network may consume some power, it is required to follow the instructions to avoid draining battery of a ZigBee device.

* Ensure your ZigBee network router or coordinator is powered on before inserting battery into ZigBee device.
* Ensure the ZigBee network router or coordinator is powered on and within range while a ZigBee device is in use.
* Do not remove a ZigBee device from the ZigBee network router or coordinator without removing the battery from a ZigBee device.

### _**Joining the ZigBee Network**_

As a ZigBee device, the Shutter Control Switch needs to join a ZigBee network to connect to the ZigBee devices. Please follow the steps bellow to join the Shutter Control Switch into the ZigBee network.

1. Remove the cover by using a screwdriver.
2. Insert the battery then replace the cover.
3. Press and hold the Function Button for 10 seconds and release when the Red LED flashes once to join ZigBee network. Please make sure to enable the permit-join feature on the router or coordinator of your ZigBee network.
4. If the Shutter Control Switch successfully joins a ZigBee network, the Red LED Indicator will flash twice to confirm.
5. After joining the ZigBee network, the Shutter Control Switch will be registered in the network automatically. Please check the ZigBee network coordinator, system control panel or CIE (Control and Indicating Equipment) to confirm if joining and registration is successful.

### _**Removing Device from ZigBee Network (Factory Reset)**_

To remove the device from current ZigBee network, the Shutter Control Switch must be put to Factory Reset to complete device removal. Factory Reset function will clear the device of its stored setting information and prompt the Shutter Control Switch to search for new ZigBee network.

**Before removing device, make sure the Shutter Control Switch is within current ZigBee network signal range**

1. Delete the Shutter Control from current control panel / CIE.
2. Press and hold the function button for 10 seconds, then release the button to reset the device.
3. Upon reset, the Shutter Control Switch will clear current ZigBee network setting and transmit signal to ZigBee coordinator to remove itself from current ZigBee network. It will then actively search for available ZigBee network again and join the network automatically.

### _**OTA Firmware Upgrade (For OTA version only)**_

The Shutter Control Switch supports OTA firmware upgrade feature via ZigBee network, which can be initiated from the ZigBee network coordinator.

Follow steps below to perform OTA firmware upgrade.

**Step 1.** You have to access your ZigBee Coordinator to perform the firmware upgrade on the air.

**Step 2.** On the configuration webpage, select the device that you wish to upgrade and select the new ZigBee firmware provided. Please refer to ZigBee Coordinator User Manual for detail.

**Step 3.** Press“OK”to start upgrading process, and the LED will keep flashing. During the OTA process, please do not perform any other actions, or power down the panel.

**Step 4.** The length of an upgrade will take approximately 20 to 30 minutes. Please note that the duration may vary based on file size or distance between your accessory and coordinator.

**Step 5.** Wait for firmware to complete update. When the progress reaches 100%, the Device will reset automatically. You can also refresh the webpage again to ensure if the Device firmware is successfully updated with the newest version displayed.

## **Installation**

The Shutter Control Switch is designed to be mounted on a flat surface with fixing screws.

The base has 3 knockouts, where the plastic is thinner, for mounting purpose.

1. Remove the cover by using a screwdriver.
2. Break through the appropriate knockouts on the base.
3. Using the holes as a template, drill holes in the surface.
4. Screw the base into the surface.
5. Replace the cover back onto the base and secure it by tightening the fixing screw.

![](<.gitbook/assets/9 (26).jpeg>)

## **Appendix (For developers only)**

_**Scene Selector Cluster ID**_

<figure><img src=".gitbook/assets/image (180).png" alt=""><figcaption></figcaption></figure>

* _**Attribute of Basic Cluster Information**_

<figure><img src=".gitbook/assets/image (181).png" alt=""><figcaption></figcaption></figure>

* _**Attribute of Identify Cluster Information**_

<figure><img src=".gitbook/assets/image (183).png" alt=""><figcaption></figcaption></figure>

* Attribute of Power Configuration Cluster Information

<figure><img src=".gitbook/assets/image (184).png" alt=""><figcaption></figcaption></figure>

* Shade Controller Cluster ID (for HPGW-G panel)

<figure><img src=".gitbook/assets/image (185).png" alt=""><figcaption></figcaption></figure>

* _**Attribute of**_ Basic Cluster Information

<figure><img src=".gitbook/assets/image (186).png" alt=""><figcaption></figcaption></figure>

* Attribute of Identify Cluster Information

<figure><img src=".gitbook/assets/image (187).png" alt=""><figcaption></figcaption></figure>

* Attribute of Power Configuration Cluster Information

<figure><img src=".gitbook/assets/image (188).png" alt=""><figcaption></figcaption></figure>
