# VESTA-187

**WSS-4E-ZBS**

## **Smart Scenario Switch (Zigbee)**

<figure><img src=".gitbook/assets/image (399).png" alt=""><figcaption></figcaption></figure>

## **Introduction**

WSS-4E-ZBS is a ZigBee Four Touch Button Scenario Switch designed to control a group of pre-programmed home automation devices by simply pressing the scenario touch buttons under the same ZigBee network.

The Scenario Switch utilizes ZigBee technology for wireless signal transmission. ZigBee is a wireless communication protocol that is reliable and has low power consumption and high transmission efficiency. Based on the IEEE802.15.4 standard, ZigBee allows a large amount of devices to be included in a network and coordinated for data exchange and signal transmission.

The Scenario Switch serves as an end device in the ZigBee network. It can be included in the ZigBee network to transmit signal upon activation, and can control any ZigBee device, but cannot permit any other ZigBee device to join the network through the Scenario Switch.

The WSS-4E ZigBee Four Touch Button Scenario Switch includes the following models:

WSS-4E-ZBS

WSS-4E-ZBS-OTA

![](<.gitbook/assets/0 (84).jpeg>)

## **Device Introduction**

1. **Scenario LED**

There are four Scenario LEDs, the LED will light up according to the correspondent Scenario touch button pressed.

When the Scenario Switch receives acknowledge from the Control Panel after a button press, it will flash once and emit a beep as indication.

If the LED flashes twice upon touch button press, it means the ZigBee control panel was unable to receive signal sent from Scenario Switch, please check ZigBee connectivity.

2. **Scenario Touch Button**

The Scenario Switch has 4 scenario touch buttons:

![](<.gitbook/assets/image (4) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1).png>)Touch Button 1

<img src=".gitbook/assets/image (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1).png" alt="" data-size="original">Touch Button 2

<img src=".gitbook/assets/image (2) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1).png" alt="" data-size="original">Touch Button 3

![](<.gitbook/assets/image (3) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1).png>)Touch Button 4

3. **Battery Compartment**
4.  **Function Button**

    Press and hold for 10 seconds to reset.
5.  **ZigBee LED (Red)**

    Red LED lights up in the following situations:

    1. Flashes once: When sending control, resetting, or learning signal. When the Scenario Switch receives acknowledgement from the Control Panel after a button press.
    2. Flashes twice: The Scenario Switch has successfully joined a ZigBee network.
6. **Function Button Hole**

## **Features**

### _**Battery and Low Battery Detection**_

The Scenario Switch uses two 1.5V AA Alkaline batteries as its power source. The Scenario Switch feature Low Battery Detection function. When the battery voltage is low, the Scenario Switch will transmit Low Battery signal to the ZigBee network coordinator.

### _**Scenario**_

When a Scenario Touch Button is pressed, the Scenario Switch will send a signal to the Control Panel to activate the correspondent scenario (see Control Panel for details).

## **ZigBee Network Setup**

### _**ZigBee Device Guideline**_

ZigBee is a wireless communication protocol that is reliable and has low power consumption and high transmission efficiency. Based on IEEE802.15.4 standard, ZigBee allows a large amount of devices to be included in a network and coordinated for data exchange and signal transmission.

Due to the fundamental structure of ZigBee network, ZigBee device will actively seek and join network after powering on. Since performing a task in connecting network may consume some power, it is required to follow the instructions to avoid draining battery of a ZigBee device.

* Ensure your ZigBee network router or coordinator is powered on before inserting battery into ZigBee device.
* Ensure the ZigBee network router or coordinator is powered on and within range while a ZigBee device is in use.
* Do not remove a ZigBee device from the ZigBee network router or coordinator without removing the battery from a ZigBee device.

### _**Joining the ZigBee Network**_

As a ZigBee device, the Scenario Switch needs to join a ZigBee network to connect to the ZigBee devices.

Please follow the steps bellow to join the Scenario Switch into the ZigBee network.

1. Remove the cover by using a screwdriver.
2. Insert the battery then replace the cover.
3. Press and hold the Function Button for 10 seconds and release when the Red LED flashes once to join ZigBee network. Please make sure to enable the permit-join feature on the router or coordinator of your ZigBee network.
4. If the Scenario Switch successfully joins a ZigBee network, the Red LED Indicator will flash twice to confirm.
5. After joining the ZigBee network, the Scenario Switch will be registered in the network automatically. Please check the ZigBee network coordinator, system control panel or CIE (Control and Indicating Equipment) to confirm if joining and registration is successful.

### _**Removing Device from ZigBee Network (Factory Reset)**_

To remove the Scenario Switch from current ZigBee network, the switch must be put to Factory Reset to complete device removal. Factory Reset function will clear the d of its stored setting information and prompt the Scenario Switch to search for new ZigBee network.

**Before removing device, make sure the Scenario Switch is within current ZigBee network signal range**

1. Press and hold the function button for 10 seconds, then release the button to reset Scenario Switch.
2. Upon reset, the Scenario Switch will clear current ZigBee network setting and transmit signal to ZigBee coordinator to remove itself from current ZigBee network. It will then actively search for available ZigBee network again and join the network automatically.

### _**OTA Firmware Upgrade (For OTA version only)**_

The Four Touch Button Scenario Switch supports OTA firmware upgrade feature via ZigBee network, which can be initiated from the ZigBee network coordinator. Follow steps below to perform OTA firmware upgrade.

**Step 1.** You have to access your ZigBee Coordinator to perform the firmware upgrade on the air.

**Step 2.** On the configuration webpage, select the device that you wish to upgrade and select the new ZigBee firmware provided. Please refer to ZigBee Coordinator User Manual for detail.

**Step 3.**&#x50;ress“OK”to start upgrading process, and the LED will keep flashing. During the OTA process, please do not perform any other actions, or power down the panel.

**Step 4.**&#x54;he length of an upgrade will take approximately 20 to 30 minutes. Please note that the duration may vary based on file size or distance between your accessory and coordinator.

**Step 5.**&#x57;ait for firmware to complete update. When the progress reaches 100%, the Device will reset automatically. You can also refresh the webpage again to ensure if the Device firmware is successfully updated with the newest version displayed.

### **Installation**

* The Scenario Switch is designed to be mounted on a flat surface with fixing screws.
* The base has 3 knockouts, where the plastic is thinner, for mounting purpose.
  1. Remove the cover by using a screwdriver.
  2. Break through the appropriate knockouts on the base.
  3. Using the holes as a template, drill holes in the surface.
  4. Screw the base into the surface.
  5. Replace the cover back onto the base and secure it by tightening the fixing screw.



![](<.gitbook/assets/8 (41).jpeg>)

