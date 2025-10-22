# VESTA-404

**Climax HSGW Gen2 Installation Guide**

<figure><img src=".gitbook/assets/image (7) (1).png" alt=""><figcaption></figcaption></figure>

Content

1\. Getting to Know Your HSGW Gen2: 3

2\. Creating a Customer Account 7

3\. Setting up the Panel 8

4\. Confirming Signaling with Alarm.com 11

5\. Adding Sensors and Peripherals 11

6\. Walk Test and Device Mounting 14

7\. System Programming 14

8\. Remote Toolkit 15

Appendix 15

Appendix A: LED Guide 15

Appendix B: Communication Troubleshooting 16

Appendix C: Panel Programming Options 16

Appendix D: Sensor Group Configuration 24

Appendix E: CID Reporting Codes 29

Appendix F: Panel Factory Reset 30

Appendix G: Sensor Enrollment Instructions 30

**Required Equipment:**

1. Phillips head Screwdriver
2. Drill and bits for mounting screws OR double-sided adhesive tape

**Local Regulation Settings:**

If your system requires compliance with the local regulation PD 6662, it is required that the system cannot be disarmed via a user code input into a keypad. Rather, the user must be provided option to disarm the system via a button press, keyfob, or prox tag that is used in tandem with an acceptable tag reading device.

| Alarm.com Hybrid Installation Guide Version 7.0 Published 4/12/23 | 2 |
| ----------------------------------------------------------------- | - |

1\. Getting to Know Your HSGW Gen2:

**About the Panel**

HSGW-Gen2-V1 is a fixed wall mounting wireless alarm system control panel. It is designed to protect your home by forming an alarm system with various wireless sensors. When an intruder is detected, the wireless sensor will transmit signal to the control panel to raise an alarm and report to the Central Monitoring Station.

HSGW-Gen2-V1 features RF and Z-Wave wireless protocol for communication with accessory devices. The RF devices are simple and easy to use while the Z-Wave devices, using corresponding network, is capable of performing more advanced function and add flexibility to alarm system such as using Remote Keypad to control system mode, view alarm memory and event log, or capturing alarm pictures using PIR Camera to send to panel wirelessly for alarm visual verification.

**What’s in the Box**

* 1 x HSGW-Gen2-V1 Control Panel
* 1 x AC Power Cord for Built-in S.P.S (12V 1.5A)
* 1 x Installation and Instruction Manual
* 4 x Screws and Wall Plug for wall mounting

**HSGW Gen2 Diagram**

![](<.gitbook/assets/0 (134).jpeg>)

| Alarm.com Hybrid Installation Guide Version 7.0 Published 4/12/23 | 3 |
| ----------------------------------------------------------------- | - |

**Diagram Key** Mounting Bracket

![](<.gitbook/assets/1 (109).jpeg>)

1. **LED 1 - Area 1 (Green/Red)**
   * Full Arm mode - Red lighting up
   * Home/1/2/3 mode - Red flashing
   * Disarm mode - Green lighting up
   * Walk Test or Learning mode - Green flashing
2. **LED 2 - Area 2 (Green/Red)**
   * Full Arm mode - Red lighting up
   * Home/1/2/3 mode - Red flashing
   * Disarm mode - Green lighting up
   * Walk Test or Learning mode - Green flashing
3. **LED 3 - Status (Orange/Red)**
   * System Fault - Orange lighting up
   * Alarm Trigger – Red flashing
   * Alarm in Memory – Red lighting up
4. **Speaker**
5. **Micro SIM Card Compartment**
6. **USB Port**
7. **Learn/Reset Button**
8. **Ethernet Port**
9. **Battery Switch (slide to “ON” to meet requirements of the applicable EN standard.)**
10. **Internal Cover**
11. **Buzzer**
12. **Wall mounting slots\***

\* NOTE: While this serves as the hook location for the wall mount back panels, there is also a secondary tamper present on the EN2 complaint variant of the panel. The internal tamper switch which is compressed when the panel is hooked onto the mounting bracket. When the panel is removed from the mounting bracket, the tamper switch will be activated and the panel will send a tamper open signal to remind the user of this condition.

1. **Power Cord Inlet**
2. **Wiring Hole**
3. **Fixing Screws x 2**
4. **Wall Mounting Holes x 2**
5. **Mounting Bracket**

| Alarm.com Hybrid Installation Guide Version 7.0 Published 4/12/23 | 4 |
| ----------------------------------------------------------------- | - |

**Design Specs**

| **Function**                                                      |                                                                        |   |   |   |
| ----------------------------------------------------------------- | ---------------------------------------------------------------------- | - | - | - |
|                                                                   |                                                                        |   |   |   |
| Number of partitions                                              | 2                                                                      |   |   |   |
|                                                                   |                                                                        |   |   |   |
| Number of wireless zones                                          | 80 per partition, 160 in total                                         |   |   |   |
|                                                                   |                                                                        |   |   |   |
| Number of PIR cameras                                             | 16 (3-5 recommended)                                                   |   |   |   |
|                                                                   |                                                                        |   |   |   |
| Number of users                                                   | 40 total users with multi-partition access\*                           |   |   |   |
|                                                                   |                                                                        |   |   |   |
|                                                                   |                                                                        |   |   |   |
| Zone Types                                                        | See Appendix D                                                         |   |   |   |
|                                                                   |                                                                        |   |   |   |
| User PIN Codes                                                    | 1 PIN Code each user (6-digits, number 0\~9), available combination    |   |   |   |
|                                                                   | from 000100\~999999 (999998 different combinations, 000000 and         |   |   |   |
|                                                                   | 000001 are disallowed).                                                |   |   |   |
|                                                                   | Note: Input of 5 invalid User PIN codes at the remote keypad will lock |   |   |   |
|                                                                   | the remote keypad for 15 minutes.                                      |   |   |   |
|                                                                   |                                                                        |   |   |   |
| Control Facilities                                                | Remote Keypad & Remote Controller                                      |   |   |   |
|                                                                   | Alarm.com Server Webpages                                              |   |   |   |
|                                                                   |                                                                        |   |   |   |
| Report Destinations                                               | 20 Monitoring Stations or mobile number                                |   |   |   |
|                                                                   |                                                                        |   |   |   |
| Reporting Format                                                  | Contact ID, SIA, SMS Text,                                             |   |   |   |
|                                                                   |                                                                        |   |   |   |
| Arming Modes                                                      | Arm Away, Arm Stay, Disarm                                             |   |   |   |
|                                                                   |                                                                        |   |   |   |
| Alarm Type                                                        | Burglar, Panic, Fire, Medical, Emergency, Water, Silent                |   |   |   |
|                                                                   |                                                                        |   |   |   |
| Siren Timeout                                                     | Programmable (3 min. by default), For Remote Keypad use only           |   |   |   |
|                                                                   |                                                                        |   |   |   |
| Supervision                                                       | Programmable time frame for inactivity alert                           |   |   |   |
|                                                                   |                                                                        |   |   |   |
| Special Function                                                  | Tamper Protection                                                      |   |   |   |
|                                                                   |                                                                        |   |   |   |
| GSM Standards                                                     | Compiles with CE standards 4GPP TS 51.010-1, EN 301 511,               |   |   |   |
|                                                                   | EN301489-7                                                             |   |   |   |
|                                                                   |                                                                        |   |   |   |
| Alarm.com Hybrid Installation Guide Version 7.0 Published 4/12/23 | 5                                                                      |   |   |   |

| **EN Classification**    | EN Grade 2 Class II                                                   |                            |   |
| ------------------------ | --------------------------------------------------------------------- | -------------------------- | - |
|                          |                                                                       |                            |   |
| Alarm Transmission Path  | Dual Path: DP1 (EN50136-1:2012)                                       |                            |   |
|                          |                                                                       |                            |   |
| Supported RCT            | Alarm Report Server (ARS), Fibro, OH200, MasterMind, Manitou,         |                            |   |
| MicroKey and SIA DC 09   |                                                                       |                            |   |
|                          |                                                                       |                            |   |
|                          |                                                                       |                            |   |
| Mode of Acknowledgement  | Pass-through (EN50136-2:2013, Clause 6.1.3)                           |                            |   |
| Operation.               |                                                                       |                            |   |
|                          |                                                                       |                            |   |
|                          |                                                                       |                            |   |
| **Memory**               | DDR3L SDRAM: 512Mbyte                                                 |                            |   |
|                          |                                                                       |                            |   |
|                          | eMMC : 4GByte                                                         |                            |   |
|                          |                                                                       |                            |   |
| **Electrical**           |                                                                       |                            |   |
|                          |                                                                       |                            |   |
| Power Source             | Built-in switching power supply (S.P.S), 100-240V, 50/60Hz input, 12V |                            |   |
|                          | 1.5A output                                                           |                            |   |
|                          |                                                                       |                            |   |
| Power Supply Type        | PS Type A, not suitable for use external to supervised premises.      |                            |   |
|                          |                                                                       |                            |   |
| Backup Battery           | 7.2V, NiMH 600mAh AAA rechargeable battery pack (built-in)            |                            |   |
|                          |                                                                       |                            |   |
| APS fault Low Voltage SD | 7.3V±3%                                                               |                            |   |
| signal threshold         |                                                                       |                            |   |
|                          |                                                                       |                            |   |
|                          |                                                                       |                            |   |
| Battery Duration         | 14 hours                                                              |                            |   |
|                          |                                                                       |                            |   |
| Battery Recharge Time to | 72 hours                                                              |                            |   |
| 80% of 600mAH            |                                                                       |                            |   |
|                          |                                                                       |                            |   |
|                          |                                                                       |                            |   |
| Minimum Energy Level of  | 86%                                                                   |                            |   |
| Backup Battery           |                                                                       |                            |   |
|                          |                                                                       |                            |   |
|                          |                                                                       |                            |   |
| Current Drain            | AC Powered                                                            | Average. 126mA/12V standby |   |
| 839mA/12V full load      |                                                                       |                            |   |
|                          |                                                                       |                            |   |
|                          |                                                                       |                            |   |
|                          |                                                                       |                            |   |
|                          | Battery Powered                                                       | Average. 42mA/7.2V standby |   |
|                          | 876mA/7.2V full load                                                  |                            |   |
|                          |                                                                       |                            |   |
|                          |                                                                       |                            |   |
| **Wireless**             |                                                                       |                            |   |
|                          |                                                                       |                            |   |

| Alarm.com Hybrid Installation Guide Version 7.0 Published 4/12/23 | 6 |
| ----------------------------------------------------------------- | - |

| GSM/GPRS/EDGE Frequency         | B1 (2100 MHz) / B3 (1800 MHz) / B5 (850 MHz) / B7 (2600 MHz) / B8 |   |
| ------------------------------- | ----------------------------------------------------------------- | - |
|                                 | (900 MHz) / B20 (800 MHz) (EU)                                    |   |
|                                 |                                                                   |   |
| LTE Frequency                   | B1 (2100 MHz) / B3 (1800 MHz) / B5 (850 MHz) / B7 (2600 MHz) / B8 |   |
| (900 MHz) / B20 (800 MHz) (EU)  |                                                                   |   |
|                                 |                                                                   |   |
|                                 |                                                                   |   |
| RF Frequency                    | 868.6375MHz / 433.82MHz / 426MHz / 910 MHz                        |   |
|                                 |                                                                   |   |
| Z-Wave Frequency\*              | 800 series Z-wave                                                 |   |
| \*Only available on select HSGW |                                                                   |   |
| Panels                          |                                                                   |   |
|                                 |                                                                   |   |
| Antenna Type                    | GSM: Main – PIFA; AUX – Dipole                                    |   |
|                                 | ZW: Monople\*                                                     |   |
|                                 | RF: Monople                                                       |   |
|                                 | \*Only available on select HSGW Panels                            |   |
|                                 |                                                                   |   |
| Encryption                      | Private Encryption Method                                         |   |
|                                 |                                                                   |   |
| Protocol                        | Climax                                                            |   |
|                                 |                                                                   |   |
| **Physical Properties**         |                                                                   |   |
|                                 |                                                                   |   |
| Operating Temperature           | -10°C to 45°C (14°F to 113°F)                                     |   |
|                                 |                                                                   |   |
| Humidity                        | 50 \~ 85% relative humidity @23°C, non-condensing                 |   |
|                                 |                                                                   |   |
| Size                            | 185mm x 185mm x 50mm                                              |   |
|                                 |                                                                   |   |
| Weight                          | 580g (Includes backup battery)                                    |   |
|                                 |                                                                   |   |

2\. Creating a Customer Account

In order to use the panel, a customer account must be created using the Alarm.com Dealer website or MobileTech app\*. The MobileTech app can be downloaded from the Apple App Store or the Android Play Store. Please obtain valid credentials from your administrator in order to use either application.

If your administrator has not created an account or commitment prior to installation, the following is needed to create the customer account:

* Customer Name

| Alarm.com Hybrid Installation Guide Version 7.0 Published 4/12/23 | 7 |
| ----------------------------------------------------------------- | - |

* Address
* Phone Number
* Email Address
* 15 digit IMEI from the panel

To activate a commitment, only the IMEI is needed.

\* For UL compliant installations, only the Customer and Dealer web portals may be used.

3\. Setting up the Panel

Before starting, verify that you have all the components needed for the installation:

* Panel
* Power Adapter
* Stand for Table Mounting (may come attached to panel)
* Ethernet Cable
* Screws for Wall Mounting
* Peripherals

**Powering up and connecting the panel**

1. Remove the 2 screws that secured the panel casing to the mounting bracket. (Figure 1)
2. Remove the mounting bracket to reveal the back cover fixing screw. (Figure 2)

**Figure 1** **Figure 2**

![](<.gitbook/assets/2 (117).png>)

| Alarm.com Hybrid Installation Guide Version 7.0 Published 4/12/23 | 8 |
| ----------------------------------------------------------------- | - |

1. Remove the screw securing the back cover (as circled in Figure 2).
2. Set up the Control Panel though the following steps:

I. Connect Ethernet cable to panel Ethernet port.

1. Insert a functional micro SIM Card into Micro SIM Card Compartment, the SIM Card PIN Code must be disabled first.
2. Slide Battery Switch to ON position.

IV. Use the AC Power Cord for Built-in S.P.S to to connect to the mains power.

1. Wire the cable, close the back cover and secure it by fastening the screw. Proceed to mount the panel onto the wall.

**Mounting the panel (Required for EN Compliance)**

The panel can be either fixed on the wall or placed on deskop. **For the panel to meet requirements of the applicable EN standard, wall mounting installation must be used.**

1. Use the mounting holes as template, mark mounting locations on the wall.
2. Secure the mounting bracket onto the wall by tightening the 2 screws through the wall mounting holes.

![](<.gitbook/assets/3 (91).jpeg>)

| Alarm.com Hybrid Installation Guide Version 7.0 Published 4/12/23 | 9 |
| ----------------------------------------------------------------- | - |

1. Mount the Control Panel with the hooks of the mounting bracket latched onto the back cover of the the panel, and push it downward until you hear a clicking sound.

Make sure the tamper switch is properly compressed against the hook of the mounting bracket. Then fasten the 2 bottom fixing screws to complete the installation.

![](<.gitbook/assets/4 (115).png>)

**Push**

**LED Status**

1. As the panel powers on, all LEDS will illuminate then turn off to indicate the panel is powering up.
2. Once the panel powers on, LED 3 will flash ORANGE to indicate the panel is registering with the Cellular network and acquiring an IP address from the router.
3. Once the panel successfully registers with the Cellular Network and acquires an IP address, LED
   1. will blink GREEN every 5 to 10 seconds to indicate communication has been established. a. See Appendix A LED Guide for a comprehensive guide to LED behavior.
4. The Cellular registration process may take up to 10 minutes. If after 10 minutes, LED 3 is still ORANGE, verify there are no fault conditions on the panel. If there are no other fault conditions, see Appendix B Communication Troubleshooting.

**Button Functionality:**

| Alarm.com Hybrid Installation Guide Version 7.0 Published 4/12/23 | 10 |
| ----------------------------------------------------------------- | -- |

The reset button is located on the right side of the PCB, located inside the panel (labeled as item 24 on the diagram key). The reset button can be used for multiple occasions by holding down the button for various lengths of time:

**Phone Test (3-10 seconds)**: Phone test is done to send a communication test from the panel to the back end. It initiates communication and verifies that the module is communicating on the cellular network.

**Learn Mode (10-20 seconds)**: Using the button to send the panel into Learn Mode is done to add sensor to your panel locally.

**Power Cycle (20-30 seconds):** A power cycle turns the security panel completely off and then powers it back on to refresh it. This is a common action taken for a variety of trouble shooting problems.

4\. Confirming Signaling with Alarm.com

In order to program and configure the system, the panel must be able to communicate with the Alarm.com backend. To confirm the system is communicating via both Cellular and Broadband, follow the steps below:

*
  1. Confirm basic communication by checking for Acknowledged Messages in the Event History on either MobileTech or the Dealer website.
  2. From the _Remote Toolkit_ run a _Communication Signal Test_ to verify Communication. This will verify communication over Broadband and Cellular, as well as check the cellular signal strength.

a. This test may take up to 5 minutes to run.

1. Adding Sensors and Peripherals

**Security Sensors**

Security Sensors can only be added to the system locally via a Learn Mode based sensor identification.

**Adding Security Sensors using the Dealer Site or MobileTech:**

1. Put the panel in learn mode
   1. Dealer Site: _Equipment > Sensors > Add a Sensor_
   2. MobileTech _Equipment > Sensors > Add Sensor_
2. Wait for the message “Checking for new sensors on the network.”
3. LED 1 and LED 2 will turn solid GREEN and a one-tone beep will sound.
4. Trigger a device to add it to the network.
   1. Refer to device installation manual for how to trigger each specific device
5. When a device is added successfully, the panel will emit a one-tone beep and the device will be shown on the screen.
6. Continue triggering other devices that need to be learned in. Several devices can be added without needing to re-enter Learn Mode.
   1. If no new devices are triggered, Learn Mode will time out after 5 minutes
7. Once all devices have been added, choose to EXIT Learn Mode.

| Alarm.com Hybrid Installation Guide Version 7.0 Published 4/12/23 | 11 |
| ----------------------------------------------------------------- | -- |

*
  1. On the subsequent screen, the option to define the Sensor Name, Group Number, Partition, and Sensor Activity Monitoring settings are available.
     1. External Sirens Only: Please refer to device specification manual for instructions on how to change the sensor partition as step 4 will need to be completed again after changing the partition from Alarm.com.
     2. Sensor Groups will have a number and a short description of the behavior. For a full description of group behavior, please refer to Appendix D.
* Note the keypad must be installed within the protected premises for UL Compliant installations.

**Removing Security Sensors using the Dealer Site or MobileTech**

* Navigate to the Delete Sensor Page.
  1. Dealer Site: _Equipment > Sensors > Delete a Sensor/Peripheral_
  2. MobileTech: _Equipment > Sensors > Delete Sensor_
* Check off the DELETE box next to the sensor that needs to be removed.
* Click Send Command to remove the sensor from the system.
* The sensor will be removed from the system within 5 minutes.

**Changing Sensor Settings and Configuration:**

1. Dealer Site: From _Equipment_ page select the appropriate sensor and action:
   1. Change Sensor Name
   2. Change Sensor Group
   3. Change Sensor Partition
   4. Change Sensor Activity Monitoring Settings
2. MobileTech: Navigate to _Equipment > Sensors._
   1. This will allow updating the Sensor Name, Group, and Activity Monitoring Setting.
   2. To update the Partition, continue to _Advanced Sensor Settings._

NOTE:

If your system requires compliance with the local regulation PD 6662, it is required that the system cannot be disarmed via a user code input into a keypad. Rather, the user must be provided option to disarm the system via a button press, keyfob, or prox tag that is used in tandem with an acceptable tag reading device.

**Z-Wave Sensors:**

Adding a Z-Wave device using the Dealer Site or MobileTech:

1. Put the panel into Add Mode
   1. Dealer Site: Navigate to _Equipment > emPower tab > Advanced Z-Wave Settings > Add Z-Wave Devices_
   2. MobileTech: Navigate to _Equipment > Z-Wave Devices > Add Z-Wave Devices_
2. Trigger Z-Wave device to add it to the network
3. When a device is added successfully, the panel will emit a one-tone beep and the device will be shown on the screen

| Alarm.com Hybrid Installation Guide Version 7.0 Published 4/12/23 | 12 |
| ----------------------------------------------------------------- | -- |

1. Continue triggering other devices that need to be learned in. Several devices can be added without needing to re-enter Learn Mode
2. When all Z-Wave devices have been added, exit Add Mode and run a Network Rediscovery

Removing a Z-Wave Device using the Dealer Site or MobileTech

1. Put the panel into Delete Mode
   1. Dealer Site: Navigate to _Equipment > emPower Devices tab > Advanced Z-Wave Settings > Delete Z-Wave Devices._
   2. MobileTech: Navigate to _Equipment > Z-Wave Devices > Delete Z-Wave Devices._
2. Trigger the device to delete if from the network and clear the device memory.
3. Continue removing other devices that need to be removed, devices that are removed will show up on the screen.
4. Once all devices are removed, exit Delete Mode and run a network rediscovery.

**Local Learning:**

Devices can be learned in locally without the Alarm.com Website as well. This action is limited to security sensors and cannot be used for Z-wave devices.

1. Press and hold the Auto Learn button for 10 seconds until the panel emits a one-tone beep to indicate it has entered Learn Mode. The top LEDs will turn solid GREEN to indicate the panel is in learn mode.
2. Trigger each device following the procedure in the device installation manual.
3. When the panel receives a signal from the device it will emit a two-tone beep to indicate that it was successfully learned into the panel.
4. When all devices are learned in, press and hold the Auto Learn button on the panel for one second to exit learn mode. The panel will emit a two-tone beep and the LEDS will turn off to indicate it has returned to its normal mode.
5. Configure the sensors from the Alarm.com Dealer Site or MobileTech.

**Removing Security Sensors using the Dealer Site or MobileTech**

* Navigate to the Delete Sensor Page.
  1. Dealer Site: _Equipment > Sensors > Delete a Sensor/Peripheral_
  2. MobileTech: _Equipment > Sensors > Delete Sensor_
* Check off the DELETE box next to the sensor that needs to be removed.
* Click Send Command to remove the sensor from the system.
* The sensor will be removed from the system within 5 minutes.

**Changing Sensor Settings and Configuration:**

After a security sensor is learned in, the following settings can be changed:

* Change sensor name
* Change sensor group
* Change sensor partition
* Change sensor Activity Monitoring Status
* Change sensor status

| Alarm.com Hybrid Installation Guide Version 7.0 Published 4/12/23 | 13 |
| ----------------------------------------------------------------- | -- |

To edit a sensor, navigate to the “change” section:

*
  *
    1. Dealer Site: _Equipment > Sensors > Change_
    2. MobileTech: _Equipment > Sensors > Change_
  * Click on the drop down to show all available settings. Once you are ready to submit the new setting, press “Send Command”

1. Walk Test and Device Mounting

Once all devices are learned in, place the devices in their final locations and run a walk test to ensure that all devices are signaling properly in their final locations. Hardwired sensors may already be placed depending on the type of install occurring.

**Walk Test**

1. Enter Walk Test mode, LED 1 and LED 2 will blink GREEN while in Walk Test mode
   1. Dealer Site: _AirFx Remote Toolkit > Walk Test_
   2. MobileTech: _Equipment > Sensors > Walk Test_
2. Select Begin Walk Test and activate each sensor
3. As sensors are Activated, their action will appear onscreen and the sensor will emit a two-tone beep
4. After all sensors have been triggered, select End Walk Test to exit walk test mode.
   1. If a sensor trigger did not register on the Walk Test, try moving it closer to the control panel and trigger it again. If the device works then, try using an RF repeater to extend the range of the control panel.

**Device Mounting**

Once devices are signaling in their final locations, they can be mounted according to the instructions provided with each device.

7\. System Programming

The system settings can be programmed via the _Remote Toolkit_ on the Alarm.com Dealer Website or MobileTech App. The below outlines the definitions of the various system settings along with descriptions and setting options including the system default.

Default system programming can be updated via the Alarm.com Dealer Site using AirFX Programming Templates. For more on AirFX Programming templates, contact your Alarm.com Sales rep.

**Panel Programming Options:**

Please see Appendix C for a full list of panel programming options and default settings.

**Sensor Programming Options:**

| Alarm.com Hybrid Installation Guide Version 7.0 Published 4/12/23 | 14 |
| ----------------------------------------------------------------- | -- |

Sensors can be programmed by changing the sensor groups from the Dealer Site _Equipment > Sensors > Change Sensor Group_ page or the MobileTech _Equipment > Sensors > Change Sensor_ Group page. See Appendix D for Sensor Group descriptions.

8\. Remote Toolkit

Once the system has been properly installed and programmed, ensure everything is running well by using a System Check from the Remote Toolkit. This will start an automatic system wide verification of proper functionality. If something is not working perfectly, troubleshooting steps and recommendations will be provided.

This check can be done by selecting _Remote Toolkit_ on MobileTech or the Dealer Site and running a System Check.

Appendix

Appendix A: LED Guide

**LED 1 (Red/Green)**

Red ON – Partition One is Armed Away

RED Flash – Partition One is Armed Stay

Green On – System is in Auto Learn Mode

Rapid Green Flash – System is in Walk Test/Z-Wave Delete Mode

Green Flash every 5 Seconds – Panel is Communicating over both Cell and IP Paths Green Flash every 10 seconds – Panel is communicating over 1 path

**LED 2 (Red/Green)**

Red ON – Partition Two is Armed Away

RED Flash – Partition Two is Armed Stay

Green On – System is in Auto Learn Mode

Rapid Green Flash – System is in Walk Test/Z-Wave Delete Mode

**LED 3 (Red/Yellow)**

Red On – Alarm in memory

Red Flash – Alarm

Yellow On – System fault.

Yellow Flash – Registering to Cellular Network

Possible System Faults:

* Sensor Tamper
* Sensor Malfunction
* Sensor Low Battery

| Alarm.com Hybrid Installation Guide Version 7.0 Published 4/12/23 | 15 |
| ----------------------------------------------------------------- | -- |

* Panel Tamper
* Panel Low Battery
* Panel Battery Off
* Cell Communication Failure
* Broadband Communication Failure/No Ethernet Cable Plugged In

Appendix B: Communication Troubleshooting

**Cell Failure**

There are several possible reasons the cellular communication is not connected to Alarm.com:

* Wireless signal strength issue or coverage issue.

1. Make sure the module is installed high enough within the structure and near an exterior wall. Alarm.com recommends that the module be installed above ground (i.e. NOT in a basement) and not in the middle of a large structure (i.e. NOT in an interior closet far

from the exterior walls).

1. Make sure nothing near the module could be causing RF interference. Large metal

objects or ductwork, sheet metal walls and appliances that generate RF may interfere with the module.

*
  1. If the customer is located in a borderline wireless coverage area, a high-gain, remote antenna may be required. Contact your Alarm.com Rep about this if needed.
* Make sure the SIM card has not been removed.

**Broadband Failure**

For issues with broadband communication, please check the following:

* Ensure the Ethernet cable is plugged into both the customer’s router and the panel.
  1. If the panel is connected via WiFi, ensure that the SSID and Password are correct.
* Ensure that the customer’s router has power and internet by checking the internet connection of a different device on the network.
* If the panel is connected via Static IP address, ensure that all the parameters are set in accordance with network specifications.

**Accessing Panel Troubleshooting Page**

**Via Customer Router:**

1. Connect a laptop, phone, or tablet to the same network as the panel.
2. Login to customer router using the router manufacturer instructions and find the IP address of the panel.
3. Navigate to the panel’s IP address

Appendix C: Panel Programming Options

| Setting                                                           | Setting Description                  | Available Options |   |
| ----------------------------------------------------------------- | ------------------------------------ | ----------------- | - |
|                                                                   |                                      |                   |   |
| AC Fail Report Timer                                              | If AC power fails, this will specify | Disabled          |   |
|                                                                   | communication delay.                 |                   |   |
|                                                                   | 20 Minutes                           |                   |   |
|                                                                   |                                      |                   |   |
|                                                                   |                                      | 3 Minutes         |   |
| Alarm.com Hybrid Installation Guide Version 7.0 Published 4/12/23 | 16                                   |                   |   |

|                                                                   |                                           | 30 Minutes  |   |
| ----------------------------------------------------------------- | ----------------------------------------- | ----------- | - |
|                                                                   |                                           |             |   |
|                                                                   |                                           | 5 Minutes   |   |
|                                                                   |                                           |             |   |
|                                                                   |                                           | 1 Hour      |   |
|                                                                   |                                           |             |   |
|                                                                   |                                           | 1 Minute    |   |
|                                                                   |                                           |             |   |
|                                                                   |                                           | 10 Minutes  |   |
|                                                                   |                                           |             |   |
|                                                                   |                                           | 15 Minutes  |   |
|                                                                   |                                           |             |   |
| Jamming Report Timer                                              | Jamming Report Delay Timer                | Disabled    |   |
|                                                                   |                                           |             |   |
|                                                                   |                                           | 2 Minutes   |   |
|                                                                   |                                           |             |   |
|                                                                   |                                           | 1 Minute    |   |
|                                                                   |                                           |             |   |
| Arm Fault Type (Partition 1)                                      | When system is being armed under fault    | Confirm     |   |
|                                                                   | condition. 1. Confirm: The panel will     |             |   |
|                                                                   | display a Mode Change Fault message.      |             |   |
|                                                                   | Arming again within 10 seconds will       |             |   |
|                                                                   | Direct Arm                                |             |   |
|                                                                   | force arm the system.                     |             |   |
|                                                                   |                                           |             |   |
|                                                                   | 2. Direct Arm: The system will be force   |             |   |
|                                                                   | armed directly and report an event.       |             |   |
| Final Door (Partition 1)                                          | Sets whether the system will              | Disable     |   |
|                                                                   | automatically Arm Away once a door        |             |   |
|                                                                   | contact, set as entry device, is detected |             |   |
|                                                                   | Enable                                    |             |   |
|                                                                   | as closed, even if the count-down period  |             |   |
|                                                                   |                                           |             |   |
|                                                                   | is not yet complete.                      |             |   |
| Entry Delay 1 for Arm Away                                        | Entry Delay 1 – For UL Compliant          | 0–240       |   |
| (Partition 1)                                                     | installations, Entry Delay must be set to | Default: 30 |   |
|                                                                   | 45 seconds or less.                       |             |   |
| Entry Delay 1 for Arm Away                                        | Entry Delay 1 – For UL Compliant          | 0–240       |   |
| (Partition 2)                                                     | installations, Entry Delay must be set to | Default: 30 |   |
|                                                                   | 45 seconds or less.                       |             |   |
| Entry Delay 2 for Arm Away                                        | Entry Delay 2 – For UL Compliant          | 0–240       |   |
| (Partition 1)                                                     | installations, Entry Delay must be set to | Default: 60 |   |
|                                                                   | 45 seconds or less.                       |             |   |
| Entry Delay 2 for Arm Away                                        | Entry Delay 2 – For UL Compliant          | 0–240       |   |
| (Partition 2)                                                     | installations, Entry Delay must be set to | Default: 60 |   |
|                                                                   | 45 seconds or less.                       |             |   |
| Exit Delay for Arm Away                                           | Exit Delay - For UL Compliant             | 0–240       |   |
| (Partition 1)                                                     | Installations, Exit Delay must be set to  | Default: 30 |   |
|                                                                   | 120 seconds or less.                      |             |   |
| Exit Delay for Arm Away                                           | Exit Delay - For UL Compliant             | 0–240       |   |
| (Partition 2)                                                     | Installations, Exit Delay must be set to  | Default: 30 |   |
|                                                                   | 120 seconds or less.                      |             |   |
| Door Chime (Partition 1)                                          | Select whether a sensor will cause the    | High        |   |
|                                                                   | panel to chime when it is activated.      |             |   |
|                                                                   | Off                                       |             |   |
|                                                                   |                                           |             |   |
|                                                                   |                                           | Low         |   |
|                                                                   |                                           |             |   |
| Door Chime (Partition 2)                                          | Select whether a sensor will cause the    | High        |   |
|                                                                   | panel to chime when it is activated.      |             |   |
|                                                                   | Off                                       |             |   |
|                                                                   |                                           |             |   |
|                                                                   |                                           | Low         |   |
|                                                                   |                                           |             |   |
| Alarm.com Hybrid Installation Guide Version 7.0 Published 4/12/23 | 17                                        |             |   |

| Warning Beep (Partition 1)                                        | Determines whether the panel will issue    | High                  |   |
| ----------------------------------------------------------------- | ------------------------------------------ | --------------------- | - |
|                                                                   | a warning beep for fault conditions.       |                       |   |
|                                                                   | Off                                        |                       |   |
|                                                                   |                                            |                       |   |
|                                                                   |                                            | Low                   |   |
|                                                                   |                                            |                       |   |
| Warning Beep (Partition 2)                                        | Determines whether the panel will issue    | High                  |   |
|                                                                   | a warning beep for fault conditions.       |                       |   |
|                                                                   | Off                                        |                       |   |
|                                                                   |                                            |                       |   |
|                                                                   |                                            | Low                   |   |
|                                                                   |                                            |                       |   |
| Entry Delay 1 for Arm Stay                                        | Entry Delay 1 – For UL Compliant           | 0–240                 |   |
| (Partition 1)                                                     | installations, Entry Delay must be set to  | Default: 30           |   |
|                                                                   | 45 seconds or less.                        |                       |   |
| Entry Delay 1 for Arm Stay                                        | Entry Delay 1 – For UL Compliant           | 0–240                 |   |
| (Partition 2)                                                     | installations, Entry Delay must be set to  | Default: 30           |   |
|                                                                   | 45 seconds or less.                        |                       |   |
| Entry Delay 2 for Arm Stay                                        | Entry Delay 2 – For UL Compliant           | 0–240                 |   |
| (Partition 1)                                                     | installations, Entry Delay must be set to  | Default: 60           |   |
|                                                                   | 45 seconds or less.                        |                       |   |
| Entry Delay 2 for Arm Stay                                        | Entry Delay 2 – For UL Compliant           | 0–240                 |   |
| (Partition 2)                                                     | installations, Entry Delay must be set to  | Default: 60           |   |
|                                                                   | 45 seconds or less.                        |                       |   |
| Exit Delay for Arm Stay                                           | Exit Delay – For UL Compliant              | 0–240                 |   |
| (Partition 1)                                                     | Installations, Exit Delay must be set to   | Default: 30           |   |
|                                                                   | 120 seconds or less.                       |                       |   |
| Exit Delay for Arm Stay                                           | Exit Delay – For UL Compliant              | 0–240                 |   |
| (Partition 2)                                                     | Installations, Exit Delay must be set to   | Default: 30           |   |
|                                                                   | 120 seconds or less.                       |                       |   |
| Dealer Code                                                       | Set Dealer Code to override Sensor         | Any 4 Digit User Code |   |
|                                                                   | Tampers during INCERT monitoring.          | Default: NULL         |   |
|                                                                   | Note: This setting is only used when       |                       |   |
|                                                                   | INCERT monitoring is enabled.              |                       |   |
| Auto Check-in Interval                                            | Select the desired Auto Check-In           | Disable               |   |
|                                                                   | frequency from the drop down menu          |                       |   |
|                                                                   | Every Week                                 |                       |   |
|                                                                   | below. After you have updated the          |                       |   |
|                                                                   | Every Day                                  |                       |   |
|                                                                   | setting and clicked "change", please click |                       |   |
|                                                                   |                                            |                       |   |
|                                                                   | Every 6 Hours                              |                       |   |
|                                                                   | "Upload From Panel" at the top of the      |                       |   |
|                                                                   |                                            |                       |   |
|                                                                   | Every 4 Weeks                              |                       |   |
|                                                                   | page to make sure the new setting takes    |                       |   |
|                                                                   |                                            |                       |   |
|                                                                   | effect.                                    |                       |   |
| Auto Check-in Offset Period                                       | Auto Check-in Offset                       | 2hr                   |   |
|                                                                   |                                            |                       |   |
|                                                                   |                                            | 3hr                   |   |
|                                                                   |                                            |                       |   |
|                                                                   |                                            | 4hr                   |   |
|                                                                   |                                            |                       |   |
|                                                                   |                                            | 6hr                   |   |
|                                                                   |                                            |                       |   |
|                                                                   |                                            | 8hr                   |   |
|                                                                   |                                            |                       |   |
|                                                                   |                                            | 1hr                   |   |
|                                                                   |                                            |                       |   |
|                                                                   |                                            | 12hr                  |   |
|                                                                   |                                            |                       |   |
| Dialer Delay                                                      | Dialer Delay                               | 0 seconds             |   |
|                                                                   |                                            |                       |   |
|                                                                   |                                            | 15 seconds            |   |
|                                                                   |                                            |                       |   |
|                                                                   |                                            | 30 seconds            |   |
| Alarm.com Hybrid Installation Guide Version 7.0 Published 4/12/23 | 18                                         |                       |   |

|                                 |                                             | 45 seconds               |   |
| ------------------------------- | ------------------------------------------- | ------------------------ | - |
|                                 |                                             |                          |   |
| Tamper Alarm (Partition 1)      | Tamper Alarm                                | Arm Away                 |   |
|                                 |                                             |                          |   |
|                                 |                                             | Always                   |   |
|                                 |                                             |                          |   |
| Tamper Alarm (Partition 2)      | Tamper Alarm                                | Arm Away                 |   |
|                                 |                                             |                          |   |
|                                 |                                             | Always                   |   |
|                                 |                                             |                          |   |
| Supervision Check (Partition 1) | Determines whether the panel                | Off                      |   |
|                                 | supervises sensors on the system to         |                          |   |
|                                 | On                                          |                          |   |
|                                 | ensure they are still signaling.            |                          |   |
| Supervision Check (Partition 2) | Determines whether the panel                | Off                      |   |
|                                 | supervises sensors on the system to         |                          |   |
|                                 | On                                          |                          |   |
|                                 | ensure they are still signaling.            |                          |   |
| Supervision Timer (Partition 1) | Select the frequency of the sensor          | Disable                  |   |
|                                 | supervision check.                          |                          |   |
|                                 | 4 hours                                     |                          |   |
|                                 |                                             |                          |   |
|                                 |                                             | 5 hours                  |   |
|                                 |                                             |                          |   |
|                                 |                                             | 6 hours                  |   |
|                                 |                                             |                          |   |
|                                 |                                             | 8 hours                  |   |
|                                 |                                             |                          |   |
|                                 |                                             | 12 hours                 |   |
|                                 |                                             |                          |   |
|                                 |                                             | 2 hours                  |   |
|                                 |                                             |                          |   |
|                                 |                                             | 24 hours                 |   |
|                                 |                                             |                          |   |
| Supervision Timer (Partition 2) | Select the frequency of the sensor          | Disable                  |   |
|                                 | supervision check.                          |                          |   |
|                                 | 4 hours                                     |                          |   |
|                                 |                                             |                          |   |
|                                 |                                             | 5 hours                  |   |
|                                 |                                             |                          |   |
|                                 |                                             | 6 hours                  |   |
|                                 |                                             |                          |   |
|                                 |                                             | 8 hours                  |   |
|                                 |                                             |                          |   |
|                                 |                                             | 12 hours                 |   |
|                                 |                                             |                          |   |
|                                 |                                             | 2 hours                  |   |
|                                 |                                             |                          |   |
|                                 |                                             | 24 hours                 |   |
|                                 |                                             |                          |   |
| Alarm Length (Partition 1)      | Alarm Length – For UL compliant             | Disable (Not Allowed for |   |
|                                 | installations, this must be set to at least | UL Compliant             |   |
|                                 | 4 minutes.                                  | Installations)           |   |
|                                 |                                             | 2 minutes                |   |
|                                 |                                             |                          |   |
|                                 |                                             | 3 minutes                |   |
|                                 |                                             |                          |   |
|                                 |                                             | 4 minutes                |   |
|                                 |                                             |                          |   |
|                                 |                                             | 5 minutes                |   |
|                                 |                                             |                          |   |
|                                 |                                             | 6 minutes                |   |
|                                 |                                             |                          |   |
|                                 |                                             | 7 minutes                |   |
|                                 |                                             |                          |   |
|                                 |                                             | 8 minutes                |   |
|                                 |                                             |                          |   |
|                                 |                                             | 9 minutes                |   |
|                                 |                                             |                          |   |
|                                 |                                             | 1 minute                 |   |
|                                 |                                             |                          |   |
|                                 |                                             | 10 minutes               |   |
|                                 |                                             |                          |   |
|                                 |                                             | 11 minutes               |   |
|                                 |                                             |                          |   |
|                                 |                                             | 12 minutes               |   |

| Alarm.com Hybrid Installation Guide Version 7.0 Published 4/12/23 | 19 |
| ----------------------------------------------------------------- | -- |

|                                                                   |                                             | 13 minutes               |   |
| ----------------------------------------------------------------- | ------------------------------------------- | ------------------------ | - |
|                                                                   |                                             |                          |   |
|                                                                   |                                             | 14 minutes               |   |
|                                                                   |                                             |                          |   |
|                                                                   |                                             | 15 minutes               |   |
|                                                                   |                                             |                          |   |
| Alarm Length (Partition 2)                                        | Alarm Length – For UL compliant             | Disable (Not Allowed for |   |
|                                                                   | installations, this must be set to at least | UL Compliant             |   |
|                                                                   | 4 minutes.                                  | Installations)           |   |
|                                                                   |                                             | 2 minutes                |   |
|                                                                   |                                             |                          |   |
|                                                                   |                                             | 3 minutes                |   |
|                                                                   |                                             |                          |   |
|                                                                   |                                             | 4 minutes                |   |
|                                                                   |                                             |                          |   |
|                                                                   |                                             | 5 minutes                |   |
|                                                                   |                                             |                          |   |
|                                                                   |                                             | 6 minutes                |   |
|                                                                   |                                             |                          |   |
|                                                                   |                                             | 7 minutes                |   |
|                                                                   |                                             |                          |   |
|                                                                   |                                             | 8 minutes                |   |
|                                                                   |                                             |                          |   |
|                                                                   |                                             | 9 minutes                |   |
|                                                                   |                                             |                          |   |
|                                                                   |                                             | 1 minute                 |   |
|                                                                   |                                             |                          |   |
|                                                                   |                                             | 10 minutes               |   |
|                                                                   |                                             |                          |   |
|                                                                   |                                             | 11 minutes               |   |
|                                                                   |                                             |                          |   |
|                                                                   |                                             | 12 minutes               |   |
|                                                                   |                                             |                          |   |
|                                                                   |                                             | 13 minutes               |   |
|                                                                   |                                             |                          |   |
|                                                                   |                                             | 14 minutes               |   |
|                                                                   |                                             |                          |   |
|                                                                   |                                             | 15 minutes               |   |
|                                                                   |                                             |                          |   |
| Cross Zone Timer (Partition 1)                                    | Select the time window within which 2       | Disable                  |   |
|                                                                   | cross zones must be tripped to generate     |                          |   |
|                                                                   | 2 minutes                                   |                          |   |
|                                                                   | a verified alarm.                           |                          |   |
|                                                                   | 3 minutes                                   |                          |   |
|                                                                   |                                             |                          |   |
|                                                                   |                                             |                          |   |
|                                                                   |                                             | 4 minutes                |   |
|                                                                   |                                             |                          |   |
|                                                                   |                                             | 5 minutes                |   |
|                                                                   |                                             |                          |   |
|                                                                   |                                             | 6 minutes                |   |
|                                                                   |                                             |                          |   |
|                                                                   |                                             | 7 minutes                |   |
|                                                                   |                                             |                          |   |
|                                                                   |                                             | 8 minutes                |   |
|                                                                   |                                             |                          |   |
|                                                                   |                                             | 9 minutes                |   |
|                                                                   |                                             |                          |   |
|                                                                   |                                             | 1 minute                 |   |
|                                                                   |                                             |                          |   |
|                                                                   |                                             | 10 minutes               |   |
|                                                                   |                                             |                          |   |
|                                                                   |                                             | 11 minutes               |   |
|                                                                   |                                             |                          |   |
|                                                                   |                                             | 12 minutes               |   |
|                                                                   |                                             |                          |   |
|                                                                   |                                             | 13 minutes               |   |
|                                                                   |                                             |                          |   |
|                                                                   |                                             | 14 minutes               |   |
|                                                                   |                                             |                          |   |
|                                                                   |                                             | 15 minutes               |   |
|                                                                   |                                             |                          |   |
| Cross Zone Timer (Partition 2)                                    | Select the time window within which 2       | Disable                  |   |
|                                                                   | cross zones must be tripped to generate     |                          |   |
|                                                                   | 2 minutes                                   |                          |   |
|                                                                   | a verified alarm.                           |                          |   |
|                                                                   | 3 minutes                                   |                          |   |
|                                                                   |                                             |                          |   |
|                                                                   |                                             |                          |   |
|                                                                   |                                             | 4 minutes                |   |
|                                                                   |                                             |                          |   |
|                                                                   |                                             | 5 minutes                |   |
|                                                                   |                                             |                          |   |
| Alarm.com Hybrid Installation Guide Version 7.0 Published 4/12/23 | 20                                          |                          |   |

|                                    |                                        | 6 minutes  |   |
| ---------------------------------- | -------------------------------------- | ---------- | - |
|                                    |                                        |            |   |
|                                    |                                        | 7 minutes  |   |
|                                    |                                        |            |   |
|                                    |                                        | 8 minutes  |   |
|                                    |                                        |            |   |
|                                    |                                        | 9 minutes  |   |
|                                    |                                        |            |   |
|                                    |                                        | 1 minute   |   |
|                                    |                                        |            |   |
|                                    |                                        | 10 minutes |   |
|                                    |                                        |            |   |
|                                    |                                        | 11 minutes |   |
|                                    |                                        |            |   |
|                                    |                                        | 12 minutes |   |
|                                    |                                        |            |   |
|                                    |                                        | 13 minutes |   |
|                                    |                                        |            |   |
|                                    |                                        | 14 minutes |   |
|                                    |                                        |            |   |
|                                    |                                        | 15 minutes |   |
|                                    |                                        |            |   |
| Fire Verification Timer (Partition | Select the time window within which    | Disable    |   |
| 1)                                 | verified fire zones must be tripped to |            |   |
| 2 minutes                          |                                        |            |   |
|                                    | generate a verified alarm.             |            |   |
|                                    | 3 minutes                              |            |   |
|                                    |                                        |            |   |
|                                    |                                        |            |   |
|                                    |                                        | 4 minutes  |   |
|                                    |                                        |            |   |
|                                    |                                        | 5 minutes  |   |
|                                    |                                        |            |   |
|                                    |                                        | 6 minutes  |   |
|                                    |                                        |            |   |
|                                    |                                        | 7 minutes  |   |
|                                    |                                        |            |   |
|                                    |                                        | 8 minutes  |   |
|                                    |                                        |            |   |
|                                    |                                        | 9 minutes  |   |
|                                    |                                        |            |   |
|                                    |                                        | 1 minute   |   |
|                                    |                                        |            |   |
|                                    |                                        | 10 minutes |   |
|                                    |                                        |            |   |
|                                    |                                        | 11 minutes |   |
|                                    |                                        |            |   |
|                                    |                                        | 12 minutes |   |
|                                    |                                        |            |   |
|                                    |                                        | 13 minutes |   |
|                                    |                                        |            |   |
|                                    |                                        | 14 minutes |   |
|                                    |                                        |            |   |
|                                    |                                        | 15 minutes |   |
|                                    |                                        |            |   |
| Fire Verification Timer (Partition | Select the time window within which    | Disable    |   |
| 2)                                 | verified fire zones must be tripped to |            |   |
| 2 minutes                          |                                        |            |   |
|                                    | generate a verified alarm.             |            |   |
|                                    | 3 minutes                              |            |   |
|                                    |                                        |            |   |
|                                    |                                        |            |   |
|                                    |                                        | 4 minutes  |   |
|                                    |                                        |            |   |
|                                    |                                        | 5 minutes  |   |
|                                    |                                        |            |   |
|                                    |                                        | 6 minutes  |   |
|                                    |                                        |            |   |
|                                    |                                        | 7 minutes  |   |
|                                    |                                        |            |   |
|                                    |                                        | 8 minutes  |   |
|                                    |                                        |            |   |
|                                    |                                        | 9 minutes  |   |
|                                    |                                        |            |   |
|                                    |                                        | 1 minute   |   |
|                                    |                                        |            |   |
|                                    |                                        | 10 minutes |   |
|                                    |                                        |            |   |
|                                    |                                        | 11 minutes |   |
|                                    |                                        |            |   |
|                                    |                                        | 12 minutes |   |
|                                    |                                        |            |   |
|                                    |                                        | 13 minutes |   |

| Alarm.com Hybrid Installation Guide Version 7.0 Published 4/12/23 | 21 |
| ----------------------------------------------------------------- | -- |

|                                |                                          | 14 minutes |   |
| ------------------------------ | ---------------------------------------- | ---------- | - |
|                                |                                          |            |   |
|                                |                                          | 15 minutes |   |
|                                |                                          |            |   |
| Entry Delay Sound for Arm Away | Entry Delay Sound Volume for Arm         | High       |   |
| (Partition 1)                  | Away                                     |            |   |
| Off                            |                                          |            |   |
|                                |                                          |            |   |
|                                |                                          | Low        |   |
|                                |                                          |            |   |
| Entry Delay Sound for Arm Away | Entry Delay Sound Volume for Arm         | High       |   |
| (Partition 2)                  | Away                                     |            |   |
| Off                            |                                          |            |   |
|                                |                                          |            |   |
|                                |                                          | Low        |   |
|                                |                                          |            |   |
| Exit Delay Sound for Arm Away  | Exit Delay Sound Volume for Arm Away     | High       |   |
| (Partition 1)                  |                                          |            |   |
|                                | Off                                      |            |   |
|                                |                                          |            |   |
|                                |                                          | Low        |   |
|                                |                                          |            |   |
| Exit Delay Sound for Arm Away  | Exit Delay Sound Volume for Arm Away     | High       |   |
| (Partition 2)                  |                                          |            |   |
|                                | Off                                      |            |   |
|                                |                                          |            |   |
|                                |                                          | Low        |   |
|                                |                                          |            |   |
| Entry Delay Sound for Arm Stay | Entry Delay Sound Volume for Arm Stay    | High       |   |
| (Partition 1)                  |                                          |            |   |
|                                | Off                                      |            |   |
|                                |                                          |            |   |
|                                |                                          | Low        |   |
|                                |                                          |            |   |
| Entry Delay Sound for Arm Stay | Entry Delay Sound Volume for Arm Stay    | High       |   |
| (Partition 2)                  |                                          |            |   |
|                                | Off                                      |            |   |
|                                |                                          |            |   |
|                                |                                          | Low        |   |
|                                |                                          |            |   |
| Exit Delay Sound for Arm Stay  | Exit Delay Sound Volume for Arm Stay     | High       |   |
| (Partition 1)                  |                                          |            |   |
|                                | Off                                      |            |   |
|                                |                                          |            |   |
|                                |                                          | Low        |   |
|                                |                                          |            |   |
| Exit Delay Sound for Arm Stay  | Exit Delay Sound Volume for Arm Stay     | High       |   |
| (Partition 2)                  |                                          |            |   |
|                                | Off                                      |            |   |
|                                |                                          |            |   |
|                                |                                          | Low        |   |
|                                |                                          |            |   |
| Entry/Exit Only Final Beeps    | When selected, the Entry/Exit beeps will | Disable    |   |
| (Partition 1)                  | only sound for the last 3-10 seconds of  |            |   |
| 10 seconds                     |                                          |            |   |
|                                | Entry/Exit Delay.                        |            |   |
|                                | 3 seconds                                |            |   |
|                                |                                          |            |   |
|                                |                                          |            |   |
|                                |                                          | 4 seconds  |   |
|                                |                                          |            |   |
|                                |                                          | 5 seconds  |   |
|                                |                                          |            |   |
|                                |                                          | 6 seconds  |   |
|                                |                                          |            |   |
|                                |                                          | 7 seconds  |   |
|                                |                                          |            |   |
|                                |                                          | 8 seconds  |   |
|                                |                                          |            |   |
|                                |                                          | 9 seconds  |   |
|                                |                                          |            |   |
| Entry/Exit Only Final Beeps    | When selected, the Entry/Exit beeps will | Disable    |   |
| (Partition 2)                  | only sound for the last 3-10 seconds of  |            |   |
| 10 seconds                     |                                          |            |   |
|                                | Entry/Exit Delay.                        |            |   |
|                                | 3 seconds                                |            |   |
|                                |                                          |            |   |
|                                |                                          |            |   |
|                                |                                          | 4 seconds  |   |
|                                |                                          |            |   |
|                                |                                          | 5 seconds  |   |
|                                |                                          |            |   |
|                                |                                          | 6 seconds  |   |

| Alarm.com Hybrid Installation Guide Version 7.0 Published 4/12/23 | 22 |
| ----------------------------------------------------------------- | -- |

|                                                                   |                                            | 7 seconds      |   |
| ----------------------------------------------------------------- | ------------------------------------------ | -------------- | - |
|                                                                   |                                            |                |   |
|                                                                   |                                            | 8 seconds      |   |
|                                                                   |                                            |                |   |
|                                                                   |                                            | 9 seconds      |   |
|                                                                   |                                            |                |   |
| Swinger Shutdown                                                  | Swinger Shutdown. When set to 0,           | 0–255          |   |
|                                                                   | setting is off.                            | Default: 0     |   |
| Ethernet Bypass                                                   | Ethernet Bypass. When enabled, the         | Disable        |   |
|                                                                   | Ethernet cable being unplugged will not    |                |   |
|                                                                   | Enable                                     |                |   |
|                                                                   | cause a fault at the panel.                |                |   |
| Access Code Digits                                                | Set user access codes to be 4 or 6 digits. | 4 Digits       |   |
|                                                                   |                                            |                |   |
|                                                                   |                                            | 6 Digits       |   |
|                                                                   |                                            |                |   |
| PIR Camera Image Resolution                                       | Choose what resolution your PIR            | 3xqVGA         |   |
|                                                                   | Camera images are uploaded at as well      |                |   |
|                                                                   | 1xqVGA                                     |                |   |
|                                                                   | as how many images are uploaded            |                |   |
|                                                                   | 1xVGA                                      |                |   |
|                                                                   | automatically during alarm.                |                |   |
|                                                                   |                                            |                |   |
| External Siren Tamper Sound                                       | Choose whether an external siren           | Off            |   |
|                                                                   | learned into the control panel sounds      |                |   |
|                                                                   | On                                         |                |   |
|                                                                   | when it is physically tampered.            |                |   |
|                                                                   | Recommended if performing                  |                |   |
|                                                                   | maintenance on the device. Note: This      |                |   |
|                                                                   | setting is download only.                  |                |   |
| External Siren Confirmation                                       | Choose whether an external siren           | Off            |   |
| Sound                                                             | sounds a confirmation beep to indicate a   |                |   |
| On                                                                |                                            |                |   |
|                                                                   | change in arming state. Note: This         |                |   |
|                                                                   | setting is download only and may           |                |   |
|                                                                   | change due to Silent Arming selection.     |                |   |
| External Siren Entry/Exit Sound                                   | Choose whether an external siren           | Off            |   |
|                                                                   | sounds during entry or exit delay. Note:   |                |   |
|                                                                   | On                                         |                |   |
|                                                                   | This setting is download only and may      |                |   |
|                                                                   | change due to Silent Arming selection.     |                |   |
| RF Replay                                                         | Enable/Disable RF Replay attacks           | Enable/Disable |   |
|                                                                   | protection                                 |                |   |
|                                                                   |                                            |                |   |
| Duress Code                                                       | Enable/Disable duress code                 | Enable/Disable |   |
|                                                                   |                                            |                |   |
| Mute Internal Panel Siren                                         | This allows the panel internal siren to    | Enable/Disable |   |
|                                                                   | be turned off. It is recommended to        |                |   |
|                                                                   | have an external siren associated with     |                |   |
|                                                                   | the system before doing this. Enabled      |                |   |
|                                                                   | = siren is muted. Disabled = Siren is      |                |   |
|                                                                   | not muted. Default value: Disabled.        |                |   |
|                                                                   |                                            |                |   |
| Ignore Sensor Tampers                                             | Enabling this will have the panel          | Enable/Disable |   |
|                                                                   | ignore sensor tampers that are             |                |   |
|                                                                   | registered from the field. This is a       |                |   |
|                                                                   | panel-wide setting and will ignore         |                |   |
|                                                                   | sensor tampers on both Partition 1         |                |   |
| Alarm.com Hybrid Installation Guide Version 7.0 Published 4/12/23 | 23                                         |                |   |

|                          | and Partition 2 if enabled.           |                    |
| ------------------------ | ------------------------------------- | ------------------ |
|                          |                                       |                    |
| External Antenna Tamper  | Determines whether the tamper from    | Enabled/Disable    |
|                          | an external antenna is enabled or     |                    |
|                          | disabled.                             |                    |
|                          |                                       |                    |
| Panic Supervision\*      | Enabling this will have cause panic   | Enable/Disable     |
|                          | devices to send supervision signals   |                    |
|                          | and log a malfunction if it hasn’t    |                    |
|                          | communicated with the panel           |                    |
| Temperature Units (TSP-3 | This changes the temperature units    | Celsius/Fahrenheit |
| only)                    | that are displayed on TSP-3s that are |                    |
|                          | assoicated with the system. This does |                    |
|                          | not change the units that are         |                    |
|                          | displayed on the customer site or     |                    |
|                          | mobile app.                           |                    |

\*Only available on certain firmware updates. For best results, please ensure your panel is on the most up to date firmware.

Appendix D: Sensor Group Configuration

**Eligible Arming States:**

**Disarm:** Lowest level of security, the panel is not armed.

**Arm Stay:** The system is partially armed, certain zones, such as those inside of the protected premises, are not armed as it is expected they may be tripped while the system is Armed Stay.

**Arm Away:** Highest level of security, all zones that generate an alarm and report to the Central Monitoring Station are armed.

**24-Hour Zones:** These zones are always armed and will generate an alarm regardless of the arming state of the panel.

**Sensor Groups by Physical Sensor Type:**

**Contact:**

| **Group**  | **Short Description**                                            | **Long Description**                                               |   |
| ---------- | ---------------------------------------------------------------- | ------------------------------------------------------------------ | - |
|            |                                                                  | 24-Hour instant burglar alarm, always armed, meant to guard        |   |
| 8          | 24 Hour Burglar                                                  | special belongings such as a gun cabinet or safe. Siren will sound |   |
|            |                                                                  | and alarm will transmit regardless of arming state.                |   |
|            | Standard Delay                                                   | An Entry/Exit zone that will begin Entry Delay when tripped        |   |
| 10         | while the system is armed in stay or away mode. If the system is |                                                                    |   |
| Entry/Exit |                                                                  |                                                                    |   |
|            | not disarmed by the end of Entry Delay, an Alarm will sound.     |                                                                    |   |
|            |                                                                  |                                                                    |   |

| Alarm.com Hybrid Installation Guide Version 7.0 Published 4/12/23 | 24 |
| ----------------------------------------------------------------- | -- |

|                                                                | Extended Delay                                                     | An Entry/Exit zone that will begin Extended Entry Delay when       |   |
| -------------------------------------------------------------- | ------------------------------------------------------------------ | ------------------------------------------------------------------ | - |
| 11                                                             | tripped while the system is armed. If the system is not disarmed   |                                                                    |   |
| Entry/Exit                                                     |                                                                    |                                                                    |   |
|                                                                | by the end of Entry Delay, an Alarm will sound.                    |                                                                    |   |
|                                                                |                                                                    |                                                                    |   |
| 13                                                             | Instant Perimeter                                                  | Exterior zones, instant audible alarm during arm stay and arm      |   |
| away. Siren will sound.                                        |                                                                    |                                                                    |   |
|                                                                |                                                                    |                                                                    |   |
| 14                                                             | Interior                                                           | Interior zones, instant audible alarm during arm stay and arm      |   |
| Stay/Away                                                      | away. Siren will sound/                                            |                                                                    |   |
|                                                                |                                                                    |                                                                    |   |
|                                                                |                                                                    | Interior zone, armed in Away mode Only, not armed in stay          |   |
| 16                                                             | Interior Away                                                      | mode. Meant for interior doors that are used during arm stay.      |   |
|                                                                |                                                                    | Siren will sound.                                                  |   |
|                                                                |                                                                    | Meant for zones subject to false alarms or for Monitoring Stations |   |
|                                                                | Sensor with Cross                                                  | that require verified alarms. Tripping one sensor with cross zone  |   |
| 18                                                             | verification activates the siren and reports as a trouble, while   |                                                                    |   |
| Zone Verification                                              |                                                                    |                                                                    |   |
|                                                                | tripping a second sensor with Cross Zone verification reports a    |                                                                    |   |
|                                                                |                                                                    |                                                                    |   |
|                                                                |                                                                    | Verified alarm to the Monitoring Station. Armed in Away only       |   |
|                                                                |                                                                    | Interior zone that starts Entry Delay when tripped. Generates an   |   |
| 19                                                             | Interior Delay                                                     | audible alarm at the end of Entry Delay if system is not disarmed. |   |
|                                                                |                                                                    | Armed in Away mode, not armed in stay mode.                        |   |
| 25                                                             | Chime Only                                                         | No Alarm Report. Tripping sensor causes an audible chine at the    |   |
| panel regardless of arm state                                  |                                                                    |                                                                    |   |
|                                                                |                                                                    |                                                                    |   |
|                                                                | Voice Chime                                                        | No Alarm Report. Tripping sensor causes an audible voice           |   |
| 31                                                             | announcement at the panel regardless of arm state. Only eligible   |                                                                    |   |
| Only                                                           |                                                                    |                                                                    |   |
|                                                                | on specific hardware                                               |                                                                    |   |
|                                                                |                                                                    |                                                                    |   |
|                                                                |                                                                    | 24-Hour instant tamper alert, always armed, meant to guard         |   |
| 36                                                             | 24-Hour Tamper                                                     | special belongings such as a gun cabinet or safe. When tripped,    |   |
| transmits a tamper to the Monitoring Station regardless of arm |                                                                    |                                                                    |   |
|                                                                |                                                                    |                                                                    |   |
|                                                                |                                                                    | state. Siren will not sound.                                       |   |
|                                                                |                                                                    |                                                                    |   |
| 40\*                                                           | Non-Reporting                                                      | Used for Occupancy sensors or other zones without a Central        |   |
| Zone                                                           | Station Report                                                     |                                                                    |   |
|                                                                |                                                                    |                                                                    |   |
|                                                                |                                                                    |                                                                    |   |
|                                                                | 24-hours silent                                                    | Used for special circumstances when a silent auxiliary panic       |   |
| 60                                                             | needs to be registered using a contact regardless of arming state. |                                                                    |   |
| alarm                                                          |                                                                    |                                                                    |   |
|                                                                | Use case: to be used with a wired panic button wired into the DC-  |                                                                    |   |
|                                                                |                                                                    |                                                                    |   |
|                                                                |                                                                    | 23. Alarm will sound                                               |   |
|                                                                |                                                                    | Meant for zones subject to false alarms or for Monitoring Stations |   |
|                                                                |                                                                    | that require verified alarms.                                      |   |
|                                                                | Sensor with Cross                                                  | Tripping one sensor with cross zone verification activates the     |   |
| 67                                                             | siren and reports an unverified alarm, while tripping a second     |                                                                    |   |
| Zone verification                                              |                                                                    |                                                                    |   |
|                                                                | sensor with Cross Zone verification reports a Verified alarm to    |                                                                    |   |
|                                                                |                                                                    |                                                                    |   |
|                                                                |                                                                    | the Monitoring Station.                                            |   |
|                                                                |                                                                    | Armed in Stay and Away.                                            |   |
|                                                                |                                                                    |                                                                    |   |
| **Motion:**                                                    |                                                                    |                                                                    |   |

| Alarm.com Hybrid Installation Guide Version 7.0 Published 4/12/23 | 25 |
| ----------------------------------------------------------------- | -- |

| **Group**                                                                  | **Short Description**                                                  | **Long Description**                                                         |   |
| -------------------------------------------------------------------------- | ---------------------------------------------------------------------- | ---------------------------------------------------------------------------- | - |
| 13                                                                         | Instant Perimeter                                                      | Exterior zones, instant audible alarm during arm stay and arm                |   |
| away. Siren will sound.                                                    |                                                                        |                                                                              |   |
|                                                                            |                                                                        |                                                                              |   |
|                                                                            |                                                                        |                                                                              |   |
|                                                                            |                                                                        | Interior follower, armed in stay and away, initiates an audible alarm if     |   |
| 15                                                                         | Interior Follower                                                      | an entry/exit zone (ex: front door) is not tripped first. If Entry/Exit Zone |   |
| is tripped, will not generate an alarm until the end of Entry Delay. Siren |                                                                        |                                                                              |   |
|                                                                            |                                                                        |                                                                              |   |
|                                                                            |                                                                        | will sound.                                                                  |   |
|                                                                            |                                                                        |                                                                              |   |
|                                                                            |                                                                        | Interior follower, when armed away initiates an audible alarm if an          |   |
| 17                                                                         | Interior Stay                                                          | entry/exit zone (ex: front door) is not tripped first. If Entry/Exit Zone is |   |
|                                                                            | Follower                                                               | tripped, will not generate an alarm until the end of Entry Delay. No         |   |
|                                                                            |                                                                        | response during arm Stay. Siren will sound.                                  |   |
|                                                                            |                                                                        |                                                                              |   |
|                                                                            |                                                                        | Meant for zones subject to false alarms or for Monitoring Stations           |   |
|                                                                            | Sensor with Cross                                                      | that require verified alarms. Tripping one sensor with cross zone            |   |
| 18                                                                         | verification activates the siren and reports as a trouble, while       |                                                                              |   |
| Zone Verification                                                          |                                                                        |                                                                              |   |
|                                                                            | tripping a second sensor with Cross Zone verification reports a        |                                                                              |   |
|                                                                            |                                                                        |                                                                              |   |
|                                                                            |                                                                        | Verified alarm to the Monitoring Station. Armed in Away only                 |   |
|                                                                            |                                                                        |                                                                              |   |
|                                                                            |                                                                        | Interior zone that starts Entry Delay when tripped. Generates an             |   |
| 20                                                                         | Interior Delay                                                         | audible alarm at the end of Entry Delay if system is not disarmed.           |   |
|                                                                            |                                                                        | Armed in Away mode, not armed in Stay mode.                                  |   |
|                                                                            |                                                                        |                                                                              |   |
| 25                                                                         | Motion-Chime Only                                                      | No Alarm Report. Tripping sensor causes an audible chime at the panel        |   |
| regardless of arm state.                                                   |                                                                        |                                                                              |   |
|                                                                            |                                                                        |                                                                              |   |
|                                                                            |                                                                        |                                                                              |   |
|                                                                            |                                                                        | No Alarm Report. Tripping sensor causes an audible voice                     |   |
| 31                                                                         | Voice Chime Only                                                       | announcement at the panel regardless of arm state. Only eligible on          |   |
|                                                                            |                                                                        | specific hardware                                                            |   |
|                                                                            |                                                                        |                                                                              |   |
| 40\*                                                                       | Non-Reporting                                                          | Used for Occupancy sensors or other zones without a Central                  |   |
| Zone                                                                       | Station Report                                                         |                                                                              |   |
|                                                                            |                                                                        |                                                                              |   |
|                                                                            |                                                                        |                                                                              |   |
|                                                                            |                                                                        | Interior sensors, activate Entry Delay when tripped in arm stay and arm      |   |
| 50                                                                         | Delay Stay/Away                                                        | away. If the system is not disarmed by the end of Entry Delay, an Alarm      |   |
|                                                                            |                                                                        | will sound. Siren will sound.                                                |   |
|                                                                            |                                                                        |                                                                              |   |
|                                                                            |                                                                        | Meant for zones subject to false alarms or for Monitoring Stations that      |   |
|                                                                            |                                                                        | require verified alarms.                                                     |   |
| 67                                                                         | Sensor with Cross                                                      | Tripping one sensor with cross zone verification activates the siren and     |   |
| Zone verification                                                          | reports an unverified alarm, while tripping a second sensor with Cross |                                                                              |   |
|                                                                            |                                                                        | Zone verification reports a Verified alarm to the Monitoring Station.        |   |
|                                                                            |                                                                        | Armed in Stay and Away.                                                      |   |
|                                                                            |                                                                        |                                                                              |   |

| Alarm.com Hybrid Installation Guide Version 7.0 Published 4/12/23 | 26 |
| ----------------------------------------------------------------- | -- |

**Glassbreak:**

| **Group**        |                   | **Short Description**                                                     | **Long Description**                                                     |   |
| ---------------- | ----------------- | ------------------------------------------------------------------------- | ------------------------------------------------------------------------ | - |
|                  |                   |                                                                           | 24-Hour instant burglar alarm, always armed, meant to guard special      |   |
| 8                |                   | 24 Hour Burglar                                                           | belongings such as a gun cabinet or safe. Siren will sound and alarm     |   |
|                  |                   |                                                                           | will transmit regardless of arming state.                                |   |
|                  |                   |                                                                           |                                                                          |   |
| 13               |                   | Instant Perimeter                                                         | Exterior zones, instant audible alarm during arm stay and arm away.      |   |
|                  | Siren will sound. |                                                                           |                                                                          |   |
|                  |                   |                                                                           |                                                                          |   |
|                  |                   |                                                                           |                                                                          |   |
|                  |                   |                                                                           | Interior zone, armed in Away mode Only, not armed in stay mode.          |   |
|                  |                   |                                                                           | Meant for interior doors that are used during arm stay. Siren will       |   |
| 16               |                   | Interior Away                                                             | sound.                                                                   |   |
|                  |                   |                                                                           |                                                                          |   |
|                  |                   |                                                                           | When triggered, this causes an instant alarm.                            |   |
|                  |                   |                                                                           |                                                                          |   |
|                  |                   |                                                                           | Meant for zones subject to false alarms or for Monitoring Stations that  |   |
|                  |                   | Sensor with Cross                                                         | require verified alarms. Tripping one sensor with cross zone             |   |
| 18               |                   | verification activates the siren and reports as a trouble, while tripping |                                                                          |   |
|                  | Zone Verification |                                                                           |                                                                          |   |
|                  |                   |                                                                           | a second sensor with Cross Zone verification reports a Verified alarm    |   |
|                  |                   |                                                                           | to the Monitoring Station. Armed away mode Only.                         |   |
|                  |                   |                                                                           |                                                                          |   |
| 40\*             |                   | Non-Reporting                                                             | Used for Occupancy sensors or other zones without a Central Station      |   |
|                  | Zone              | Report                                                                    |                                                                          |   |
|                  |                   |                                                                           |                                                                          |   |
|                  |                   |                                                                           | Meant for zones subject to false alarms or for Monitoring Stations that  |   |
|                  |                   |                                                                           | require verified alarms.                                                 |   |
| 67               |                   | Sensor with Cross                                                         | Tripping one sensor with cross zone verification activates the siren and |   |
|                  | Zone verification | reports an unverified alarm, while tripping a second sensor with Cross    |                                                                          |   |
|                  |                   |                                                                           | Zone verification reports a Verified alarm to the Monitoring Station.    |   |
|                  |                   |                                                                           | Armed in Stay and Away.                                                  |   |
|                  |                   |                                                                           |                                                                          |   |
| **Life Safety:** |                   |                                                                           |                                                                          |   |
|                  |                   |                                                                           |                                                                          |   |
| **Group**        |                   | **Short Description**                                                     | **Long Description**                                                     |   |
| 34               |                   | 24-Hour Carbon                                                            | Carbon Monoxide gas detectors, instant alarm, always armed.              |   |
|                  |                   | Monoxide                                                                  | Generates audible CO alarm when tripped.                                 |   |
|                  |                   |                                                                           |                                                                          |   |
|                  |                   |                                                                           | 24-Hour fire, rate-of-rise heat, and smoke sensors, instant alarm,       |   |
| 26               |                   | 24-Hour Fire                                                              | always armed. Tripping sensor generates an audible fire alarm            |   |
|                  |                   |                                                                           | regardless of arming state.                                              |   |
|                  |                   |                                                                           |                                                                          |   |

| Alarm.com Hybrid Installation Guide Version 7.0 Published 4/12/23 | 27 |
| ----------------------------------------------------------------- | -- |

|                             | 24-Hour Fire with                                                       | 24-Hour fire with verification, requires a second sensor to validate the |   |
| --------------------------- | ----------------------------------------------------------------------- | ------------------------------------------------------------------------ | - |
| 61                          | fire smoke or heat rise sensor, instant alarm, always armed. Siren will |                                                                          |   |
| Verification                |                                                                         |                                                                          |   |
|                             |                                                                         | sound.                                                                   |   |
|                             |                                                                         |                                                                          |   |
| 79\*                        | 24-Hour Silent Fire                                                     | 24-Hour fire, rate-of-rise heat, and smoke sensors, instant alarm        |   |
| without siren, always armed |                                                                         |                                                                          |   |
|                             |                                                                         |                                                                          |   |
|                             |                                                                         |                                                                          |   |
|                             |                                                                         | 24-Hour auxiliary Water Sensors. Generates an audible Water Alarm        |   |
| 38                          | 24-Hour Water                                                           | when tripped regardless of arming state. Siren will sound and device     |   |
|                             |                                                                         | will beep (if device has internal sounder).                              |   |
|                             |                                                                         |                                                                          |   |
|                             |                                                                         | 24 Hour Auxiliary freeze or water sensors, Generates an audible Water    |   |
| 91\*                        | 24-Hour Silent                                                          | Alarm when tripped regardless of arming state. Alarm with no siren,      |   |
| Freeze/Water                | device will issue trouble beeps when tripped if device has internal     |                                                                          |   |
|                             |                                                                         |                                                                          |   |
|                             |                                                                         | sounder.                                                                 |   |
|                             |                                                                         |                                                                          |   |
| 40\*                        | Non-Reporting                                                           | Used for Occupancy sensors or other zones without a Central Station      |   |
| Zone                        | Report                                                                  |                                                                          |   |
|                             |                                                                         |                                                                          |   |
|                             |                                                                         |                                                                          |   |
|                             |                                                                         | 24-Hour Auxiliary freeze sensors. Generates a Freeze Alarm when          |   |
|                             |                                                                         | tripped regardless of arming state.                                      |   |
| 52                          | 24-Hour Freeze                                                          | Alarm with no siren, device will issue trouble beeps when tripped if     |   |
|                             |                                                                         | device has internal sounder.                                             |   |
|                             |                                                                         | When triggered, this causes an instant alarm.                            |   |
|                             |                                                                         |                                                                          |   |
| **Keypad:**                 |                                                                         |                                                                          |   |
|                             |                                                                         |                                                                          |   |
| **Group**                   | **Short Description**                                                   | **Long Description**                                                     |   |
| 0                           | 24-Hour Fixed Panic                                                     | When the panel is armed away, tampering the keypad will cause an         |   |
|                             |                                                                         | audible panic alarm. Siren will sound.                                   |   |
|                             |                                                                         |                                                                          |   |
| 2                           | 24-Hour Silent                                                          | When the panel is armed away, tampering the keypad will cause a          |   |
| Fixed Panic                 | silent panic alarm. Siren will not sound.                               |                                                                          |   |
|                             |                                                                         |                                                                          |   |
| 4                           | 24-Hour Fixed                                                           | When the panel is armed away, tampering the keypad will cause an         |   |
| Auxiliary                   | audible Medical panic. Siren will sound.                                |                                                                          |   |
|                             |                                                                         |                                                                          |   |
| **Keyfob:**                 |                                                                         |                                                                          |   |
|                             |                                                                         |                                                                          |   |
| **Group**                   | **Short Description**                                                   | **Long Description**                                                     |   |
| 1                           | 24-Hour Portable                                                        | When the panic button is triggered, an audible panic alarm will occur    |   |
|                             | Panic                                                                   | regardless of arm state. Siren will sound.                               |   |
|                             |                                                                         |                                                                          |   |

| Alarm.com Hybrid Installation Guide Version 7.0 Published 4/12/23 | 28 |
| ----------------------------------------------------------------- | -- |

| 3              | 24-Hour Silent                                        | When the panic button is triggered, a silent panic alarm will occur |   |
| -------------- | ----------------------------------------------------- | ------------------------------------------------------------------- | - |
| Portable Panic | regardless of arm state. Siren will not sound.        |                                                                     |   |
|                |                                                       |                                                                     |   |
| 6              | 24-Hour Portable                                      | When the panic button is triggered, an audible medical panic alarm  |   |
| Auxiliary      | will occur regardless of arm state. Siren will sound. |                                                                     |   |
|                |                                                       |                                                                     |   |
| **Misc.:**     |                                                       |                                                                     |   |
|                |                                                       |                                                                     |   |
| **Group**      | **Short Description**                                 | **Long Description**                                                |   |
| 72\*           | Security Sensor                                       | Auxiliary: Device Repeater used to extend range                     |   |
| Repeater       |                                                       |                                                                     |   |
|                |                                                       |                                                                     |   |
|                |                                                       |                                                                     |   |
| 33             | Siren                                                 | Wireless Siren.                                                     |   |
|                |                                                       |                                                                     |   |
| 30             |                                                       | Used to denote a device that is not recognized or supported.        |   |
|                |                                                       |                                                                     |   |
| 40\*           | Non-Reporting                                         | Used for Occupancy sensors or other zones without a Central Station |   |
| Zone           | Report.                                               |                                                                     |   |
|                |                                                       |                                                                     |   |

\*Not available on certain firmware versions. For best results, please update to the latest firmware version.

Appendix E: CID Reporting Codes

| **CS Event**                                                      | **SIA Code** | **CID Code** |   |
| ----------------------------------------------------------------- | ------------ | ------------ | - |
| **Description**                                                   |              |              |   |
| Sensor Low Battery                                                | XT           | 1384         |   |
| Sensor Low Battery                                                | XR           | 3384         |   |
| Restore                                                           |              |              |   |
| Sensor Tamper Alarm                                               | TA           | 1383         |   |
| Sensor Tamper Restore                                             | TR           | 3383         |   |
| AC Power Fail Restore                                             | AR           | 3301         |   |
| AC Power Fail                                                     | AT           | 1301         |   |
| Closing Report                                                    | CL           | 3401         |   |
| Closing Report                                                    | CL           | 3403         |   |
| Recent Closing                                                    | CR           | 1459         |   |
| Exit Alarm                                                        | EE           | 1457         |   |
| Bus Supervisories                                                 | NULL         | NULL         |   |
| Fire Panic                                                        | FA           | 1110         |   |
| Fire Panic Cancel                                                 | FH           | 3110         |   |
| Duress Alarm                                                      | HA           | 1121         |   |
| Touchpad Tamper -                                                 | JA           | 1137         |   |
| Keystroke                                                         |              |              |   |
| Touchpad Tamper Restore                                           | NULL         | 3137         |   |
| Alarm.com Hybrid Installation Guide Version 7.0 Published 4/12/23 | 29           |              |   |

| Panel Programming          | LB | 1627 |
| -------------------------- | -- | ---- |
| Phone Failure Restore      | LR | 3350 |
| Phone Failure              | LT | 1350 |
| Auxiliary Panic            | MA | 1100 |
| Auxiliary Panic Cancel     | MH | 3100 |
| No Activity Alarm          | NA | 1102 |
| No Activity Restore        | NS | 3102 |
| Cancel Report              | OC | 1406 |
| Opening Report             | OP | 1401 |
| Opening Report             | OP | 1403 |
| Police Panic               | PA | 1120 |
| Police Panic Cancel        | PH | 3120 |
| Receiver Failure           | XS | 1355 |
| CPU Low Battery - Restoral | YR | 3302 |
| CPU Low Battery            | YT | 1302 |
| Freeze - ESM Module        | ZA | 1159 |
| Freeze - ESM Module        | ZH | 3159 |
| Restore                    |    |      |
| Panel Tamper               | TA | 1137 |
| Manual Phone Test          | RX | 1601 |
| Auto-Phone Test            | RP | 1602 |
| Cellular Backup Failure    | YC | 1356 |
| Cellular Backup Restore    | YK | 3356 |
| Sensor Test Start          | TS | 1607 |
| Sensor Test End            | TE | 3607 |
| Receiver Jammed            | XQ | 1355 |
| Suspected Entry Delay      | UZ | 1777 |
| Alarm (Possible Crash &    |    |      |
| Smash)                     |    |      |
| Two Trip Error             | XM | 3138 |
| Silent Police Panic        | HA | 1122 |
| Silent Police Panic Cancel | HH | 3122 |

Appendix F: Panel Factory Reset

1. Disconnect AC adapter, slide battery switch to Off.
2. Press and hold the Learn button and connect AC adapter to the panel. All LEDs will turn on for 10 seconds.
3. Keep holding the Reset button for 30 seconds then release. After 10 seconds, the panel will restart and all LEDs will turn ON.
4. Wait for 10 seconds and all LEDs will turn OFF to indicate factory reset is complete.

Appendix G: Sensor Enrollment Instructions

| Alarm.com Hybrid Installation Guide Version 7.0 Published 4/12/23 | 30 |
| ----------------------------------------------------------------- | -- |

Prior to enrollment, put control panel into Sensor Learn Mode. For more detailed instructions and diagrams, please see device installation manuals.

**Keypad:**

While in normal operation mode, press and hold \* & # at the same time for 1 second. The keypad will emit a long beep to indicate it sent the enroll signal to the control panel.

Alternatively:

1. Put keypad into test mode:
2. Press \*.
3. Enter the default PIN 0000.
4. Press \* and then 7, the keypad will emit a long beep to indicate it sent the enroll signal to the control panel.
5. Exit test mode by pressing the disarm key twice.

**Keyfob:**

Press any button on the keyfob once.

**Contact, PIR, Shock, Glassbreak:**

Press the “Test” button on the device. If unsure which button is the “Test” button, please refer to the sensor diagram in the installation manual.

**Siren:**

Please refer to the siren installation guide for information on how to send the enroll signal from the siren. To put a siren into partition 2, the siren must first be enrolled into partition 1. Then, move the siren to partition 2 using AirFX or MobileTech and ensure command is acknowledged by the panel by checking the Event History. Once the command is acknowledged, follow the instructions to send the enroll signal from the siren a second time to complete the move to partition 2. If this step is not followed, the siren will not function properly.

| Alarm.com Hybrid Installation Guide Version 7.0 Published 4/12/23 | 31 |
| ----------------------------------------------------------------- | -- |
