# VESTA-288

### IR2900

## **IR Thermostat IR2900**

![](<.gitbook/assets/1 (138).png>)

### Quickstart.

Please make sure the internal battery is fully charged.

To add this device to your network execute the following action:

1. In the home page, long press UP and DOWN synchronously for 3 sec to enter into Z-Wave interface, Product IDwill be displayed on the interface.
2. If Product ID is 0, press POWER to include the device into Z-Wave network, if the inclusion is successful, it willnot show 000 on the interface.

### Product Description

MCO Home IR2900 is a Z-Wave 800 series thermostat which is compliant to Z-Wave-to-IR bridge to control split air conditioner by receiving Z-Wave command and converting to Infrared command. IR2900 can control various brands and models of split air conditioner globally combination with the all-around built-in and cloud-stores IR database. With distinct display, you can intuitively read the room temperature with setting buttons to have a peace-in-mind smart home control experience.

### Prepare for Installation / Reset

Please read the user manual before installing the product.

In order to include (add) a Z-Wave device to a network it **must be in factory default state.** Please make sure to reset the device into factory default. You can do this by performing an Exclusion operation as described below in the manual. Every Z-Wave controller is able to perform this operation however it is recommended to use the primary controller of the previous network to make sure the very device is excluded properly from this network.

### Reset to factory default

This device also allows to be reset without any involvement of a Z-Wave controller. This procedure should only be used when the primary controller is inoperable.

Long press UP + POWER + DOWN synchronously for 3 sec, it displays “333” then press POWER for 4 times, the display will change from “333”->‘‘222″->”111″->”000″->”OFF‘, then factory restore setting succeeds.

### Installation

1. Separate the device into two parts: the front panel and the mounting plate.

![](<.gitbook/assets/2 (93).jpeg>)

2. Put SV adapter into the junction box, and insert the wire into the SV terminal by following the wiring diagram as below.

![](<.gitbook/assets/3 (95).jpeg>)

3. Secure the bottom part onto a junction box with screws, and then mount the front panel back.
4. Confirm the device is well mounted, powered on, and it is ready to operate.

### Match the infrared code of the air conditioner via Bluetooth

**1. Connect Bluetooth to IR2900**

When there is no infrared code library in the device

(the device has not downloaded the infrared code or the device has been restored to factory settings), the device automatically enters the Bluetooth pairing mode when powered by USB, The Bluetooth indicator flashes, and the ID number of Bluetooth is displayed on the

Home page, tap any key to exit the Bluetooth pairing mode. When the device is powered by battery, tap any key to exit the Bluetooth pairing mode, or it will automatically exit the Bluetooth pairing mode after 30 minutes.

When the infrared code needs to be modified, long-press **(Mode-Button + Fan-Button )** of the device synchronously for 3sec until the Bluetooth icon in the upper left corner flashes. The last 3 digits of Bluetooth ID will be displayed on the screen (e.g.

123\); Click “Next” of APP, APP will scan Bluetooth device, and “IR2900\_X123” will appear on the APP. Then click to complete the connection. The Bluetooth icon of IR2900 will light up after a successful connection. Here is App‘s download information:

{% embed url="https://play.google.com/store/apps/details?id=com.mcohome.codingctrl" %}

{% embed url="https://apps.apple.com/ios/app/ir-thermostat/id1582146430" %}

#### 2. Choose a brand of air conditioner

Enter air conditioner brand search, or manually find the corresponding brand, if it is not able to know the model then just select the brand of the air conditioner. Then click to enter the next step.

#### 3. Pair the infrared code of the air conditioner

Place the device in front of the air conditioner as close as possible (within 7 meters). If

the air conditioner can be correctly controlled by testing more than three keys on the APP interface, the pairing will be considered successful. If it is not working, click “Next” and repeat the test until a successful pair.

#### 4. Download infrared code

After successfully paired the infrared code, click “Yes, Use this” button, enter the download interface, wait for the progress bar to complete, click “Horne” to complete and exit.

#### 5. Local control test

If local operation mode, fan, setting temperature etc. can control the air conditioner normally, indicating that the infrared code pairing has been downloaded successfully, and can be used normally.

### Problems that you may encounter

1. Some keys are not being able to control the air conditioner. Maybe it is not being chosen the most appropriate infrared code, please follow the above steps on the APP to choose the most matching set of infrared code.
2. Tried everything but couldn‘t control the air conditioner, please take a picture of the model of the remote control and send it back to the manufacturer.

**Batch download infrared code library:**

1. If the device has downloaded the infrared code, then restore the device into factory setting first.
2. Power on multiple devices (IR2900) within S meters from the mobile phone (As the Bluetooth paring mode will automatically exit after 30 minutes if the device is powered by battery, we suggest that there is no more than 280 units of devices to be download the infrared code library in batch at a time when the devices are powered by battery, otherwise some devices may not be downloaded successfully. But there is no limit if the devices are powered by USB). All devices

(IR2900) enter the Bluetooth pairing mode, and the ID number of Bluetooth will be displayed on the screens.

1. Open the “IR thermostat” APP, click the Batch Download, check the infrared code to be downloaded, and then click Start Batch Download. The mobile APP will automatically connect the devices (IR2900) and download the infrared code one by one. Keep the devices powered on and do not manually operate the devices until the download is completed. After infrared codes are download completely, the device Bluetooth indicator will automatically turn off. If the device is powered by battery, it will enter the sleep mode automatically. If the device is powered by USB, it will automatically enter the Home page and after a period of time to transfer to sleep mode.

#### Inclusion/Exclusion

On factory default the device does not belong to any Z-Wave network. The device needs to be **added to an existing wireless network** to communicate with the devices of this network.

This process is called **Inclusion**.

Devices can also be removed from a network. This process is called **Exclusion**. Both processes are initiated by the primary controller of the Z-Wave network. This controller is turned into exclusion respective inclusion mode. Inclusion and Exclusion is then performed doing a special manual action right on the device.

#### Inclusion

1. In the home page, long press UP and DOWN synchronously for 3 sec to enter into Z-Wave interface, Product IDwill be displayed on the interface.
2. If Product ID is 0, press POWER to include the device into Z-Wave network, if the inclusion is successful, it willnot show 000 on the interface.

#### Exclusion

1. In the home page, long press UP and DOWN synchronously for 3 sec to enter into Z-Wave interface, Product IDwill be displayed on the interface.
2. If Product ID is not 0, press to exclude the device from Z-Wave network POWER, if the Exclusion is successful,it will show 000 on the interface.

#### Product Usage

![](<.gitbook/assets/4 (78).jpeg>)

### On/Off Setting

_In battery charge mode:_ remove the mounting plate at the back, switch the power button to ON, then the device will be powered on.

{% hint style="warning" %}
Note:

If the rechargeable battery has run out of the power, please charge the device by 5V USB Type-C

_In 5V USB ‘type-C charge mode:_ remove the mounting plate at the back, put the charging wire into 5V USB ‘type-C charging port, if switch the power button to ON, then the rechargeable battery will be charged in the meantime, if switch the power button to OFF, then only the device is charged and the rechargeable battery will not be charged.
{% endhint %}

#### Temperature Setting

1.lndoor temperature is displayed on the home page.

2\. Setting ternperature of current mode is displayed on the interface when pressing UP or DOWN , “SET‘‘ icon will be displayed on upper right side, the setting temperature value is adjustable.

#### Brightness Setting

1. In the home page, long press DOWN for 3 seconds, xx.x% (x indicates digit} will be displayed on the interface, it is the current value of LED brightness.
2. Press UP or DOWN to set the LED brightness, there are eight levels can be set from 100%-87%-75%-62%50%-37%-25%-12%. Click POWER to confirm and exit.

#### Battery Level Dsiplay

In the home page, long press FAN for 3 sec, “xx.x% (x indicates digit) “will be displayed on the interface, it is the percentage value of the remaining capacity of the battery, then press any key to exit.

#### Humidity Value Display

In the home page, long press TIMER for 3 sec, ‘‘xx.x% (x indicates digit) “will be displayed on the interface, it is the percentage value of current humidity, then press any key to exit.

#### Timer Function

Set timer to turn off the air conditioner regularly

1. In the home page, short press TIMER to enter the timer setting interface, the timer indicator icon will flash constantly.
2. Short press UP or DOWN to set the timer of turning off the air conditioner regularly (setting range is 0.5-24H), after the timer is set, short press POWER again to enable the timer shutdown function, then timer indicator icon will be always on.

#### Disable timer function

In the home page, short press TIMER twice to disable the timer function, the timer indicator icon will be disappeared.

#### Temperature Deadband Setting (when the device ls controlled by IR)

Long press MODE + TIMER + FAN synchronously for 3 sec, it displays current value of deadband, short press UP or DOWN to adjust the value then press POWER to confirm and exit.

Notice:

1. When deadband is 0 (default value), the control logic of the device is the same as the AC remote control, that means the setting temperature on the device is the same as the AC.
2. When deadband is set to 1-3, the device will follow thermostat‘s internal control logic to control AC‘s setting temperature, in order that the indoor temperature reaches the setting temperature of the device.

**Note:** In this mode, it is normal that the setting temperature of the device differs from that of air conditioner, if you want to keep the indoor temperature value close to the setting temperature of the device, set deadband to !)

#### Quick trouble shooting

Here are a few hints for network installation if things dont work as expected.

1. Make sure a device is in factory reset state before including. In doubt exclude before include.
2. If inclusion still fails, check if both devices use the same frequency.
3. Remove all dead devices from associations. Otherwise you will see severe delays.
4. Never use sleeping battery devices without a central controller.
5. Dont poll FLIRS devices.
6. Make sure to have enough mains powered device to benefit from the meshing

#### Association – one device controls an other device

Z-Wave devices control other Z-Wave devices. The relationship between one device controlling another device is called association. In order to control a different device, the controlling device needs to maintain a list of devices that will receive controlling commands. These lists are called association groups and they are always related to certain events (e.g. button pressed, sensor triggers, …). In case the event happens all devices stored in the respective association group will receive the same wireless command wireless command, typically a ‘Basic Set’ Command.

**Association Groups:**

Group NumberMaximum NodesDescription

<figure><img src=".gitbook/assets/image (305).png" alt=""><figcaption></figcaption></figure>

#### Configuration Parameters

Z-Wave products are supposed to work out of the box after inclusion, however certain configuration can adapt the function better to user needs or unlock further enhanced features.

**IMPORTANT:** Controllers may only allow configuring signed values. In order to set values in the range 128 … 255 the value sent in the application shall be the desired value minus 256. For example: To set a parameter to 200â€ˆit may be needed to set a value of 200 minus 256 = minus 56. In case of a two byte value the same logic applies: Values greater than 32768 may needed to be given as negative values too.

#### Parameter 2: Variation of reported temperature(C)

_Automatically report to gateway when variation of temperature greater than this value_

Size: 2 Byte, Default Value: 5



<table data-header-hidden><thead><tr><th width="174">SettingDescription</th><th></th></tr></thead><tbody><tr><td>0</td><td>not report to gateway when temperature varies</td></tr><tr><td>3 – 255</td><td>n *0.1 C</td></tr></tbody></table>

#### Parameter 3: Variation of reported humidity

_Automatically report to gateway when variation of humidity greater than this value_

Size: 1 Byte, Default Value: 6



<table data-header-hidden><thead><tr><th width="157">SettingDescription</th><th></th></tr></thead><tbody><tr><td>0</td><td>not report to gateway when humidity varies</td></tr><tr><td>1 – 99</td><td>Automatically report</td></tr></tbody></table>

#### Parameter 4: IR-Command heating mode

_Whether to send IR command when the device is in the heating mode_

Size: 1 Byte, Default Value: 1



<table data-header-hidden><thead><tr><th width="190">SettingDescription</th><th></th></tr></thead><tbody><tr><td>0</td><td>disabled</td></tr><tr><td>1</td><td>enabled</td></tr></tbody></table>

#### Parameter 5: IR-Command cooling mode

_Whether to send IR command when the device is in the cooling mode_

Size: 1 Byte, Default Value: 1

SettingDescription

| 0 | disabled |
| - | -------- |
| 1 | enabled  |

#### Parameter 6: Send repetition to Association group 2

_The number of times to verify and resend after sending a command to the device of association group 2_

Size: 1 Byte, Default Value: 3

SettingDescription

| 0     | not verify                                            |
| ----- | ----------------------------------------------------- |
| 1 – 9 | the number of times to resend if verification failure |
| 10    | always verify till success                            |

#### Parameter 7: Send repetition to Association group 3

_The number of times to verify and resend aller sending a command to the device of association group 3_

Size: 1 Byte, Default Value: 3

SettingDescription

| 0     | not verify                                            |
| ----- | ----------------------------------------------------- |
| 1 – 9 | the number of times to resend if verification failure |

#### Parameter 10: Lock key

_OFF–key works; ON –keys of up and down not works (this function is invalid for menu interface_

Size: 1 Byte, Default Value: 0

SettingDescription

| 0 | OFF |
| - | --- |
| 1 | ON  |

#### Parameter 11: Sound On/Off

Size: 1 Byte, Default Value: 1

SettingDescription

| 0 | OFF |
| - | --- |
| 1 | ON  |

#### Parameter 12: Temperature deadband setting

_The device will follow thermostat‘s internal control logic to control AC‘s setting temperature, in order that the indoor temperature ranches the setting temperature of the device. (In this case, it is normal that the setting temperature of the device differs from that of air conditioner)_

Size: 1 Byte, Default Value: 0

SettingDescription

| 0     | Local setting temperature is same as setting temperature of air conditioner. |
| ----- | ---------------------------------------------------------------------------- |
| 1 – 3 | Value of temperature deadband (n\*1°C),                                      |

#### Parameter 13: Temperature calibration

Size: 1 Byte, Default Value: 0

SettingDescription

| -100 – 100 | Value of temperature calibration (n\*0,1 °C) |
| ---------- | -------------------------------------------- |

#### Parameter 14: Screen On

Size: 1 Byte, Default Value: 1

SettingDescription

| 0      | always on                    |
| ------ | ---------------------------- |
| 1 – 60 | time of screen on in minutes |

#### Parameter 15: LED Brightness

Size: 1 Byte, Default Value: 8

SettingDescription

| 0     | OFF   |
| ----- | ----- |
| 1 – 8 | Level |

#### Parameter 16: Controlled by association group

_Temperature deadband when the device is controlled by association group._

Size: 1 Byte, Default Value: 10

SettingDescription

| 5 – 30 | Value of temperature deadband (n\* 0.1 C) |
| ------ | ----------------------------------------- |

#### Parameter 255: Factory reset

Size: 1 Byte, Default Value: 0

SettingDescription

| 85 | Factory restore |
| -- | --------------- |

#### Technical Data

| Dimensions                 | 105 x 105 x 15 mm    |
| -------------------------- | -------------------- |
| Weight                     | 176 gr               |
| Hardware Platform          | ZGM230S              |
| EAN                        | 4251295701820        |
| IP Class                   | IP IP20              |
| Voltage                    | 5V                   |
| Firmware Version           | 2.12                 |
| Z-Wave Version             | 07.10                |
| Z-Wave Product Id          | 0x015f.0x2900.0x7102 |
| Frequency                  | Europe – 868,4 Mhz   |
| Maximum transmission power | 5 mW                 |

#### Supported Command Classes

Basic

Sensor Multilevel

Thermostat Mode

Thermostat Operating State Thermostat Setpoint

Thermostat Fan Mode

Thermostat Fan State

Transport Service

Association Grp Info

Device Reset Locally

Zwaveplus Info

Supervision

Configuration

Manufacturer Specific

Powerlevel

Firmware Update Md

Battery

Association

Version

Multi Channel Association

Security 2

#### Explanation of Z-Wave specific terms

**Controller** — is a Z-Wave device with capabilities to manage the network.

Controllers are typically Gateways,Remote Controls or battery operated wall controllers.

**Slave** — is a Z-Wave device without capabilities to manage the network.

Slaves can be sensors, actuators and even remote controls.

**Primary Controller** — is the central organizer of the network. It must be

a controller. There can be only one primary controller in a Z-Wave network.

**Inclusion** — is the process of adding new Z-Wave devices into a network.

**Exclusion** — is the process of removing Z-Wave devices from the network. **Association** — is a control relationship between a controlling device and

a controlled device.

**Wakeup Notification** — is a special wireless message issued by a Z-Wave

device to announces that is able to communicate.

**Node Information Frame** — is a special wireless message issued by a Z-Wave device to announce its capabilities and functions.
