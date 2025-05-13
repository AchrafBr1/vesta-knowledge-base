# VESTA-104

**TMST-15ZW Series**

## **Thermostat**

**Introduction**

TMST-15ZW is a battery powered thermostat. It is designed to be incorporated into household heating and cooling system for home environment control. The Thermostat can be operated manually using the LCD screen and buttons, or accessed remotely via Z-Wave coordinator. It features cooling and heating modes with temperature set point and automatic schedule for you to control your home environment easily.

## Parts Identification

1. **LCD Display**

The LCD displays the following information:

![](<.gitbook/assets/1 (32).png>)

A. Heat mode Icon: When displayed, the Thermostat is under Heat mode.

B. Cool mode Icon: When displayed, the Thermostat is under Cool mode.

C. Battery level Icon: Only displayed when battery level is at 25%, 50%, and 75%. The icon will disappear when battery level is below 15%.

D. Z-Wave network connectivity:

When displayed, it indicates that the thermostat is not yet learnt into any gateway/panel, or when the device loses connection to current Z-Wave network.

E. Mode: Mode Selection, Remote Mode, and Offset

F. Schedule: The Thermostat will execute programmed schedule setting.

G. Temperature Reading / Setpoint

**2. Down (-) Button.**

\- Press the button and the LCD screen will display current setpoint, mode, and set for 5 seconds. Within 5 seconds, press the Down (-) button to decrease setpoint.

\- Press and hold for 3 seconds to enter programming mode.

<figure><img src=".gitbook/assets/1 (2) (1) (1).png" alt=""><figcaption></figcaption></figure>

**3. Up (+) Button**

\- Press the button and the LCD screen will display current setpoint, mode, and set for 5 seconds. Within 5 seconds, press the UP (+) button to increase setpoint.

\- Press 3 times within 1.5 seconds to transmit learning code, and “Joi NET” will be displayed on the LCD screen.

![](<.gitbook/assets/2 (36).png>)

**4. Wall Mounting Hole**

<figure><img src=".gitbook/assets/2 (2) (1) (1).png" alt=""><figcaption></figcaption></figure>

**5. Battery Compartment**

Insert 2 AA Alkaline batteries.

<figure><img src=".gitbook/assets/3 (1) (1) (1) (1) (1).png" alt=""><figcaption></figcaption></figure>

**6. Relay Terminals (Remove Relay Cover to Access)**

230V 5A NO/COM/NC relay terminals.

Connect to home heating/cooling system.

<figure><img src=".gitbook/assets/4 (1) (1) (1) (1).png" alt=""><figcaption></figcaption></figure>

## **Features**

### _Battery and Low Battery Detection_

The Thermostat uses 2 AA Alkaline batteries as its power source. The Sensor will report its battery percentage to the Gateway/Control Panel respectively at 100% (0x64), 75% (0x4B), 50% (0x32) and 25% (0x19). When battery level is below 15%, the sensor will send 0xFF to the Gateway/Control Panel.

### _Relay Control_

The Thermostat control home heating/cooling system through relay control. Open and flip over the back cover, remove the internal cover on the relay to reveal the terminals for wiring. When wiring the Thermostat, wire the cable through the central opening on the back cover.

![](<.gitbook/assets/3 (15).jpeg>)

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

After the Thermostat joins a Z-Wave network, you can control the Thermostat via Z-Wave network coordinator or gateway. Please refer to your Z-Wave coordinator/gateway manual for more information.

The following functions are only available for setting via Z-Wave coordinator and gateway:

### **Schedule:**

You can only program Schedule configuration via Z-Wave network coordinator/gateway.

Schedule Setting: Up to 5 schedules can be programmed for every weekday with Mode, Setpoint and Start time.

Schedule Control:

Normal - The Thermostat will execute programmed schedule setting accordingly.

Hold – The Thermostat will bypass currently timed schedule and perform the next schedule when it begins

No Schedule – The Thermostat will not execute any set schedule until it is set to Normal again.

### _**Temperature Detection**_

* The Thermostat has built-in temperature sensors and will display the temperature reading on the LCD display.
* The Thermostat will transmit temperature signals regularly according to setting. The factory default interval is 5 minutes.
* You can also press the Z-Wave Network Button once to transmit a temperature signal manually.

### _**Z-Wave Sleep Mode**_

* The Thermostat will enter Z-Wave Sleep mode (to conserve power) after waking up for a short period of time. While in Z-wave sleep mode, Z-Wave gateways or control panels are unable to send commands to the Thermostat

## _**Programming Mode**_

**Step 1.** Press and hold Down (-) button for 3 seconds to enter programming mode.

**Step 2.** There are 3 functions available for programming, including Thermostat Functions, Controlling Remote Relay, and Setpoint

Offset. You can press either UP (+) or Down (-) button to switch modes.

**Step 3.** After finishing selection, wait for a few seconds for the Thermostat to enter selected mode.

### **Thermostat Functions (Heating and Cooling):**

In this mode, “Pro Mod” will be displayed on the LCD screen.

![](<.gitbook/assets/4 (33).png>)

Heating/Cooling modes are available for selection. Press UP (+) button to select Heating and Down (-) button to select Cooling.

Heating Cooling

![](<.gitbook/assets/5 (28).png>)

After finishing selection, wait for a few seconds for the Thermostat to quit setting mode automatically. The Thermostat will enter the mode last selected.

### **Controlling Remote Relay:**

In this mode, “Pro RM” will be displayed on the LCD screen.

The Remote Mode allows you to control remote relay via the Control Panel when function enabled. The Thermostat will not control the local relay in Remote Mode.

![](<.gitbook/assets/6 (21).png>)

* If remote mode is disabled, “dS RM” will be displayed on the LCD screen.
* If remote mode is enabled, “En RM” will be displayed on the LCD screen.

![](<.gitbook/assets/7 (18).png>)

### **Setpoint Offset:**

In this mode, “Pro OFS” will be displayed on the LCD screen. Setpoint Offset function allows you to compensate the deviation. To calculate setpoint offset, simply subtract room temperature with device temperature. When under local mode, press and hold Down (-) button for 3 seconds to enter programming mode. After finishing selection, wait for a few seconds for the Thermostat to enter mode selection.

![](<.gitbook/assets/8 (18).png>)

For example: If device temperature is 20°C and room temperature is 18°C, then setpoint offset = 18 – 20 = -2°C.

After setpoint offset is applied, the device will operate according to adjusted temperature.

For example: If device temperature reading is 20°C, setpoint offset is -2°C, the device will operate using 18°C as actual reference.

## _**Adding Device (Inclusion)**_

This product can be included and operated in any Z-Wave network with other Z-Wave certified devices from other manufactures and/or other applications. All non-battery operated nodes within the network will act as repeaters regardless of vendor to increase reliability of the network.

* Load two AA Alkaline batteries into the battery compartment.
* Put the Z-Wave control panel into Inclusion mode (please refer to the Z-Wave control panel manual).
* Within 1.5 seconds, press the Up (+) Button 3 times to transmit learning code, and “Joi NET” will be displayed on the LCD screen. If the Thermostat successfully joins a network, the Z-Wave connection icon will disappear on LCD display.
* Refer to the operation manual of the Z-Wave gateway or control panel to complete the adding process.
* If the device has already been added (included) into another Z-Wave Gateway/Control Panel, or if the device is unable to be added into the current Z-Wave Gateway/Control Panel, try removing it first (see Removing Device).

### _**Removing Device (Exclusion)**_

The device must be removed from existing Z-Wave network before being added into another.

### **Exclusion Mode:**

* Put the Z-Wave gateway or control panel into Exclusion mode (please refer to the Z-Wave or control panel manual).
* Within 1.5 seconds, press the Up (+) Button 3 times and the device will be removed from the Z-Wave network. If the Thermostat is successfully removed from network, the Z-Wave connection icon will appear on LCD display.

### **Factory Reset**

Factory resetting the device will restore it to factory default settings (i.e. not included into any Z-Wave network). Please only use this procedure if the Z-Wave gateway or control panel is lost or otherwise inoperable.

* Press and hold the Up (+) Button of the device for 10 seconds to factory reset.

## _**Installation**_

The Thermostat is designed to be wall mounted using the mounting holes on the back cover.

1. Before mounting, make sure to complete relay wiring through the opening on the back cover first.
2. Use the mounting holes on the back cover as template to mark mounting location on the wall.
3. Drill holes on the wall and insert wall plug if required, screw the back cover onto the mounting location.
4. Place the Thermostat main body on the back cover, installation is complete.

## **Z-Wave Information**

**Device Type:** Thermostat

**Role Type:** Reporting Sleeping Slave (RSS)

**Command Class Support/Control**

**Mandatory CC Support:**&#x20;

Association CC, v2

Association Group Information CC

Battery CC

Device Reset Locally CC

Manufacturer Specific CC, v2

Version CC, v2

Power Level CC

Z-Wave Plus Info CC, v2

&#x20;Multi-Channel Association CC, v2

&#x20;Wakeup CC

&#x20;Supervision CC

Thermostat Mode CC, v3

&#x20;Thermostat Setpoint CC, v3

Thermostat Operating State CC

Sensor Multilevel CC

Firmware Update CC, v2 (OTA version only)

### _**Z-Wave Groups (Association Command Class Version 2)**_

Group 1 for “LifeLine”:

Battery CC (COMMAND\_CLASS\_BASIC)

Device Reset Locally CC

Thermostat Mode CC, V3

Thermostat Setpoint CC, V3

Thermostat Operating State CC

Sensor Multilevel CC

Group 2 for Thermostat Operating State:

Thermostat Operating State CC
