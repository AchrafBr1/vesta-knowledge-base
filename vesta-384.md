# VESTA-384

**SD-32-BUS**

## **Wired Smoke Detector**

**Introduction**

SD-32-BUS is a wired smoke detector designed to protect you against potential fire hazards. The Smoke detector uses multi criteria sensor technology for detecting between fast burning flames and slow smoldering fires, while at the same time includes intelligent technology to differentiate between cooking smoke and actual life-threatening house-fire emergencies, virtually eliminating nuisance alarms.

The wired smoke detector can also be interconnected with other smoke detectors in the alarm system, and raises alarm when any smoke detector in the system is triggered.

## **Parts Identification**

![](<.gitbook/assets/1 (96).png>)

**1. LED Indicator / Test Button**

**Red LED**

* Quick flash: Alarming.
* Flashes every 1 second: Smoke Detector under Alarm Silence Mode.
* Flashes every 2 seconds: Smoke Detector under warmup and calibration process.
* Flashes briefly: When Learn Button is pressed to see if the device is functioning normally.
* Turns ON briefly: Transmitting signal.

**Orange LED**

* Flashes every second: Calibration failed.
* Flashes every 5 seconds: Detecting smoke failed or device malfunctioning.

**Test Button**

* Press the button once to:
  * Send a test signal.
  * Check smoke detection chamber.
  * Silence alarm when the Smoke Detector is alarming.
* Press and hold the button for 10 seconds to enter calibration process.

2. **Buzzer**
3. **BUS Terminal Compartment**
4. **Hooks**
5. **Pre-punched Hole for Wiring**
6. **Fixing Screw of BUS Terminal Comapartment Cover**
7. **BUS Terminal**
8. **Terminal Resistor Jumper Switch**

When the Smoke Detector is connected as the furthest BUS device on a BUS line, please set the Smoke Detector 's terminal resistor jumper and the first BUS device’s (usually the Hybrid Panel’s) Jumper Switch to ON to serve as terminating resistors. The connected BUS line’s communication ability will be enhanced.

* If the jumper is OFF (the jumper link is removed or “parked” on one pin), the communication ability is in normal level.
* If the jumper is ON, the the communication ability will be enhanced.

9. **Mounting Bracket**
10. **Mounting Holes**
11. **Mounting Sheet**

## **Features**

* _**Power Supply**_
  * When SD-32-BUS is hardwired to a Hybrid Panel, 13.5V power supply can be provided by the Hybrid Panel.
* _**Testing the Smoke Detector**_

By pressing the Test Button on the Smoke Detector, you can test if the Smoke Detector is functioning normally.

* If the Smoke Detector functions normally, the Red LED will be on for 2 seconds followed by a 2-tone beep.
* If the buzzer sounds 2-tone beeps 3 times, the “**Optical Chamber**” on the Smoke Detector is either dirty or out-of-order.
* _**Dust Accumulation Detection**_
  * The detector regularly checks for excessive dust buildup inside the Optical Chamber.
  * If the chamber accumulates must dust, the detector will report to the Panel to notify the user to clean it.
  * If the chamber is still not cleaned and gets too much dust that it doesn't work anymore, the detector will report to the Panel for maintenance warning.
* _**Supervision**_
  * The Wired Smoke Detector will automatically transmit supervision signal to the Control Panel every 75 seconds.
  * If the Control Panel has not received the signal from the Wired Smoke Detector for a preset period time, the Control Panel will indicate that the particular Smoke Detector is experiencing an out-of-signal problem.
* _**Alarm Activation**_

The Smoke Detector will activate fire alarm when smoke detection is triggered. When an alarm is activated, the Smoke Detector will transmit alarm signal and raise alarm with its built-in buzzer.

#### **Smoke Detection:**

* The Smoke Detector checks smoke concentration every 8 seconds
* The alarm is activated whenever the smoke concentration exceeds the detection threshold, and will continue until the smoke concentration drops below alarm threshold.
* The Red LED will flash quickly during alarm.
* _**Alarm Silence**_
  * When the Smoke Detector is alarming, pressing the Test button will put the Smoke Detector into Alarm Silence mode to silence the alarm for 9 minutes. The buzzer will only stop sounding after the alarm has been activated for at least 1-minute. If the button is pressed before alarm time reaches 1 minute, the Smoke Detector will wait until alarm time has reach 1 minute before silencing the alarm.
  * During the 9-minute Alarm Silence period, the Red LED will flash once per second. The Smoke Detector will continue to monitor smoke concentration during the alarm silence period:
  * After the 9-minute Alarm Silence period has expired, if the smoke concentration has dropped below alarm threshold, the Smoke Detector will emit a 2-tone beep and return to normal operation without sounding alarm.
  * If smoke concentration still exceeds alarm threshold, the Smoke Detector will start alarming again.
  * If smoke concentration continues to rise during Alarm Silence period and exceeds a second alarm threshold, the Smoke Detector will start alarming again. An alarm activated by exceeding the second alarm threshold could not be silenced by pressing the test button.
* _**Interconnection**_
  * The Smoke Detector is interconnected with other Smoke Detectors in the alarm system. When a Smoke Detector activates alarm, the Control Panel will notify other Smoke Detectors to also raise alarm even if they have not detected smoke yet. The alarm length will be in accordance with the Control Panel’s setting.
  * Disarming the system will stop alarm of other Smoke Detectors activated by the Control Panel. The alarm triggered by the Smoke Detector that detects smoke will only stop when the smoke concentration drops below alarm threshold.
  * Pressing the Test button of a smoke detector will only silence alarm of that specific smoke detector, but cannot silence alarm of all interconnected Smoke detectors.

{% hint style="danger" %}
_**Caution**_

* Wiring of the Smoke Detector should only be performed by certified technicians with proper knowledge and training in electric equipment.
* Before installation or any maintenance work, make sure the power supply has been disconnected.
{% endhint %}

* _**Smoke Detector Wiring**_
  * Before connecting the Wired Smoke Detector to the system BUS, please switch the power off.
  * To assist with cable connections, the terminal blocks on each BUS system module are color-coded.

![](<.gitbook/assets/13 (41).jpeg>)

* Multiple BUS devices can be connected in series to the Hybrid Panel. For optimal communication of the the connected BUS line devices, ensure the terminal resistor jumper switches of the first (usually the Hybrid Panel) and the furthest BUS devices on a BUS line are set to ON to serve as terminating resistors. Be sure to only enable the aforementioned 2 jumper switches, and do not set the jumper switches to ON for any other BUS devices in between.

{% hint style="warning" %}
Note:

* The pluggable design of BUS terminal blocks improves upon installation efficiency. Before wiring, you can remove the terminal blocks from the PCB board for ease of use, and plug in again after wiring.
* After unplugging the terminal, when re-installing the terminal back to the board, make sure to install the terminal in the same direction to avoid potential hazards.
{% endhint %}

* Incorrect connections will result in failure or malfunction. Inspect wiring and ensure proper connections before applying power.

![](<.gitbook/assets/14 (54).png>)

## _**Getting Started**_

**Step 1** Connect the detector to the Panel. Then, power the Panel on, the Smoke Detector will be powered on as well.

**Step 2** After power is provided to the Smoke Detector, it will emit 2 short beeps and begin **warm up for 1 minute**. The Red LED will flash every 2 second&#x73;**.**

**Step 3.** When the Smoke Detector completes warm-up, it will emit a beep to indicate it has entered **calibration mode**. The calibration mode lasts for **1 minute** (If calibration fails, the smoke detector will retry calibration, calibration mode will last 9 minutes at most). The Red LED will continue to flash every two seconds during calibration.

**Step 4.** When calibration is completed, the Smoke Detector will emit 2 short beeps and turn off LED to return to normal mode.&#x20;

{% hint style="warning" %}
Note:

If calibration fails, the Smoke Detector will beep continuously. Please power off the smoke detector, and then re-power on to retry from step 1.
{% endhint %}

After warm up and calibration process are successfully completed, you can proceed to learning.

**Step 5.** Put Control Panel into **learning mode**.

**Step 6** The smoke detector will be detected if it is correctly connected to the Hybrid Panel.

**Step 7.** Click “**Add**” to include the detected smoke detector to Control Panel.

### _**Identification**_

The “Identify” function is used to localize a specific BUS device in the BUS wired system. This function is helpful in distinguishing which device is which especially in a large installation where numerous BUS devices are included.

To locate the Wired Smoke Detector in the BUS system:

**Step 1.** On Hybrid Panel’s webpage, click “Identify” under the device list after the SD-32-BUS’s device column entry.

**Step 2.** If the Wired Smoke Detector receives the signal from the Hybrid Panel, the webpage will display a success message and the Wired Smoke Detector’s Red LED indicator will flash 10 times to indicate where it is to the user.

{% hint style="warning" %}
Note:

If a timeout message is displayed on the webpage, it means the Wired Smoke Detector did not receive the signal from the Panel. Please check whether SD-32-BUS is connected properly to the Panel within appropriate wiring distance.
{% endhint %}

### _**Walk Test**_

* To make sure the Wired Smoke Detector is able to communicate with the Panel after it is learned-in, place the Control Panel in Walk Test mode and press the Test button on SD-32-BUS to transmit a test signal to the Control Panel.
* When the Panel receives the test signal, it will beep once and display the Wired Smoke Detector’s information accordingly on the top of the device list.

{% hint style="info" %}
Note:

If there is no response from the Panel after the press of test button, it means the Panel did not receive the test signal from the device. Please check whether the Smoke Detector is connected properly to the Panel within appropriate wiring distance.
{% endhint %}

### _**Recalibration**_

As the operation condition of the Smoke Detector may vary after being installed for some time, you may wish to recalibrate the Smoke 3

Detector to take a new smoke detection threshold value and ensure optimal performance of the Smoke Detector. To do this:

* Press and hold the Test Button for 20 seconds and release when the Smoke Detector emits 3 beeps. The device will begin calibration, and the Red LED will flash every 2 seconds to indicate.
* Calibration process lasts for **1 minute** (If calibration fails, the smoke detector will retry calibration, calibration mode will last 9 minutes at most).
* When calibration is finished, the Smoke Detector will sound a two-tone beep. The Red LED will stop flashing to indicate it has returned to normal mode.
* If calibration fails, the Smoke Detector will beep continuously, and the Orange LED will flash every second. Please power off the smoke detector, and then re-power on to restart Smoke Detector.

## **Maintenance & Cleaning**

Regular maintenance and cleaning will help keep your Smoke Detector in good working order.

* Test the Smoke Detector weekly to verify that the alarm sounds and indicators are working properly.
* Clean the Smoke Detector at least once every 6 months.
  * Gently vacuum off the dirt/dust/small particles accumulated in the smoke detection chamber and slots.
  * Clean the casing by swiping it thoroughly with a damp cloth and dry it. Do not get water inside the alarm.
  * Never use cleaning agents, detergents or solvents on the detector.
* Avoid spraying air freshener, hair spray, or other aerosols near the Smoke Detector.
* Do not paint nor modify the detector under any circumstances.

## **Expiration**

The Smoke Detector has a maximum life time of **10 years** from the date of installation. You should replace the Smoke Detector immediately after 10 years of service.

It is recommended to write the “Replace by” date (10 years from installation date) on the back of the detector prior to installation.

## **Installation**

### _**Installation Guideline**_

* It is recommended that the installation site be in the center area of the ceiling.
* Do not locate the detector in the following locations:
* The Kitchen – Smoke from cooking might cause an unwanted alarm.
* Near a ventilating fan, florescent lamp or air-conditioning equipment – air drafts from them may affect the sensitivity of the detector.
* Near ceiling beams or over a cabinet – stagnant air in these areas may affect the sensitivity of the detector.
* In the peak of an “**A**” frame type of ceiling.

### _**Mounting the Smoke Detector**_

**Step 1.** Place the Smoke Detector at desired mounting location.

**Step 2.** Take out the mounting sheet included in the package. The picture’s size equals the Smoke Detector’s actual size and the perforated design allows for easy tear-off after installation.

**Step 3.** Position the sheet tight against the ceiling and use the four holes as template to drill holes and insert wall plugs if required.

Ensure the wall plugs are flush with the mounting surface.

**Step 4.** Place the mounting bracket on top of the mounting sheet and screw it onto the wall.

**Step 5.** The Smoke Detector has 4 hooks on its back cover. Hold the Smoke Detector with extra care and align the 4 notches on the mounting bracket with the 4 hooks.

<figure><img src=".gitbook/assets/image (272).png" alt=""><figcaption></figcaption></figure>

**Step 6.** Rotate clockwise to lock the hook.

<figure><img src=".gitbook/assets/image (273).png" alt=""><figcaption></figcaption></figure>

<figure><img src=".gitbook/assets/image (274).png" alt=""><figcaption></figcaption></figure>

**Step 7.** Installation is now complete. You can now tear off the mounting sheet.
