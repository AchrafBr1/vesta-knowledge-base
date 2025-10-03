# VESTA-183

**TRV-1ZBS**

## &#x20;**Thermostatic Radiator Valve (Zigbee)**

<figure><img src=".gitbook/assets/image (395).png" alt=""><figcaption></figcaption></figure>

## **Introduction**

TRV-1ZBS is a ZigBee Radiator Valve designed to control the surrounding temperature by controlling the flow of hot water of radiators in the ZigBee network, i.e. indoor room temperatures.

The Radiator Valve utilizes ZigBee technology for wireless signal transmission. ZigBee is a wireless communication protocol that is reliable and has low power consumption and high transmission efficiency. Based on the IEEE802.15.4 standard, ZigBee allows a large amount of devices to be included in a network and coordinated for data exchange and signal transmission.

The Radiator Valve serves as an end device in the ZigBee network. It can be included in the ZigBee network to transmit signal upon activation, it can be controlled manually or remotely.

## **Parts Identification**

<figure><img src=".gitbook/assets/1 (1) (1) (1) (1) (1) (1) (1) (1) (1) (1).png" alt=""><figcaption></figcaption></figure>

1. **Valve Cap**
2. **LCD Display**

**A.** ![](<.gitbook/assets/2 (62).jpeg>) **ON** when device is already learned into Zig-Bee network.

**B.** <img src=".gitbook/assets/image (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1).png" alt="" data-size="line">**Low Battery Indicator.**

**C**. &#x20;

<img src=".gitbook/assets/4 (52).jpeg" alt="" data-size="line"> On: Device set to default temperature 17°C.

![](<.gitbook/assets/5 (39).jpeg>)   Flash: Valve closing.

![](<.gitbook/assets/6 (50).jpeg>)  On: Device set to default temperature 21°C.

![](<.gitbook/assets/7 (47).jpeg>)  Flash: Valve opening.

**D. Auto / Manual Mode.**

**E.** <img src=".gitbook/assets/image (2) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1).png" alt="" data-size="line">**Boost function.**

**F.** <img src=".gitbook/assets/image (3) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1).png" alt="" data-size="line"> **Open Window**.

**G. Temperature Indicator.**

**Others:   InS**: When power on device (also for learning period).

&#x20;                **AdA:** device motor working.

&#x20;                **F1/F3:** the valve is jammed, **F2:** no valve installed.

3. **Function Buttons**
   1. **Manual/Auto:** Enter Manual or Auto mode.
   2. **Boost/ ZigBee:** Speed up heating process/learn into ZigBee Network.
   3. &#x20;![](<.gitbook/assets/9 (28).jpeg>) Press this button to instantly switch day and night temperatures.                                     _**Default day**_ ![](<.gitbook/assets/10 (21).jpeg>) _temperature: 21_ °&#x43;_, **Default night**_ ![](<.gitbook/assets/11 (25).jpeg>) _temperature: 17_°C
4. **Temperature Sensor**
5.  **Control Knob**

    Adjust temperature manually.
6.  **Battery Compartment**

    The Radiator Valve is powered by two 1.5V AA alkaline batteries.

<figure><img src=".gitbook/assets/2 (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1).png" alt=""><figcaption></figcaption></figure>

## **Features**

### _**Power ON / Manual / Auto mode**_

#### **Power ON**:&#x20;

When the Radiator Valve powers on, it’s motor starts working with LCD displaying **InS**, device is ready for installation and start learning process. (see **Installation** for details)

#### **Manual Mode:**&#x20;

In the Manual mode, you can use the following functions:

* ![](<.gitbook/assets/13 (24).jpeg>) button: switch day/night temperatures instantly.
* **Boost button:** Speed up heating, learning device into Control Panel.
* **Control Knob**: Control temperature, set to ON (summer season mode) and OFF (winter season mode).

### **Auto Mode:** &#x20;

The Auto mode is only available when device is learned with a control panel. After learning with the Control Panel you can control and set the time schedule for the Radiator Valve automatically through the control panel (please refer to yo&#x75;_&#x72; control panel manual for details)._

In the Auto Mode, you can use the same functions as in Manual mode except the Control Knob Set to ON and OFF function.

### _**Anti-frosting**_

When the Radiator Valve detects a frosting hazard, it will automatically open the valve for hot water to flow in order to maintain the temperature and to prevent further frosting.

### _**Anti-calcification**_

The Radiator Valve will open and close the valve weekly to prevent calcification. During anti-calcification process the LCD will display a **CAL**.

The default value for anti-calcification process is 23:00p.m every Saturday.

### _**Boost Function**_

Press the Boost button to temporarily speed up heating process by further opening the valve. The boost function lasts 5 minutes (LCD displays: 300 seconds countdown). If you wish to cancel boost function, press the button again.

### _**Setpoint Offset**_

The device is usually installed at the corner of the room and near the heating pipe. As a result its temperature reading may deviate from room temperature at center of room. Use the Setpoint Offset function to compensate the deviation.

To calculate setpoint offset, simply subtract room temperature with device temperature.

For example: If device temperature is 20°C and room temperature is 18°C, then setpoint offset = 18 – 20 = -2°C.

After setpoint offset is applied, the device will operate according to adjusted temperature.

For example: If device temperature reading is 20°C, setpoint offset is -2°C, the device will operate using 18°C as actual reference.

To program Setpoint Offset:

1. Press and hold the ![](<.gitbook/assets/18 (11).jpeg>) button for 3 seconds to enter offset adjustment.
2. Rotate the Control Knob to desired offset temperature.
3. Press any key to finish and exit offset adjustment.

### _**Open Window**_

If Radiator Valve detects indoor temperature drops rapidly by opening the window, the Radiator Valve will activate Open Window function by partly closing the valve to reduce temperature setting for 15 minutes. The LCD will display <img src=".gitbook/assets/image (4) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1).png" alt="" data-size="line"> symbol, the device will check the temperature every minute. After 15 minutes, the Radiator Valve will return to the set temperature with valve opening again, Open Window Function closes.

### _**Control Knob**_

Rotate the Control Knob to adjust the temperature, rotate clockwise to reduce temperature and anti-clockwise to increase the temperature. The adjustable temperature range is 5°C to 30°C. If you rotate the Control Knob over 30°C to ON, after 1 minute, the Radiator Valve will open the valve completely, to preserve battery power. If you rotate the Control Knob lower than 5°C to OFF, after 1 minute, the Radiator Valve will close the valve completely. To disable ON/Off status please rotate the control knob or press button <img src=".gitbook/assets/image (5) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1).png" alt="" data-size="line">.

**ON:** When turned to ON, the valve is opened completely. This function is used to preserver battery life during summer, when heating is not required. Do not use this function in winter when heater is activated, otherwise the room temperature will rise uncontrolled.

**OFF:** When turn to OFF, the valve is closed completely. This function is used when heater is activated but heating is not required in a room with no occupants.

### _**Key Lock Function**_

Press and hold both the Auto/Manual button and the <img src=".gitbook/assets/image (6) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1).png" alt="" data-size="line"> button for 3 seconds to enable key lock function. If successful the LCD will display the <img src=".gitbook/assets/image (7) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1).png" alt="" data-size="line"> symbol. All keys and Control Knob actions will not respon&#x64;**.** If you wish to cancel key lock function, please press and hold both the Auto/Manual button and <img src=".gitbook/assets/image (8) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1).png" alt="" data-size="line"> button for 3 seconds likewise.

### _**Remote Control**_

After the Radiator Valve joins a ZigBee network, you can control the Radiator Valve via ZigBee network coordinator or gateway. Please refer to your ZigBee coordinator/gateway manual for more information.

The following functions are only available for setting via ZigBee coordinator and gateway:

#### **Schedule:**

You can only program Schedule configuration via ZigBee network coordinator/gateway.

Schedule Setting: Up to 5 schedules can be programmed for every weekday with Mode, Setpoint and Start time.

Schedule Control:

1. Normal - The Radiator Valve will execute programmed schedule setting accordingly.
2. No Schedule – The Radiator Valve will not execute any set schedule until it is set to Normal again.

## **Zig-Bee Network Setup and Installation**

### _**ZigBee Device Guideline**_

ZigBee is a wireless communication protocol that is reliable and has low power consumption and high transmission efficiency. Based on IEEE802.15.4 standard, ZigBee allows a large amount of devices to be included in a network and coordinated for data exchange and signal transmission.

Due to the fundamental structure of ZigBee network, ZigBee device will actively seek and join network after powering on. Since performing a task in connecting network may consume some power, it is required to follow the instructions to avoid draining battery of a ZigBee device.

* Ensure your ZigBee network router or coordinator is powered on before inserting battery into ZigBee device.
* Ensure the ZigBee network router or coordinator is powered on and within range while a ZigBee device is in use.
* Do not remove a ZigBee device from the ZigBee network router or coordinator without removing the battery from a ZigBee device.

### _**Joining the ZigBee Network and Installation**_

As a ZigBee device, the Radiator Valve needs to join a ZigBee network for user to control it remotely. Joining ZigBee network should be performed together with installation at the same time. Please follow the steps bellow to join the Radiator Valve into the ZigBee network.

1. Remove the Radiator Valve back cover and insert 2 AA Alkaline batteries to power up the Radiator Valve, LCD will display **InS** and  icon will flash to indicate Radiator Valve’s motor is working.
2. Press and hold the Boost button for 10 seconds, LCD will flash **888** to indicate release button to join ZigBee network. Please make sure the permit-join feature on the router or coordinator of your ZigBee network is enabled.
3. Wait for several seconds for the Radiator Valve to join ZigBee network. Please check the security system control panel or CIE (Control and Indicating Equipment) to confirm if joining and registration is successful.
4. When the motor stops working and <img src=".gitbook/assets/image (9) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1).png" alt="" data-size="line"> icon changes to steady on, attach the Valve cap to the pipe.

<figure><img src=".gitbook/assets/image (10) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1).png" alt="" width="404"><figcaption></figcaption></figure>

5. Rotating the Valve cap clockwise to tighten the Radiator Valve.

<figure><img src=".gitbook/assets/image (11) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1).png" alt=""><figcaption></figcaption></figure>

6. Press the Auto/Manual button, LCD displays **AdA** and valve motor starts working again, the ![](<.gitbook/assets/image (12) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1).png>)  icon will flash. The device motor is measuring the distance to adjust the current temperature.
7. When the valve motor stops, the system will enter Manual mode with LCD displaying the default set temperature 18.0°C, the installation is now complete.
8. After joining ZigBee network and completing installation, the ZigBee connection <img src=".gitbook/assets/image (13) (1) (1) (1) (1) (1) (1) (1) (1) (1).png" alt="" data-size="line"> icon  will appear on LCD display.
9. After joining the ZigBee network, if the Radiator Valve loses connection to current ZigBee network, the ZigBee connection icon will disappear after 10 minutes. Please check the ZigBee network condition and Radiator Valve signal range to correct the situation.

### _**Removing Device from ZigBee Network (Factory Reset)**_

To remove the Radiator Valve from current ZigBee network, the device must be put to Factory Reset to complete device removal. Factory Reset function will clear the Radiator Valve of its stored setting and information and prompt it to search for new ZigBee network.

**Before removing device, make sure the Radiator Valve is within current ZigBee network signal range**

1. Press and hold the function button for 10 seconds, then release the button to reset Radiator Valve.
2. Upon reset, the Radiator Valve will clear current ZigBee network setting and transmit signal to ZigBee coordinator to remove itself from current ZigBee network. It will then actively search for available ZigBee network again and join the network automatically.

## **Appendix(For developers only.)**

### _**Thermostat Cluster ID**_

<figure><img src=".gitbook/assets/image (14) (1) (1) (1) (1) (1) (1) (1) (1).png" alt=""><figcaption></figcaption></figure>

### _**Attribute of Basic Cluster Information**_

<figure><img src=".gitbook/assets/image (15) (1) (1) (1) (1) (1) (1) (1).png" alt=""><figcaption></figcaption></figure>

### Attribute of Power Configuration Cluster Information

<figure><img src=".gitbook/assets/image (16) (1) (1) (1) (1) (1) (1).png" alt=""><figcaption></figcaption></figure>

### _**Attribute of Identify Cluster Information**_

<figure><img src=".gitbook/assets/image (17) (1) (1) (1) (1) (1).png" alt=""><figcaption></figcaption></figure>

### _**Attribute of Thermostat Cluster Information**_

<figure><img src=".gitbook/assets/image (18) (1) (1) (1) (1) (1).png" alt=""><figcaption></figcaption></figure>
