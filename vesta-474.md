# VESTA-474

SFB-3-COMBO

## URFOG Integration board

<figure><img src=".gitbook/assets/image (1253).png" alt="" width="375"><figcaption></figcaption></figure>

## Introduction

The SFB-3 Fog Signal Transmitter can integrate with the UR Fog Security System, enabling the system to receive command from the Panel to activate during burglar alarm. Upon activation, the fog system will generate dense, harmless fog to obscure intruders' vision.

The SFB-3 Transmitter Board connects to and is powered by the UR Fog mainboard via a 1.27 mm pitch flat cable with an IDC-type polarized connector.

After SFB-3 is learned into the Control Panel, the UR Fog Security System will get notified to arm by heating up and getting ready to shoot. Home Automation Rules / Scenes can be set up for the Panel to activate Fog Security System in a burglar alarm.

Supported UR Fog Security System models include:

* UR FOG Modular 200/300/400/500/800
* UR Fog Compact 390

&#x20;

<figure><img src=".gitbook/assets/image (16).png" alt=""><figcaption></figcaption></figure>

## Identifying the Parts

#### 1.     Learn/Test Button

* Press and hold for 6 seconds to send a learn code to the Control Panel.
* Press the button once to send a test signal.&#x20;

#### 2.     J2 Serial Port

* Connects to the J11 port of UR Fog System mainboard via a standard 1.27 mm pitch flat cable ended with IDC type polarized connector.

#### 3.     Red LED Indicator



### Installation of the Transmitter

* Secure the SFB-3 transmitter board to the upper section of the fog system mounting bracket using the four screws provided.
* &#x20;Connect the J2 serial port on the SFB-3 to the J11 serial port on the UR Fog mainboard using a 1.27 mm pitch flat cable with an IDC-type polarized connector.

&#x20;

<figure><img src=".gitbook/assets/image (17).png" alt=""><figcaption></figcaption></figure>

&#x20;

## Features

#### Power Supply​

* When SFB-3 is connected to UR Fog System, 3.3V power supply can be provided by the fog system mainboard.

#### LED Indicator​

**SFB-3 RED LED**

* The Red LED displays the following statuses.

\-       Steady ON: Communication with the UR Fog system is not established.

\-       1 flash every 11 seconds: Communication is established with the UR Fog system.

\-       1 flash: When powered on / When the button is pressed shortly.

\-       5 flashes: Successful learning.

\-       2 flashes: Upon receiving acknowledgement from the panel.

**Fog System Front LEDs**

* The Green, Blue, and Red LEDs display the following statuses.

\-       Green LED ON: Fog system is heated to the correct temperature.

\-       Blue LED ON: Fog system is armed and ready to shoot.

\-       Red LED ON: Low battery or Absent Battery / Lack of electricity (AC Fail)

\-       Red LED quick flash: Finished Liquid

#### Supervision

* The SFB-3 will transmit a supervision signal every 17 to 19 minutes regularly to the Control Panel to report its condition.

### URFOG Security System fault Detection

**Fault Detection**

* The UR Fog Security System is able to detect and transmit the following Fog Security System fault status to the Control Panel.

\-          Finished Liquid

\-          Low battery or Absent Battery

\-          Lack of electricity (AC Fail)

\-          Burner failure

**Fault Restore**

* If no fault is detected for 1 minute, the transmitter will send fault restore signal the Control Panel.
* For a burner failure, after clearing the fault, you must restart the system and wait 8 minutes for the restore signal to be transmitted.

&#x20;

### Getting Started

#### Learning​

1\.  After connecting the SFB-3 transmitter to the UR Fog System, power on the fog system, the SFB-3 transmitter will be powered on as well.

2\.  Put the Control Panel into learning mode, refer to Control Panel manual for details.

3\.  Press the Learn button of SFB-3 for 6 seconds. The SFB-3 transmitter is now in learning mode and will transmit a learning code to the Control Panel.

4\.  When the Control Panel receives the learning code, it will list the device information accordingly. (SFB-3 will be displayed as Fog Generator.) Follow Control Panel manual instructions to complete

the learning procedure.

{% hint style="info" %}
Note:&#x20;

The SFB-3 transmitter will flash the red LED 5 times to upon successful learning.

If learning fails, the red LED will turn on for 6 seconds.
{% endhint %}

&#x20;

#### _Walk Test_

* After the SFB-3 transmitter is learnt-in, put the Control Panel into Walk Test mode, hold the SFB-3 transmitter in the desired location, and press the Test Button to transmit test signal to Control Panel.
* If the Control Panel is within the SFB-3 transmitter signal range, the panel will display device information accordingly. The LED of the SFB-3 shall flash twice for indication the communication between the panel and SFB-3 works fine.
* Proceed with mounting and installation once you are satisfied with the signal strength.

#### Edit Fog Generator Operation Area​

After the fog generator is learned into the Control Panel, if you wish to change the operation area, follow the instructions below to proceed.

1\.   Use the panel Edit Device function to change fog generator area setting.

2\.   Press the learn button on the SFB-3 transmitter for 6 seconds to send learning signal to panel.

&#x20;

### Operation

#### Arming the URFOG Security System​

* After SFB-3 is learned into the Control Panel, the transmitter will signal to UR Fog Security System to arm by heating up and getting ready to shoot with default 10 seconds emission time. The shooting time can be adjusted with local button operation on the UR Fog Security System. Please refer to the UR Fog System user manual for details.

#### &#x20;Alarm Activation

* &#x20;The Fog Generator can be triggered by home automation rules/scenes set in the Climax Control Panel.
* When activated, the Fog Generator will start shooting fog for default 10 seconds or the set shooting time.

{% hint style="info" %}
Note: The Fog Generator can only be activated when it is heated to the correct temperature (Green LED ON), armed and read to shoot (Blue LED ON).
{% endhint %}
