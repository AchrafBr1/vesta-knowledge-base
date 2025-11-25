# VESTA-155

DIO-52-B

## DI/DO Module

<figure><img src=".gitbook/assets/image (31) (1).png" alt=""><figcaption></figcaption></figure>

### Introduction

DIO-52-B is a DI/DO module that integrates wired devices into wireless networks to create automated responses and enhances security and convenience.&#x20;

The DI/DO module has built-in Digital Input and Digital Output terminals. It can be connected to a single sensor, switch, or device to receive on/off command from the Control Panel via DO, and return current status via DI to the Panel.

The DIO-52-B can also be connected to separate devices. With the Home Automation rule set in the Panel, the device connected to its DI point can be turned into the trigger of events, and its DO point into the responder of events. When “Input Follower Mode” is selected in the Control Panel, the DO terminal is interconnected to the DI terminal, and DO terminal device will be activated by DI terminal device trigger.

&#x20;                           **Top Cover**                                                                                     **Base**

![](<.gitbook/assets/0 (34).png>)

### **Parts Identification**

1.  **Test Button**

    Press once to send a learn code to the Control Panel.
2.  **LED indicator**

    The LED indicator lights up in the following conditions:

    1. Flashes 6 times: When Input terminal is triggered or when the Switch is transmitting a signal.
    2. Flashes 3 times: When Output Terminal is triggered.
    3. Flashes once every 4 seconds: Batteries are extremely low and need to be replaced.
3. **Battery Compartment**
4. **Power Terminal**
5. **Digital Input (DI) Terminal**
6.  **Digital Output (DO) Terminal**

    When connecting wire to each terminal, please use a mini Phillips screwdriver to screwn/unscrew the terminal. Avoid using a flat-head screwdriver, which may cause scrapes.
7. **Mounting Holes**
8.  **Strain Relief Clamps**

    The clamps are used for securing the wires, and providing strain relief to protect the wires from metal cutout.
9. **Wiring Holes**

### Features

#### _**Power Supply**_

* **AC Power and Battery**
  * DIO-52-B can be powered by a two-wired 5-12V DC adapter when connected to the Power Terminal, or it can be battery-powered by three CR123 Lithium batteries.
  * When Power Terminal and batteries are both in use, DIO-52-B will only power through the adaptor.
* **Low Battery Detection**
  * DIO-52-B features Low Battery Detection function. When the battery voltage is low, DIO-52-B will transmit Low Battery signal to notify the user. When changing batteries, after removing the old batteries, press the Test Button twice to fully discharge before inserting new batteries.

#### _**Supervision**_

DIO-52-B will transmit a supervision signal every 30 to 50 minutes regularly to report its condition.

#### _**Getting Started**_

1. nsert batteries or connect the two-wired 5-12V DC adapter to power on DIO-52-B.
2. Put the Control Panel into Learning Mode, refer to Control Panel manual for details.
3. Press the Test button once, the LED will flash 6 times.
4. If the Control Panel receives the signal, it will display the information accordingly, refer to Control Panel manual to complete the learning process.

{% hint style="info" %}
When learnt into the Control Panel, the DIO-52-B will be recognized as 2 separate devices (DI & DO), occupying 2 zones in the Panel.
{% endhint %}

#### _**Walk Test**_

* After the DIO-52-B is learnt-in, put the Control Panel into (**Walk Test**) mode, hold the DI/DO module in the desired location, and press the Test Button to transmit test signal to Control Panel. If the Control Panel is within the DIO-52-B signal range, the panel will display DI\&DO information accordingly.
* Proceed with mounting and installation once you are satisfied that the DI/DO module functions properly in the desired location.

#### _**Operation Mode**_

The DI/DO module can operate according to different mode selected on the Control Panel webpage, or SmartHomeSec Server . Please select the mode in **DO Device Edit** page.

| **Control Panel webpage**                                          | **SmartHomeSec**                                                                                                                                                                          |
| ------------------------------------------------------------------ | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| <img src=".gitbook/assets/1 (39).png" alt="" data-size="original"> | <img src=".gitbook/assets/image (4) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1).png" alt="" data-size="original"> |

*   **Appliance Control:**

    When DIO-52-B is used for appliance control, the input and output terminals are connected to the same device, e.g. a water valve.

    The output terminal is used to receive on/off signal from the Control Panel to turn/on off the connected device, while the input terminal is used to transmit the current status of the connected device to the Panel.

    When the “Appliance Control” mode is selected, you can remotely turn on/off the connected device from the Control Panel webpage or _**SmartHomeSe**_&#x63; server, but the output follow input setting in DO will be deactivated. You can program Home Automation rules, Scenes on Panel webpageor _**SmartHomeSe**_&#x63; Server to integrate the device connected to DIO-52-B with other devices in the Control Panel.

<figure><img src=".gitbook/assets/image (5) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1).png" alt=""><figcaption></figcaption></figure>

Example of DI/DO practice for Appliance Control:

![](<.gitbook/assets/4 (39).png>)

* **Separate Devices:**

In this mode, the input and output terminals of DIO-52-B are connected to separate devices. The input terminal is used to monitor the activation of the connected device, and transmit the trigger signal to the Control Panel. The output terminal is used to receive on/off signal from the Control Panel to turn/on off the connected device.

When DIO-52-B is working in this mode, the output follow input setting in DO is deactivated. Users can program Home Automation rules, Scenes on Panel webpage or _**SmartHomeSec**_ Server to turn the DI point into trigger of events, and the DO point into responder of events.

Example of DI/DO practice for Separate Devices:

DI input terminal is connected to a water leakage sensor, and DO output is connected to a water valve. By setting a Home Automation rule on SHS, the Panel will automatically turn off the water valve when the water leakage sensor is triggered.

| **DI settings**                                                         | **DO settings**                                                         |
| ----------------------------------------------------------------------- | ----------------------------------------------------------------------- |
| <img src=".gitbook/assets/image (147).png" alt="" data-size="original"> | <img src=".gitbook/assets/image (146).png" alt="" data-size="original"> |

| **Home Automation rule**                                                |
| ----------------------------------------------------------------------- |
| <img src=".gitbook/assets/image (149).png" alt="" data-size="original"> |

![](<.gitbook/assets/8 (21).png>)

* **Input Follower:**

In this mode, the input and output terminals of DIO-52-B are connected to separate devices. The output terminal device is interconnected with the input terminal device.

When input terminal device is triggered, the output terminal device will activate according to the Output Follow Input setting. Please refer to below section _**DI and DO Settings**_ for details.

After the “Input Follower” mode is selected, the Home Automation Rule & Apply Scene function on _**SmartHomeSec**_ Server will be deactivated. You will need to program the **Output Follow Input** setting on DO Device Edit page, so that the output terminal device will activate accordingly following trigger of the input terminal device.

Example of DI/DO practice for Input Follower:

After selecting the “Input Follower” mode on the DO device edit page, select “Latch” for the Output Follow Input setting. The output terminal device will be activated instantly when the input terminal device is triggered.

<figure><img src=".gitbook/assets/image (150).png" alt=""><figcaption></figcaption></figure>

![](<.gitbook/assets/10 (20).png>)

### _**DI and DO Settings**_

#### **Output Terminal (DO):**

Program the DO settings in **DO Device Edit** page on Panel webpage or _**SmartHomeSec**_ server.

| **Control Panel webpage**                                           | **SmartHomeSec**                                                                                                                                                                      |
| ------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| <img src=".gitbook/assets/11 (15).png" alt="" data-size="original"> | <img src=".gitbook/assets/image (4) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1).png" alt="" data-size="original"> |

_Swith on via APP_:

* **Do nothing** – The Do output device cannot be switched on via APP.
* **Don’t switch off** - The Do output device will not switch off after being switched on via APP.
* **Switch off after 1-240 sec/5-30 min** – After being switched on via APP for the selected time, the DO output device will switch off.

_Status for 0_: Enter the Status 0 description for the Output terminal.

_Status for 1_: Enter the Status 1 description for the Output terminal.

_Invert Input:_ Select to change the order of Status 0 and Status 1 for DI input. When “Yes” is selected, the order of Status 0 and Status 1 for DI input will be changed.

_Invert Output_: Select to change the order of Status 0 and Status 1 for DO output. When “Yes” is selected, the order of Status 0 and Status 1 for DO output will be changed.

_Output Follow Input:_ This function is available only when Operation Mode "3-Input Follower" is selected.

* **No** - When input terminal device is triggered, the output terminal device will Not be activated.
* **Latch** - The output terminal device will be activated instantly when the input terminal device is triggered.
* **On for 10-240 sec/5-30 min** - When input terminal device is triggered, the output terminal device will be activated for a set duration.

_Operation Mode:_ Select the Operation Mode for DIO-52-B. Please refer to previous section for details.

#### **Input Terminal (DI):**

Program the DI settings in **DI Device Edit** page on Panel webpage or SmartHomeSec server.

| **Control Panel webpage**                                           | **SmartHomeSec** **Server**                                                                                                                                                                                                                               |
| ------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| <img src=".gitbook/assets/13 (16).png" alt="" data-size="original"> | <img src=".gitbook/assets/image (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1).png" alt="" data-size="original"> |

_Status for 0_: Enter the Status 0 description for the Input terminal.

_Status for 1:_ Enter the Status 1 description for the Input terminal.

### Installation

DIO-52-B can be deployed on a flat surface or mounted on the wall. After you have finished the walk test, and you are satisfied that the device is able to communicate with the control panel in the chosen location, proceed with installation.

1. Disconnect the main power supply.
2. Loosen the bottom fixing screw and remove the top cover of DIO-52-B.
3. Use the holes on the base to mark mounting location on the wall.
4. Drill holes into marked location and insert wall plugs if required, screw the base onto the mounting location.
5. Replace the top cover and tighten the bottom fixing screw.
