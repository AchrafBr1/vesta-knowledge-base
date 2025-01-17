# VESTA-185

## **LMHT-1ZBS Ambient Light, Humidity and Temperature Sensor**

## **Introduction**

LMHT-1ZBS is a ZigBee Ambient Light, Humidity and Temperature Sensor. It monitors your home environment and transmits measured Illuminance (lux), humidity and temperature to the coordinator in the ZigBee network.

The sensor utilizes ZigBee technology for wireless signal transmission. ZigBee is a wireless communication protocol that is reliable, has low power consumption and high transmission efficiency. Based on the IEEE802.15.4 standard, ZigBee allows a large amount of devices to be included in a network and coordinated for data exchange and signal transmission.

The sensor serves as an end device in the ZigBee network. It can be included in the ZigBee network to transmit signal upon activation, but cannot permit any other ZigBee device to join the network through the sensor.

## **Parts Identification**

![](<.gitbook/assets/0 (82).jpeg>)

1. **Light Sensor / LED Indicator**
   * **Flashes once:** Factory Reset
   * **Flashes twice:** After the sensor has successfully joined a ZigBee network.
   * **Flashes 3 times:** Battery inserted.
   * **Flashes 5 times:** Low battery detected when inserting battery.
   * **Flashes once every 20 minutes:** The sensor has lost connection to its current ZigBee network.
2. **Temperature Sensor**
3. **Battery Compartment**
4. **Function Button**
   * Press once to send a signal to the coordinator.
   * Press and hold for 10 seconds to reset the device.

## **Features**

### _**Lighting, Humidity and Temperature Monitoring**_

The sensor measures illuminance, humidity and temperature to transmit measured data to ZigBee network coordinator regularly.

Illuminance reading is transmitted every 30 minutes.

Humidity and temperature reading is transmitted every 10 minutes. The sensor will also transmit signal automatically when:

* The temperature changes by +/- 2°C.
* Humidity changes +/- 10%.
* When the current illuminance changes by +/- 10%.
*   The change level required to trigger signal transmission is programmable using ZigBee Configure Reporting command – Reportable Change parameter.&#x20;

    The default values are:

    Temperature: **200** for 2°C.

    Humidity: **1000** for 10%.

    Illuminance: **10** for 10%.

You can also press the Function Button once to transmit current reading manually.

### _**Battery and Low Battery Detection**_

* The sensor uses one CR123A 3V Lithium battery as its power source.
* The sensor features Low Battery Detection function. When the battery voltage is low, the sensor will transmit Low Battery signal to the coordinator in ZigBee network
* When changing battery, after removing the old batteries, press the Function Button twice to fully discharge before inserting new battery.
* If low battery voltage is detected upon inserting new battery, the LED indicator will flash 5 times.

### _**Supervision**_

The sensor will transmit a supervision signal along with the reading signal to report its condition regularly. The factory default interval is 30 minutes, which can be adjusted according to setting.

## **ZigBee Network Setup**

### _**ZigBee Device Guideline**_

ZigBee is a wireless communication protocol that is reliable and has low power consumption and high transmission efficiency. Based on the IEEE802.15.4 standard, ZigBee allows a large amount of devices to be included in a network and coordinated for data exchange and signal transmission.

Due to the fundamental structure of ZigBee network, ZigBee device will actively seek and join network after powering on. Since performing a task in connecting network may consume some power, it is required to follow the instructions to avoid draining battery of a ZigBee device

* Ensure your ZigBee network router or coordinator is powered on before inserting battery into the ZigBee device.
* Ensure the ZigBee network router or coordinator is powered on and within range while a ZigBee device is in use.
* Do not remove a ZigBee device from the ZigBee network router or coordinator without removing the battery from a ZigBee device.

### _**Joining the ZigBee Network**_

As a ZigBee device, the sensor needs to join a ZigBee network to transmit signal. Please follow the steps below to join the sensor into the ZigBee network.

1. Detach the Top Cover and Base assembly and insert battery.
2. Press and hold the function button for 10 seconds as the sensor resets (LED flashes once) and starts searching for existing ZigBee network. Please make sure the permit-to-join feature on the router or coordinator of your ZigBee network is enabled.
3. If the sensor successfully joins a ZigBee network, the LED Indicator will flash twice to confirm.
4. After joining the ZigBee network, the sensor will be registered in the network automatically. Please check your ZigBee coordinator, system control panel or CIE (Control and Indicating Equipment) to confirm if joining and registration is successful.
5. After joining the ZigBee network, if the sensor loses connection with current ZigBee network, the LED will flash every 20 minutes to indicate. Please check your ZigBee network condition and sensor signal range to correct the situation.

### _**Removing Device from ZigBee Network (Factory Reset)**_

To remove the device from current ZigBee network, the sensor must be put to Factory Reset to complete device removal. Factory Reset function will clear the device of its stored setting information and prompt the sensor to search for new ZigBee network.

**Before removing device, make sure the sensor is within current ZigBee network signal range**

1. Press and hold the function button for 10 seconds, then release the button to reset sensor.
2. Upon reset, the sensor will clear current ZigBee network setting and transmit signal to ZigBee coordinator to remove itself from current ZigBee network. It will then actively search for available ZigBee network again and join the network automatically.

## **Installation**

### _**Mounting the Sensor**_

<figure><img src=".gitbook/assets/image (197).png" alt="" width="151"><figcaption></figcaption></figure>

The sensor can be mounted using two methods: Self-adhesive or Screw mounting.

**Self adhesive mounting**

1. Clean the surface with a suitable degreaser.
2. Remove the protective covering from one side of double-sided adhesive pad and firmly apply to the back of the device.
3. Remove the other covering and firmly place/press the device in the desired location.

Do not use the Self-adhesive mounting method on poorly painted and/or rough surfaces.

**Screw Mounting**

The base of the sensor has two screw knockouts, where the plastic is thinner for mounting purposes. To mount the sensor:

1. Detach the Top Cover and Base assembly by loosening the Cover-Fixing Screw using a Philips screwdriver.
2. Break through the knockouts on the base.
3. Use the holes as a template to drill two holes and insert the wall plugs.
4. Screw the base into the wall plugs.
5. Replace the top cover over the base by hooking the base onto the fixing hook and pushing the cover towards the base.
6. Secure and screw the top cover back on to its base using a Philips screwdriver.

### _**Using the Sensor with ZigBee Router**_

{% hint style="info" %}
_**IMPORTANT NOTE**_

If the sensor installation location is away from your system control panel and requires ZigBee routers to improve signal strength. **DO NOT** use a ZigBee Router without backup battery. A ZigBee router without battery will be powered down during AC power failure and the sensor connected to the router will lose connection with ZigBee network. You should plan your sensor installation location using only ZigBee router with backup battery.
{% endhint %}

### _**OTA Firmware Upgrade (For OTA version only)**_

The Ambient Light, Humidity and Temperature Sensor supports OTA firmware upgrade feature via ZigBee network, which can be initiated from the ZigBee network coordinator. Follow steps below to perform OTA firmware upgrade.&#x20;

**Step 1.** You have to access your ZigBee Coordinator to perform the firmware upgrade on the air.

**Step 2.** On the configuration webpage, select the device that you wish to upgrade and select the new ZigBee firmware provided. Please refer to ZigBee Coordinator User Manual for details.

**Step 3.**&#x50;ress“OK”to start upgrading process, and the LED will keep flashing. During the OTA process, please do

not perform any other actions, or power down the panel.

**Step 4.**&#x54;he length of an upgrade will take approximately 20 to 30 minutes. Please note that the duration may vary based on file size or distance between your accessory and coordinator.

**Step 5.**&#x57;ait for firmware to complete update. When the progress reaches 100%, the Device will reset automatically. You can also refresh the webpage again to ensure that the Device firmware is successfully updated with the newest version displayed.

## **Appendix**

**(The Appendix information is for developers only.)**

_**Light Sensor Cluster ID**_

<figure><img src=".gitbook/assets/image (198).png" alt=""><figcaption></figcaption></figure>

_**Attribute of Basic Cluster Information**_

<figure><img src=".gitbook/assets/image (199).png" alt=""><figcaption></figcaption></figure>

<figure><img src=".gitbook/assets/image (200).png" alt=""><figcaption></figcaption></figure>

_**Attribute of Identify Cluster Information**_

<figure><img src=".gitbook/assets/image (201).png" alt=""><figcaption></figcaption></figure>

_**Attribute of Power Configuration Cluster Information**_

<figure><img src=".gitbook/assets/image (202).png" alt=""><figcaption></figcaption></figure>

_**Attribute of Illuminance Measurement Cluster Information**_

<figure><img src=".gitbook/assets/image (203).png" alt=""><figcaption></figcaption></figure>

_**Attribute of Temperature Measurement Cluster Information**_

<figure><img src=".gitbook/assets/image (204).png" alt=""><figcaption></figcaption></figure>

_**Attribute of Relative Humidity Measurement Cluster Information**_

<figure><img src=".gitbook/assets/image (205).png" alt=""><figcaption></figcaption></figure>
