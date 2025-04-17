# VESTA-186

**PSS-29ZBS(R) / PSM-29ZBS(R)**&#x20;

## **Power Switch Series**

## **Introduction**

The Power Switch series include the following models:

**PSS-29ZBS:** ZigBee Power Switch

**PSS-29ZBSR:** ZigBee Power Switch with Router function

**PSM-29ZBS:** ZigBee Power Switch with Meter

**PSM-29ZBSR:** ZigBee Power Switch with Meter and Router function

The Power Switches are capable of receiving wireless signals from the coordinator in the ZigBee network to toggle On/Off of appliances that are attached to it.

The Power Switch utilizes ZigBee technology for wireless signal transmission. ZigBee is a wireless communication protocol that is reliable, has low power consumption and has high transmission efficiency. Based on the IEEE802.15.4 standard, ZigBee allows a large amount of devices to be included in a network and coordinated for data exchange and signal transmission.

Models with Meter functions (PSM-29ZBS / PSM-29ZBSR) have the extra feature of keeping tracks of energy consumption with built-in power meter and transmit the data to coordinator regularly.

Models with router function (PSS-29ZBSR / PSM-29ZBSR) also serve as a router in the ZigBee network. After being included in the ZigBee network, it allows other ZigBee device to join the network through the Power Switch.

| **Model No.**  | **Meter** | **ZigBee Router** |
| -------------- | --------- | ----------------- |
|                |           |                   |
| **PSS-29ZBS**  | **No**    | **No**            |
|                |           |                   |
| **PSS-29ZBSR** | **No**    | **Yes**           |
|                |           |                   |
| **PSM-29ZBS**  | **Yes**   | **No**            |
|                |           |                   |
| **PSM-29ZBSR** | **Yes**   | **Yes**           |
|                |           |                   |

## **Parts Identification**

1. **Function Button aka LED indicator**

The Function Button also doubles as the LED Indicator. The function button is used to control the Power Switch. The LED indicator is used to indicate Power Switch status.

**LED Indication:**

The LED indicator lights up in the following conditions:

* On: The Power Switch is turned on.
* Off: The Power Switch is turned off.
* Flashes twice: The Power Switch has successfully joined a ZigBee network.
* Flashes 5 times: The Power Switch has successfully bound with a controller
* Flashes every 20 minutes: The Power Switch has lost connection to its current ZigBee network (**PSS-29ZBS and PSM-29ZBS only**)

**Function Button Usage:**

* Press the button to toggle on/off the Power Switch
* Press and hold the button for 10 seconds then release to reset the Power Switch.
* Press and hold the button for 3 seconds then release to bind with a controller.

&#x20;                                                                    _**Type F**_                                    _**Type B**_

<figure><img src=".gitbook/assets/image (206).png" alt=""><figcaption></figcaption></figure>

&#x20;                                                                      _**Type L**_                                   _**Type J**_

<figure><img src=".gitbook/assets/image (208).png" alt=""><figcaption></figcaption></figure>

## **ZigBee Network Setup**

### _**ZigBee Device Guideline**_

ZigBee is a wireless communication protocol that is reliable, has low power consumption and has high transmission efficiency. Based on the IEEE802.15.4 standard, ZigBee allows a large amount of devices to be included in a network and are coordinated for data exchange and signal transmission.

### _**Joining the ZigBee Network**_

As a ZigBee device, the Power Switch needs to join a ZigBee network to receive commands and transmit energy consumption information. Follow the steps bellow to join the Power Switch into a ZigBee network.

1. Plug in the Power Switch into a power outlet.
2. Press and hold the function button for 10 seconds as the Power Switch resets and starts searching for existing ZigBee network. Please make sure the permit-to-join feature on the router or coordinator of your ZigBee network is enabled.
3. If the Power Switch successfully joins a ZigBee network, the LED Indicator will flash twice to confirm.
4. After joining the ZigBee network, the Power Switch will be registered in the network automatically. Please check the ZigBee network coordinator, system control panel or CIE (Control and Indicating Equipment) to confirm if joining and registration is successful.
5. If registration and joining to the network is unsuccessful, please check your ZigBee network coordinator, system control panel or CIE setting to ensure the permit-to-join function is available, and then use the Factory Reset function below to join the ZigBee network.

### _**Binding with Controller**_

After joining the ZigBee network, the Power Switch can bind itself with a controller device which can be used to turn on/off the Power Switch. To bind the Power Switch and the device:

1. Press and hold the Function Button for 3 seconds, then release the button. The Power Switch will send binding request to the coordinator.
2. Refer to your controller manual to send binding request for the device within 16 seconds.
3. If binding is successful, the Power Switch LED indicator will flash 5 times to confirm. You can now use the controller to adjust power output level for the Power Switch.
4. If binding is unsuccessful, please retry the binding process.

### _**Removing Device from ZigBee Network (Factory Reset)**_

To remove the Power Switch from current ZigBee network, the Power Switch must be put to Factory Reset to complete device removal. Factory Reset function will clear the Power Switch of its stored setting and information and prompt the Power Switch to search for new ZigBee network.

**Before removing device, make sure the Power Switch is within current ZigBee network signal range**

1. Press and hold the function button for 10 seconds, then release the button to reset Power Switch.
2. Upon reset, the Power Switch will clear current ZigBee network setting and transmit signal to ZigBee coordinator to remove itself from current ZigBee network. It will then actively search for available ZigBee network again and join the network automatically.

### _**ZigBee Router Device Capacity (PSS-29ZBSR / PSM-29ZBSR Only)**_

The Power Switch models with Router function allow other ZigBee devices to join the ZigBee Network through the Router. The Power Switch Router has maximum capacity of 40 devices, including 10 routers; the Power Switch Meter Router has maximum capacity of 10 devices including 5 routers.

<figure><img src=".gitbook/assets/image (209).png" alt=""><figcaption></figcaption></figure>

## **Operation**

### _**Installation**_

Plug the Power Switch into a power outlet, then Plug the appliance into the socket of the Power Switch. The appliance must be in ON status.

{% hint style="danger" %}
_**IMPORTANT NOTE**_**:** The Power Switch does not have a backup battery and will be powered down when AC power fails. **DO NOT** use the Power Switch as router for your security sensor or alarm control devices such as Door Contact, PIR Sensor…etc., otherwise the sensors will lose connection to ZigBee network if the Power Switch is disconnected from AC power. Plan the installation locations of these security sensors without using the Power Switch and only use a router with backup battery for them. The router function of the Power Switch should **ONLY** be used to provide signal range extension for other Power Switches/Dimmer
{% endhint %}

### _Appliance Control_&#x20;

* After the Power Switch has successfully joined a ZigBee network, the coordinator can remotely turn on/off the Power Switch to control the appliance&#x20;
* You can also press the button on the Power Switch to toggle its on/off status&#x20;
* If you have bound a controller with the Power Switch, you can also use the controller to turn on/off the Power Switch.&#x20;
* If the Power Switch is removed from power outlet, after re-plugging the Power Switch, its previous on/off status will be restored within 1 minute

### _**Energy Consumption Monitor (PSM-29ZBS / PSM-29ZBSR Only)**_

* Power Switch models with built-in meter will transmit a signal with its power consumption data every 10 minutes to the ZigBee network coordinator.
* Whenever the Power Switch energy output changes by +/- 2W, it will automatically transmit a signal with power consumption data to the ZigBee network coordinator for update.
* The Power Switch transmits a signal with power data to coordinator whenever accumulated power usage increases by 0.1kW/hr.
* The Meter has an accuracy of +/- 5%.
* To clear the Power Switch of its accumulated power consumption data, follow steps below:
  1. Unplug the Power Switch from power outlet.
  2. Press and hold the function button and plug in the Power Switch again when holding down the button.
  3. Keep holding the button and release after 3 seconds. The accumulated power consumption data will be cleared.

### _**Maximum Operation Load**_

* For 110V: the maximum operation load is 1760W and 16A.
* For 230V: the maximum operation load is 3680W and 16A.
* If the Power Switch is overheating, It will cut off power automatically as a safety measure. The Power Switch must be unplugged and re-plugged after cut off to resume normal operation.

