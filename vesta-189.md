# VESTA-189

**TMST-15-ZBS**&#x20;

## **Thermostat**

## **Introduction**

TMST-15-ZBS is a battery powered ZigBee Thermostat. It is designed to be incorporated into household heating and cooling system for home environment control. The Thermostat can be operated manually using the LCD screen and buttons, or accessed remotely via ZigBee network. It features Cooling and Heating modes with temperature set point and automatic schedule for you to control your home environment easily.

The Thermostat utilizes ZigBee technology for wireless signal transmission. ZigBee is a wireless communication protocol that is reliable and has low power consumption and high transmission efficiency. Based on the IEEE802.15.4 standard, ZigBee allows a large amount of devices to be included in a network and coordinated for data exchange and signal transmission

The Thermostat serves as an end device in the ZigBee network. It can be included in the ZigBee network to transmit signal upon activation, but cannot permit any other ZigBee device to join the net.

**TMST-15-ZBS series has the following models:**

TMST-15-ZBS

TMST-15-ZBS-OTA

## **Parts Identification**

**1. LCD Display**

The LCD displays the following information:

![](<.gitbook/assets/1 (79).jpeg>)

A. Heat mode Icon: When displayed, the Thermostat is under Heat mode.

B. Cool mode Icon: When displayed, the Thermostat is under Cool mode.

C. Low battery Icon: When displayed the Thermostat battery voltage is low.

D. ZigBee network connectivity:

The icon is displayed when Thermostat is not yet learnt into any gateway/panel, or when the device loses connection to current ZigBee network.

E. Mode: Mode Selection, Remote Mode, and Offset

F. Schedule: The Thermostat will execute programmed schedule setting.

G. Temperature Reading / Setpoint

**2. Down (-) Button:**  Press to decrease setpoint

&#x20;    Press and hold for 3 seconds to enter programming mode.

<figure><img src=".gitbook/assets/1 (2) (1) (1).png" alt=""><figcaption></figcaption></figure>

**3. Up (+) Button**  Press to increase setpoint.

&#x20;   Press and hold for 10 seconds to enter learning mode, and “Joi NET” will be displayed on the LCD screen.

![](<.gitbook/assets/2 (67).jpeg>)

4. **Wall Mounting Hole**
5.

    <figure><img src=".gitbook/assets/2 (2) (1) (1).png" alt=""><figcaption></figcaption></figure>
6. **Battery Compartment**

Insert 2 AA Alkaline batteries.

<figure><img src=".gitbook/assets/3 (1) (1) (1) (1) (1) (1) (1) (1) (1).png" alt=""><figcaption></figcaption></figure>

**6. Relay Terminals (Remove Relay Cover to Access)**

230V 5A NO/COM/NC relay terminals.

Connect to home heating/cooling system.

## **Features**

### _**Battery and Low Battery Detection**_

The Thermostat uses 2 AA Alkaline batteries as its power source. The Thermostat features Low Battery Detection function. When the battery voltage is low, the Thermostat will transmit Low Battery signal to the coordinator in ZigBee network.

### _**Relay Control**_

The Thermostat control home heating/cooling system through relay control. Open and flip over the back cover, remove the internal cover on the relay to reveal the terminals for wiring. When wiring the Thermostat, wire the cable through the central opening on the back cover.

![](<.gitbook/assets/5 (77).png>)

### _**Mode Control**_

The Thermostat has two operation modes: Local mode and Scheduled mode.

* **Local Mode:**

Local mode allows adjustment of Thermostat Heat/Cool function and setpoints using thermostat buttons.

* **Scheduled Mode:**

Scheduled mode allows Thermostat mode and setpoint control via Gateway after learning is completed.

To change the operation mode, please refer to “_Programming Mode_” section for more details.

* _**Heating/Cooling and Setpoint Control**_

The Thermostat Heating/Cooling and setpoint can only be adjusted locally when Thermostat is set to Local mode.

When under local mode, press the **UP** (**+**) or **Down (-)** button to adjust setpoiont.

When under scheduled mode, use the Gateway/Control Panel to adjust the setpoint remotely.

Heat setpoint range: 9°C \~ 30°C.

Cool setpoint range: 11°C \~ 32°C

### _**Remote Control**_

After the Thermostat joins a ZigBee network, you can control the Thermostat via ZigBee network coordinator or gateway. Please refer to your ZigBee coordinator/gateway manual for more information.

The following functions are only available for setting via ZigBee coordinator and gateway:

### **Schedule:**

You can only program Schedule configuration via ZigBee network coordinator/gateway.

Schedule Setting: Up to 5 schedules can be programmed for every weekday with Mode, Setpoint and Start time. Schedule Control:

Normal - The Thermostat will execute programmed schedule setting accordingly.

Hold – The Thermostat will bypass currently timed schedule and perform the next schedule when it begins No Schedule – The Thermostat will not execute any set schedule until it is set to Normal again.

### _**Temperature Detection**_

* The Thermostat has built-in temperature sensors and will display the temperature reading on the LCD display.
* The Thermostat will transmit temperature signals regularly according to setting. The factory default interval is 10 minutes.
* When the temperature changes by +/- 2°C, the Thermostat will also transmit a signal.
* You can also press the ZigBee Network Button once to transmit a temperature signal manually.
* _**Supervision**_

The Thermostat will transmit a supervision signal every 10 minutes along with the temperature, current mode and set point information to report its condition regularly.

## _**Programming Mode**_

**Step 1.** Press and hold Down (-) button for 3 seconds to enter programming mode.

**Step 2.** There are 3 functions available for programming, including Thermostat Functions, Controlling Remote Relay, and Setpoint Offset. You can press either UP (+) or Down (-) button to switch modes.

**Step 3.** After finishing selection, wait for a few seconds for the Thermostat to enter selected mode.

**Thermostat Functions (Heating and Cooling):**

In this mode, “Pro Mod” will be displayed on the LCD screen.

![](<.gitbook/assets/17 (17).jpeg>)

Heating/Cooling modes are available for selection. Press UP (+) button to select Heating and Down (-) button to select Cooling.

Heating Cooling

![](<.gitbook/assets/18 (12).jpeg>)

After finishing selection, wait for a few seconds for the Thermostat to quit setting mode automatically. The Thermostat will enter the mode last selected.

**Controlling Remote Relay:**

In this mode, “Pro RM” will be displayed on the LCD screen. The Remote Mode allows you to control remote relay via the Control Panel when function enabled. The Thermostat will not control the local relay in Remote Mode.

![](<.gitbook/assets/19 (29).png>)

* If remote mode is disabled, “dS RM” will be displayed on the LCD screen.
* If remote mode is enabled, “En RM” will be displayed on the LCD screen.

![](<.gitbook/assets/20 (22).png>)

**Setpoint Offset:**

In this mode, “Pro OFS” will be displayed on the LCD screen. Setpoint Offset function allows you to compensate the deviation. To calculate setpoint offset, simply subtract room temperature with device temperature. When under local mode, press and hold Down (-) button for 3 seconds to enter programming mode. After finishing selection, wait for a few seconds for the Thermostat to enter mode selection.

For example: If device temperature is 20°C and room temperature is 18°C, then setpoint offset = 18 – 20 = -2°C.

After setpoint offset is applied, the device will operate according to adjusted temperature.

For example: If device temperature reading is 20°C, setpoint offset is -2°C, the device will operate using 18°C as actual reference.

## **ZigBee Network Setup**

* _**ZigBee Device Guideline**_

ZigBee is a wireless communication protocol that is reliable and has low power consumption and high transmission efficiency. Based on IEEE802.15.4 standard, ZigBee allows a large amount of devices to be included in a network and coordinated for data exchange and signal transmission.

Due to the fundamental structure of ZigBee network, ZigBee device will actively seek and join network after powering on. Since performing a task in connecting network may consume some power, it is required to follow the instructions to avoid draining battery of a ZigBee device

* Ensure your ZigBee network router or coordinator is powered on before inserting battery into the ZigBee device.
* Ensure the ZigBee network router or coordinator is powered on and within range while a ZigBee device is in use.
* Do not remove a ZigBee device from the ZigBee network router or coordinator without removing the battery from a ZigBee device.
* _**Joining the ZigBee Network**_

As a ZigBee device, the Thermostat needs to join a ZigBee network to for user to control it remotely. Please follow the steps bellow to join the Thermostat into the ZigBee network.

1. Remove the Thermostat back cover and insert 2 AA Alkaline batteries to power up the Thermostat.
2. Press and hold the ZigBee network button for 10 seconds then release to join ZigBee network. Please make sure the permit-join feature on the router or coordinator of your ZigBee network is enabled.
3. Wait for several seconds for the Thermostat to join ZigBee network. If the Thermostat successfully joins a network, the ZigBee connection icon will disappear on LCD display.
4. After joining the ZigBee network, the Thermostat will be registered in the security system in the network automatically. Please check the security system control panel or CIE (Control and Indicating Equipment) to confirm if joining and registration is successful.
5. After joining the ZigBee network, if the Thermostat loses connection to current ZigBee network, the ZigBee connection icon will appear after 10 minutes. Please check the ZigBee network condition and Thermostat signal range to correct the situation.

* _**Removing Device from ZigBee Network (Factory Reset)**_

To remove the Thermostat from current ZigBee network or set to factory default values, please follow the steps below:

**Remove the Thermostat from current ZigBee network:**

1. Before removing device, make sure the Thermostat is within current ZigBee network signal range.
2. Press and hold the UP (+) button for 10 seconds, and then release the button.
3. The Thermostat will be removed from current ZigBee network. It will actively search for available ZigBee network again and join the network automatically.

**Set the Thermostat to factory default values:**

1. Press the UP (+) and Down (-) buttons at the same time, and then power on the device.
2. Release the buttons. The Thermostat will clear its stored setting and return to factory default values.

## _**OTA Firmware Upgrade**_

The Thermostat supports OTA firmware upgrade feature via ZigBee network, which can be initiated from the ZigBee network coordinator.

Follow steps below to perform OTA firmware upgrade.

**Step 1.** You have to access your ZigBee Coordinator to perform the firmware upgrade on the air.

**Step 2.** On the configuration webpage, select the device that you wish to upgrade and select the new ZigBee firmware provided. Please refer to ZigBee Coordinator User Manual for detail.

**Step 3.**&#x50;ress“OK”to start upgrading process, and the LED will keep flashing. During the OTA process, please do not perform any other actions, or power down the panel.

**Step 4.**&#x54;he length of an upgrade will take approximately 20 to 30 minutes. Please note that the duration may vary based on file size or distance between your accessory and coordinator.

**Step 5**.Wait for firmware to complete update. When the progress reaches 100%, the Device will reset automatically. You can also refresh the webpage again to ensure if the Device firmware is successfully updated with the newest version displayed.

## **Installation**

The Thermostat is designed to be wall mounted using the mounting holes on the back cover.

1. Before mounting, make sure to complete relay wiring through the opening on the back cover first.
2. Use the mounting holes on the back cover as template to mark mounting location on the wall.
3. Drill holes on the wall and insert wall plug if required, screw the back cover onto the mounting location.
4. Place the Thermostat main body on the back cover, installation is complete.

<mark style="color:red;">**Appendix(For developers only.)**</mark>

* _**Thermostat Cluster ID**_

**Device ID: ZCL\_HA\_DEVICEID\_THERMOSTAT 0x0301**
