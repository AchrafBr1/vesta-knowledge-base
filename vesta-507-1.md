# VESTA-507

SD-32 BUS

## Wired Smoke Detector&#x20;

<figure><img src=".gitbook/assets/image (1325).png" alt="" width="375"><figcaption></figcaption></figure>

## Introduction

SD-32-BUS is a Wired Smoke Detector designed to protect you against potential fire hazards. It uses multi criteria sensor technology for detecting between fast burning flames and slow smoldering fires, while at the same time includes intelligent technology to differentiate between cooking smoke and actual life-threatening house-fire emergencies, virtually eliminating nuisance alarms.

The Wired Smoke Detector can also be interconnected with other smoke detectors in the alarm system and raises alarms when any Smoke Detector in the system is triggered.

## Parts Identification

![](<.gitbook/assets/Unknown image (494)>)

#### **1 LED Indicator / Test Button**

**Red LED**

* Quick flash: Alarming
* Flashes every 1 second: Under Alarm Silence Mode
* Flashes every 2 seconds: Under warm-up and calibration process
* Flashes every 4 seconds with Orange LED: battery exhausted
* Flashes briefly: When Test Button is pressed to see if the device is functioning normally  Turns ON briefly (6 flashes): signal transmission

**Orange LED**

* Flashes every second: Calibration failed
* Flashes every 4 seconds with Red LED: battery exhausted
* Flashes every 5 seconds: Detecting smoke failed or device malfunctioning
* Flashes every 45 seconds: Low battery condition **Test Button**
* Press the button once to:
  * Send a test signal
  * Check smoke detection chamber
  * Silence alarm when the Smoke Detector is alarming
* Press and hold the button for 10 seconds to enter calibration process.

2. **Buzzer**
3. **Pre-punched Hole for Wiring**
4. **PowerTermnial for DC Connection (Red & Black) / BUS Terminal**
5. **Terminal Resistor Jumper Switch**

* On each BUS network, enable the terminal resistor jumper switch at both endpoints (the two farthest nodes) to prevent signal reflection and ensure stable connection.
* If the Wired Smoke Detector is one of the two endpoints, set its terminal resistor jumper switch to ON.

&#x20;                   **Jumper On =** Enable the terminal resistor

&#x20;                   **Jumper Off =** Disable the terminal resistor

6. **DC Strip Connection Socket / BUS Strip Connection Socket**
7. **Battery Switch (OFF <-->** ON)
8. **Mounting Bracket**
9. **Mounting Holes**
10. **Mounting Sheet**

## Features

### Power Supply

The Wired Smoke Detector is powered by one of the following 3 power sources:

* 13.5V (typical) DC power supply from the Control Panel _(primary source)_
* 12V DC power supply\_ (alternative/optional source)\_
* Rechargeable battery pack _(used during power failure)_

**Power Supply from Panel**

When SD-32-BUS is hardwired to the Control Panel, a 13.5V (typical) DC power supply can be provided by the Panel to the Smoke Detector.

![](<.gitbook/assets/Unknown image (497)>)

**12V DC Power Supply**

Connect the red and black power terminals to a 12V DC power source (e.g., a PSU or a power adapter).

<figure><img src=".gitbook/assets/image (1326).png" alt=""><figcaption></figcaption></figure>

![](<.gitbook/assets/Unknown image (499)>)

**Rechargeable Battery Pack**

* When the primary DC power (e.g., 13.5V from the Panel or 12V DC power) is available and the battery switch is set to ON, the rechargeable battery pack will charge and serve as a backup power source during DC power loss.
* The Wired Smoke Detector will transmit a BUS Power Loss signal to the Panel when the primary power is lost, and a BUS Power OK signal when it is restored.
* If the Wired Smoke Detector is operating on battery power and detects low battery voltage twice in a row, it will transmit a low battery signal and enter low battery status, indicated by a beep and a flash of its Orange LED every 45 seconds.

{% hint style="info" %}
Note: The first press of the Test Button in the low battery status will mute the warning beeps for 7 days. Any further button press after 7 days will not silence the warning beeps.
{% endhint %}

* The Red and Orange LEDs will flash once every 4 seconds when the batteries are exhausted.
* If the battery switch is set to OFF or the battery pack is not properly connected, the Detector will send a signal to the Panel.
* Backup battery replacement must be performed by qualified technicians only.

### Smoke Detector Wiring

* Before connecting the Wired Smoke Detector to the system BUS, please toggle the power switch to off.
* To assist with cable connections, the terminal blocks on each BUS system module are color-coded.

<figure><img src=".gitbook/assets/image (1327).png" alt=""><figcaption></figcaption></figure>

* For optimal communication on the BUS network, enable the Terminal Resistor Jumper Switches only at the two farthest endpoints to prevent signal reflection and ensure stable communication. Do not enable jumpers on intermediate BUS devices — only the two farthest nodes should have them enabled.

{% hint style="info" %}
Note:

* The pluggable design of BUS terminal blocks enhances installation efficiency. Before wiring, you can remove the terminal blocks from the PCB for ease of use, and plug in after wiring.
* After unplugging the terminal, when re-installing the terminal back to the board, make sure to install the terminal in the same direction to avoid potential hazards.
{% endhint %}

* Place the BUS terminal cover onto the device. Push it downward and forward to ensure the BUS strips on the cover connect properly to the device’s connection socket, then tighten the screw to enable the BUS terminal’s function.

![](<.gitbook/assets/Unknown image (501)>)

* Incorrect connection will result in failure or malfunction. Ensure proper connection before supplying power.

<figure><img src=".gitbook/assets/Unknown image (502)" alt=""><figcaption></figcaption></figure>

### Testing the Smoke Detector

By pressing the Test Button on the Wired Smoke Detector, you can test if the Detector is functioning normally.

* If the Detector functions normally, the Red LED will be on for 2 seconds followed by a 2-tone beep.
* If the buzzer sounds 2-tone beeps 3 times, the “**Optical Chamber**” on the Smoke Detector is either dirty or out-of-order.

### Dust Accumulation Detection

* The Detector regularly checks for excessive dust buildup inside the Optical Chamber.
* If the chamber accumulates must dust, the Detector will report to the Panel to notify the user to clean it.
* If the chamber is still not cleaned and gets too much dust that it doesn't work anymore, the Detector will report to the Panel for maintenance warning.

### Supervision

* The Wired Smoke Detector automatically transmits a supervision signal to the Control Panel every 75 seconds when powered by the primary power source.
* If the Control Panel has not received the signal from the Wired Smoke Detector for a preset period time, the Control Panel will indicate that the particular Smoke Detector is experiencing an out-of-signal problem.

### Alarm Activation

The Wired Smoke Detector will activate a fire alarm when the smoke concentration reaches the alarm threshold. When an alarm is raised, the Smoke Detector will transmit alarm signals and sound its built-in buzzer.

#### Smoke Detection

* The Smoke Detector checks smoke concentration regularly.
* The alarm is activated whenever the smoke concentration exceeds the alarm threshold, and will continue until the smoke concentration drops below the threshold.
* The Red LED will flash quickly during an alarm.

### Alarm Silence

* When the Smoke Detector is alarming, press the Test button or disarm the system to immediately deactivate the buzzer.
* During the 9-minute Alarm Silence period, the Red LED will flash once per second, and the Smoke Detector will remain silent even if smoke concentration continues to rise and exceeds a second alarm threshold.
* After the 9-minute Alarm Silence period has expired, if the smoke concentration has dropped below alarm threshold, the Smoke Detector will emit a 2-tone beep and return to normal operation without sounding alarm.

### Interconnection

* The Smoke Detector is interconnected with other Smoke Detectors in the alarm system. When one Smoke Detector triggers an alarm, the Control Panel will notify all interconnected Smoke Detectors to also raise their alarms, even if they have not detected smoke.
* To stop the alarm:
  * Wait for the smoke concentration to drop below the alarm threshold, or
  * Press the Test Button on the triggered Smoke Detector. This will also stop all interconnected Smoke Detectors. ![](<.gitbook/assets/Unknown image (503)>)_**Pressing the Test Button on any interconnected Smoke Detector will only stop the alarm of that specific unit; it will not silence the alarms across the entire system**._
* **(For Security System only)** Disarming the system will stop alarms activated by the Control Panel on all interconnected Smoke Detectors. However, the originally triggered Smoke Detector will continue alarming until the smoke concentration falls below the threshold or its Test Button is pressed to silence its alarm.

### Getting Started

**Step 1 Power on: Connect the Detector to the Control Panel and then toggle the battery switch to ON.**

**Step 2 Warm up: After power is provided to the Detector, it will emit 2 short beeps and begin warm-up for 1 minute. The Red LED will flash every 2 seconds.**

**Step 3 Calibration: When the Detector completes warm-up, it will emit a beep to indicate it has entered calibration mode. The calibration mode lasts for 1 minute (If calibration fails, the Detector will retry calibration; calibration mode will last 9 minutes at most). The Red LED will continue to flash every two seconds during calibration.**

**Step 4:** When calibration is completed, the Detector will emit 2 short beeps and return to normal mode with the LED off.

{% hint style="info" %}
Note:  If calibration fails, the Detector will beep continuously. Please power it off, then re-power it on and retry from step 1.
{% endhint %}

**Step 5:** Put the Control Panel to **Learning Mode**.

**Step 6:** Press the Test Button once to transmit a learn code.

**Step 7:** Click “**Add**” to include the detected Smoke Detector in the Panel.

### Identification

The “Identify” function is used to localize a specific BUS device in the BUS wired system. This function is helpful in distinguishing which device is which especially in a large installation where numerous BUS devices are included. To locate the Wired Smoke Detector in the BUS system:

**Step 1** On Hybrid Panel’s webpage, click “Identify” under the device list after the SD-32-BUS’s device column entry.

**Step 2** If the Wired Smoke Detector receives the signal from the Hybrid Panel, the webpage will display a success message and the Wired Smoke Detector’s Red LED indicator will flash 10 times to indicate where it is to the user.

{% hint style="info" %}
Note: If a timeout message appears on the webpage, it means the Wired Smoke Detector did not receive the signal from the Panel.

Please check whether SD-32-BUS is connected properly to the Panel within appropriate wiring distance.
{% endhint %}

### Walk Test

* To make sure the Wired Smoke Detector is able to communicate with the Panel after it is learned-in, place the Control Panel in Walk Test mode and press the Test Button on SD-32-BUS to transmit a test signal to the Panel.
* When the Panel receives the test signal, it will beep once and display the Wired Smoke Detector’s information accordingly on the top of the device list.

{% hint style="info" %}
Note: If there is no response from the Panel after the press of test button, it means the Panel did not receive the test signal from the device.

Please check whether the Detector is connected properly to the Panel within appropriate wiring distance.
{% endhint %}



### Wired Device Test (Power Test)

The “Wired Device Test” verifies that the power supply is sufficient for stable operation of all connected BUS devices. During Power Test, the Hybrid Panel will request all connected BUS devices to operate simultaneously under their highest power consumption conditions.

If all BUS devices complete their operations successfully, it indicates the system has adequate power for normal operation.

To perform the Wired Device Test:

**Step 1** On Hybrid Panel’s webpage, click “**Wired Device Test**” to access the test page. All learned-in BUS devices will be listed in the Wired Devices section.

![](<.gitbook/assets/Unknown image (504)>)

**Step 2** From the **Action** drop-down menu, select “**Prepare**”, then click “**Execute**”. This will initiate a 250-second execution period during which devices are prepared and tested.

**Step 3** During the execution period, select “**Power Test**” from the Action menu, then click “**Execute**”. All connected BUS devices will operate at maximum current draw for 10 seconds.

* Device behavior varies by type. For SD-32-BUS, it will sound its built-in buzzer and flash its Red LED for 10 seconds.
* If a device operates successfully and reports back, the message “**Executed successfully**” will appear in the _Status_ column.If the message does not appear, possible reasons include: a) abnormal device operation (e.g., due to insufficient power), b) improper connection, or c) the device does not support the Power Test function.
* You can repeat the Power Test multiple times within the 250-second period by repeating Step 3.

**Step 4** Select “**Stop Test**” and click “**Execute**” to manually end the Power Test. Otherwise, the test will automatically end once the 250 seconds have elapsed.



### Auto-Calibration

* Frequency: After the first installation, the Wired Smoke Detector will perform auto-calibration after 12 hours. Afterwards, it will perform auto-calibration once every 15 days. During the auto-calibration process, the Smoke Detector will not emit any sounds, and the red LED will flash once every 2 seconds for about 50 seconds.
* Calibration Failure: If the auto-calibration fails, the orange LED will start to flash every second. The flashing of the orange LED can be cancelled by removing and reloading the batteries, or by manually starting the calibration process.
* Recalibration Failure: If the manual calibration fails again, the Detector will emit continuous beeps and the orange LED will also flash continuously. In this case, you need to remove the batteries, wait for 30 second, and then reload the batteries to restart the Detector.

{% hint style="info" %}
Note:  If the auto-calibration fails, the smoke alarm function will still work normally using the threshold value taken from the last successful calibration.
{% endhint %}

### Recalibration (Manual Calibration)

As the operation condition of the Detector may vary after being installed for some time, you may wish to recalibrate the Smoke Detector to take a new smoke detection threshold value and ensure optimal performance of the Smoke Detector. To do this:

* Initiation: Press and hold the Test Button for 20 seconds and release when the Smoke Detector emits 3 beeps. The device will begin calibration, and the Red LED will flash every 2 seconds to indicate.
* Duration: The calibration process lasts\*\* 1 minute\*\* (If it fails, the Detector will retry; the calibration will last for 9 minutes at most).
* Recalibration Success: When calibration is finished, the Detector will sound a two-tone beep. The Red LED will stop flashing to indicate it has returned to normal mode.

Recalibration Failure: If calibration fails, the Detector will beep continuously, and the Orange LED will flash every second. Please power off the smoke detector, and then re-power on to restart Smoke Detector.

### Maintenance & Cleaning

Regular maintenance and cleaning will help keep your Smoke Detector in good working order.

* Test the Smoke Detector weekly to verify that the alarm sounds and LED indicators are working properly.
* Clean the Smoke Detector at least once every 6 months.
  * Gently vacuum off the dirt/dust/foreign particles accumulated in the smoke detection chamber and slots.
  * Clean the casing by swiping it thoroughly with a damp cloth and dry it. Do not get water inside the device.  Never use cleaning agents, detergents or solvents on the detector.
* Avoid spraying air freshener, hair spray, or other aerosols near the Smoke Detector.
* Do not paint nor modify the detector under any circumstances.

### Expiration

The Smoke Detector has a maximum life time of **10 years** from the date of installation. You should replace the Smoke Detector immediately after 10 years of service.

It is recommended to write the “Replace by” date (10 years from installation date) on the back of the detector prior to installation.

### Installation

<figure><img src=".gitbook/assets/image (1328).png" alt=""><figcaption></figcaption></figure>

#### Installation Guideline

 It is recommended to install the device near the center of the ceiling.

<mark style="color:$danger;">**LOCATIONS TO AVOID:**</mark>

* The Kitchen – Smoke from cooking might cause an unwanted alarm.
* Near ventilating fans, florescent lamps or air conditioners as air drafts from them may affect the device sensitivity.
* Near ceiling beams or over a cabinet – stagnant air in these areas may affect the device sensitivity.
* In the peak of an “**A**” frame type of ceiling.
* In or near insect-attracting areas, such as trash cans, plants, or humid areas, as insects may interfere with the Detector’s operation or trigger false alarms.

#### Mounting the Smoke Detector

* A mounting sheet is provided to help users correctly install the Smoke Detector.
* The mounting sheet has a perforated design for mounting holes, and can be removed from the mounting surface easily after installation.

Please follow the steps below to mount the Wired Smoke Detector:

Step 1 – Using Mounting Sheet: Place the mounting sheet on the surface to be mounted; use the mounting holes on the mounting sheet to drill four mounting holes into the surface.

**Step 2 –** **Inserting Wall Plugs:** Insert the wall plugs. Ensure the wall plugs are flush with the mounting surface.

**Step 3 – Aligning Mounting Bracket:** Precisely align the four mounting holes on the mounting bracket with those on the mounting sheet and screw the mounting bracket onto the wall plugs.

For easier alignment, first locate the two mounting holes farther from the inner circle edge on both the mounting sheet and the mounting bracket. Align these holes first, and the remaining ones should naturally follow.

<figure><img src=".gitbook/assets/Unknown image (507)" alt=""><figcaption></figcaption></figure>

<figure><img src=".gitbook/assets/Unknown image (506)" alt=""><figcaption></figcaption></figure>

**Step 4 – Mounting Detector**: The Smoke Detector has 4 hooks (circled in red) on its back cover. Carefully hold the Smoke Detector and fit it onto the four notches (circled in green) on the mounting bracket (FIG. 1).

![](<.gitbook/assets/Unknown image (508)>) ![](<.gitbook/assets/Unknown image (509)>)

**Step 5:** Rotate the Smoke Detector clockwise to lock it in place (FIG. 2).

**Step 6:**&#x49;nstallation is now complete (FIG. 3). You can remove the mounting sheet.

![](<.gitbook/assets/Unknown image (510)>)
