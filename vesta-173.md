# VESTA-173

**RSB-1ZBS**

## **RGBW Smart Bulb (Zigbee)**

<figure><img src=".gitbook/assets/image (385).png" alt=""><figcaption></figcaption></figure>

## **Introduction**

![](<.gitbook/assets/0 (73).jpeg>)

The RSB-1ZBS is a ZigBee Smart LED Color Light Bulb. It features both multicolor adjustment and light level control. When joined into a ZigBee network, the user will be able to control Light Bulb remotely from the ZigBee network coordinator.

The Light Bulb utilizes ZigBee technology for wireless signal transmission. ZigBee is a wireless communication protocol that is reliable and has low power consumption and high transmission efficiency. Based on the IEEE802.15.4 standard, ZigBee allows a large amount of devices to be included in a network and coordinated for data exchange and signal transmission

The Light Bulb also serves as a route in the ZigBee network. After being included in the ZigBee network, it allows other ZigBee devices to join the network through the Light Bulb.

## **ZigBee Network Setup**

### _**ZigBee Device Guideline**_

ZigBee is a wireless communication protocol that is reliable, has low power consumption and has high transmission efficiency. Based on the IEEE802.15.4 standard, ZigBee allows a large amount of devices to be included in a network and coordinated for data exchange and signal transmission.

Due to the fundamental structure of ZigBee network, ZigBee device will actively seek and join network after powering on.

* Ensure your ZigBee network router or coordinator is powered on before powering on the ZigBee device.
* Ensure your ZigBee network router or coordinator is powered on and within range while a ZigBee device is in use.
* Do not remove a ZigBee device from the ZigBee network router or coordinator without powering down the ZigBee device.

### _**Joining the ZigBee Network**_

As a ZigBee device, the Light Bulb needs to join a ZigBee network to send and receive command signals. Please follow the steps below to add the Light Bulb into the ZigBee network.

1. &#x20;Scroll the Light Bulb into the lamp socket. Do not supply power yet.
2. Enable the permit-join feature on the router or coordinator of your ZigBee network.
3. Switch ON Light Bulb for 3\~5 seconds. (No more than 5 seconds), then switch OFF.
4. Repeat Step 3 for three (3) times for a total of four (4) ON/OFF cycles.
5. Switch ON Light Bulb for the 5th time, the device will reset and start searching for new ZigBee network.
6. After joining the ZigBee network, the Light Bulb will be registered in the security system in the network automatically. Please check the ZigBee network coordinator, system control panel, or CIE (Control and Indicating Equipment) to confirm if joining and registration was successful.

![](<.gitbook/assets/4 (48).jpeg>)

### _**Removing Device from ZigBee Network (Factory Reset)**_

To remove the Light Bulb from current ZigBee network, the device must be placed on Factory Reset to complete device removal. Factory Reset function will clear the Light Bulb of its stored setting and information and prompt the Light Bulb to search for new ZigBee network.

**Before removing device, make sure the Light Bulb is within current ZigBee network signal range**

1. Delete the Light Bulb from current control panel / CIE.
2. Power off the Light Bulb.
3. Switch ON Light Bulb for 3\~5 seconds. (No more than 5 seconds), then switch OFF.
4. Repeat Step 3 for 3 times for a total of 4 ON/OFF cycles
5. Switch ON Light Bulb for the 5th time, the device will reset and start searching for new ZigBee network.
6. Upon reset, the Light Bulb will clear current ZigBee network setting and transmit signal to ZigBee coordinator to remove itself from current ZigBee network. It will then actively search for available ZigBee network again and join the network automatically.

![](<.gitbook/assets/6 (48).jpeg>)

### _**ZigBee Router Device Capacity**_

The Light Bulb with Router function allows other ZigBee devices to join the ZigBee Network through the Router. The Light Bulb has a maximum capacity of 7 devices, including 4 routers.

## **Features**

### _**Color and Saturation Adjustment**_

The Light Bulb’s color and saturation may be adjusted from the ZigBee Coordinators remotely by sending commands.

### _**Light Level Adjustment**_

The Light Bulb has dimmable lighting, the light percentage maybe adjusted from the ZigBee Coordinators remotely by sending commands.

### _**Supervision**_

The Light Bulb will transmit a supervision signal to report its condition regularly according to user setting. The factory default interval is 10 minutes.

## **Appendix (For developers only)**

### _**Light Bulb Cluster ID**_

<figure><img src=".gitbook/assets/image (152).png" alt=""><figcaption></figcaption></figure>

### _**Attribute of Basic Cluster Information**_

<figure><img src=".gitbook/assets/image (153).png" alt=""><figcaption></figcaption></figure>

### _**Attribute of Identify Cluster Information**_

<figure><img src=".gitbook/assets/image (154).png" alt=""><figcaption></figcaption></figure>

### _**Attribute of Group Cluster Information**_

<figure><img src=".gitbook/assets/image (155).png" alt=""><figcaption></figcaption></figure>

### _**Attribute of Scenes Cluster Information**_

<figure><img src=".gitbook/assets/image (156).png" alt=""><figcaption></figcaption></figure>

### _**Attribute of On/Off Cluster Information**_

<figure><img src=".gitbook/assets/image (157).png" alt=""><figcaption></figcaption></figure>

### _**Attribute of Level Control Cluster Information**_

<figure><img src=".gitbook/assets/image (158).png" alt=""><figcaption></figcaption></figure>

### _**Attribute of Color Control Cluster Information**_

<figure><img src=".gitbook/assets/image (159).png" alt=""><figcaption></figcaption></figure>
