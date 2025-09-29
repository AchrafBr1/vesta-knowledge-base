# VESTA-032

SDCO-1-F1 Series

## Smoke and Carbon Monoxide Detector

<figure><img src=".gitbook/assets/image (29) (1) (1).png" alt=""><figcaption></figcaption></figure>

## Introduction

SDCO-1-F1 Series is a Smoke and Carbon Monoxide Detector. It is capable of sending wireless signals to the Control Panel upon detection of smoke particles or Carbon Monoxide. The SDCO-1 is designed to be mounted on ceiling or top of stairwells where smoke would concentrate to raise alarm timely and protect your home from fire hazards.

The SDCO-1 Series include the following models:

<figure><img src=".gitbook/assets/1 (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1).png" alt=""><figcaption></figcaption></figure>

## Parts Identification

![](<.gitbook/assets/0 (24).png>)

1. **Test Button**

* Press the button once to send a test/learn signal.
* Press the button once during alarm to enter alarm silence mode.
* Press and hold the button for 10 seconds. Release the button when the SDCO emit 2 beeps to enter smoke calibration and CO self-diagnosis process.
* Press the button twice to fully discharge before inserting new batteries.

2. **LED Indicator**

&#x20;  **Red LED**

* Turns ON briefly: Transmitting test/learn signal.
* Quick flash: Alarming.
* Flashes every second: in alarm silence mode.
* Flashes every 2 seconds: Under warmup and calibration process.

**Amber LED**

* Flashes every 5 seconds: Device malfunction
* Flashes every 45 seconds: Low battery condition

**Both Red and Amber LED (Orange when looking from the outside)**

* Flashes every 4 seconds: Batteries are extremely low and need to be replaced.

3. **Buzzer**
4. **Mounting Holes (for Hooks)**

&#x20;      The Hooks of the Mounting Bracket can hook into its Mounting Holes.

5. **Mounting Bracket**
6. **Battery Compartment Cover**
7. **Battery Compartment Cover Fixing Screw**
8. **Notches**
9. **Firmware Update Port (USB Type-C)**

* For firmware update with customized cable only. **Please note:** Misuse of normal USB Type C cable can result in device malfunction.

## Features

### Battery and Low Battery Detection

* The SDCO-1 uses three EL123AP Lithium Batteries as its power source. The batteries are included in the package.
* The SDCO has a foolproof mechanism which prohibits cover closure without first installing battery.
* When the SDCO is low on battery, a low battery signal will be transmitted along with regular signal transmissions. The Amber LED will flash with a low-volume beep once every 45 seconds.
* Both Red and Amber LED will flash once every 4 seconds when batteries are extremely low and needed to be replaced.
* When changing the batteries, after removing the old batteries, press the Test Button twice to fully discharge before inserting new batteries.

### Getting Started

**Step 1:** Use a Phillips screwdriver to loosen the battery compartment fixing screw, and remove the battery compartment cover.

**Step 2:** Insert 3 batteries into the battery compartment.

**Step 3:** The SDCO Detector will emit 2 short beeps, and begin warm up process for **1** minute. LED will flash every 2 seconds.

**Step 4.** During the 1 minute period, learn in the Smoke Detector.

1. Press the Learn/Test button once to transmit an IR sensor learn code.
2. Press and hold the Learn/Test button for 3 seconds to transmit a Smoke/Temperature sensor learn code **(step a. and step b. are both required for serial connected models)**.

If the Control Panel receives the signal, the Smoke Detector will emit a 2-tone beep. Refer to Control Panel manual to complete learning process.

**Step 5:** When 1-minute warm up period expires, the SDCO Detector will emit a beep to indicate it now enters calibration process. The

calibration process takes 1\~7 minutes; the LED will continue to flash during calibration.

**Step 6:** When calibration is complete, the SDCO Detector will emit a 2-tone sound and LED will stop flashing to indicate it is now under

normal operation. If calibration fails, the SDCO Detector will sound continuous beeps.

### _**Alarm Detection**_

The SDCO Detector will activate fire alarm when either of its smoke detection or high heat detection function is triggered. When an alarm is activated, the SDCO Detector will transmit alarm signal and raise alarm with its built-in buzzer. The Red LED will flash rapidly.

**Smoke Detection:**

* The SDCO Detector checks smoke concentration every 8 seconds
* Whenever the smoke concentration exceeds the detection threshold, SDCO will send active signal to the Control Panel, and activate the alarm.
* If the smoke concentration persists, the SDCO Detector will continue to send the active signal every 2 minutes to the Control Panel.
* If no smoke is detected for 20 continuous detection times, the SDCO will transmit a restore signal and stop the alarm.

**Heat Detection (For SDCO-1H-F1 and SDCO-1H-F1-2W models only):**

* The SDCO Detector checks temperature every 10 seconds.
* The alarm will be activated in the following conditions:

\- When the temperature rises by 8.25°C per minute (Rate of Rise).

\- When the temperature exceeds 57.25°C (High Heat).

* If no high heat is detected for 20 continuous detection times, the SDCO will transmit a restore signal and stop alarming.
* If the alarm was triggered by High Heat condition (57.25°C), the temperature must drop below 49°C for the Detector to stop alarming.
* If the alarm was triggered by Rate of Rise condition (8.25°C per minute or more), the temperature must drop to 4°C below highest temperature detected for the Detector to stop alarming.

**Carbon Monoxide Detection:**

* The CO sensor checks the CO concentration level every 16 seconds. If the concentration level exceeds the detection threshold, the SDCO Detector will transmit alarm signal and raise alarm with its built in buzzer.
* The CO sensor features self-diagnosis function and will regularly check the health or status of the sensor every 12 hours.
* The alarm will be activated after CO concentration is detected according to time length in the following table: (compliant with EN-50291 standard)

<figure><img src=".gitbook/assets/2 (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1).png" alt=""><figcaption></figcaption></figure>

* The alarm will be activated after CO concentration is detected according to the time length in the following table: (compliant with UL-2034 standard)

<figure><img src=".gitbook/assets/3 (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1).png" alt=""><figcaption></figcaption></figure>

* Once the CO concentration level exceeds the threshold and persists for the time length as listed in the above table, the SDCO Detector will transmit the signal to the Control Panel and raise alarm with its built-in siren.

### Testing the SDCO Detector

By pressing the Test Button on the SDCO Detector, you can test if the SDCO is functioning normally.

* If the SDCO Detector functions normally, the Red LED will flash once followed by a 2-tone beep.
* If three 2-tone beeps (DO-DI DO-DI DO-DI) are emitted, it means the Smoke Sensor is out-of-order.
* If 5 beeps (DO-Bi-Bi-Bi-DO) are emitted, it means the Heat Sensor is out-of-order.
* If 7 beeps (Bi-Bi-Bi-DO-Bi-Bi-Bi) are emitted, it means the CO Sensor is out-of-order.

### _**Supervision**_

* For SDCO-1(H)-F1 models, the SDCO Detector will transmit a supervision signal to report its condition regularly every 30 to 50 minutes.
* For SDCO-1(H)-F1-2W models, the SDCO Detector will transmit a supervision signal to report its condition regularly every 90 to 110 minutes.
* If the Control Panel has not received the signal from the Smoke Detector for a preset period of time, the Control Panel will determine the Smoke Detector is out of order.

### _Serial Connection_ _(serial connected model only)_

* The Smoke Detector is in serial connection with other Smoke Detector in the alarm system. When a Smoke Detector activates alarm, the Control Panel will notify other Smoke Detectors to also raise alarm even if they have not detected smoke yet. The alarm length will be in accordance with the Control Panel’s setting.
* You cannot press the function button to silence alarm activated by other Smoke Detectors.
* Alarm will be restored only after 3 minutes timeout or until the other Smoke Detector which triggers alarm transmits a restore signal.

### Alarm Silence

* When the Smoke Detector is alarming, pressing the Test button will put the Smoke Detector into Alarm Silence mode to silence the alarm for 9 minutes. The buzzer will only stop sounding after the alarm has been activated for at least 1-minute. If the button is pressed before alarm time reaches 1 minute, the Smoke Detector will wait until alarm time has reach 1 minute before silencing the alarm.
* During the 9-minute Alarm Silence period, the Red LED will flash once per second. The Smoke Detector will continue to monitor smoke concentration during the alarm silence period:

1. After the 9-minute Alarm Silence period has expired, if the smoke concentration has dropped below alarm threshold, the Smoke Detector will emit a 2-tone beep and return to normal operation without sounding alarm.
2. If smoke concentration still exceeds alarm threshold, the Smoke Detector will start alarming again.
3. If smoke concentration continues to rise during Alarm Silence period and exceeds a second alarm threshold, the Smoke Detector will start alarming again. An alarm activated by exceeding the second alarm threshold could not be silenced by pressing the test button.

### Recalibration

The SDCO will calibrate its smoke detector sensor every time when power is applied to ensure optimal smoke sensitivity. After installation, the operation condition of the Smoke Detector may vary after some time, which may affect its smoke detection function and requires recalibration. There are two ways to recalibrate the Smoke Detector: auto calibration and manual calibration.

### **Auto Calibration:**

* After power up, the Smoke Detector will perform auto-calibration after 4 hours.
* After the first auto-calibration, the Smoke Detector will perform auto calibration every month. During the auto-calibration process, the Smoke Detector will not emit any sound.
* If auto-calibration fails, the Amber LED will flash every second along with continuous beeps and Smoke Detector will transmit a calibration failure signal.
* When Smoke Detector auto calibration fails, the smoke alarm function will still work normally using the threshold value taken from the last successful calibration.

### **Manual Calibration:**

* Manual calibration can be performed any time as desired:

1. Press and hold the Learn/Test button for 10 seconds and release when the Smoke Detector emits 2 beeps.
2. The Smoke Detector will enter calibration process. The LED Indicator will flash every 2 seconds.
3. After the Smoke Detector finishes recalibration, it will emit two quick beeps to indicate. The LED will turn off.
4. If calibration process fails, Smoke Detector will emit alarm sound. Please remove and reinsert battery to restart process again.

## Installation

### Installation Guideline

<figure><img src=".gitbook/assets/4 (119).png" alt=""><figcaption></figcaption></figure>

* It is recommended that the installation site be in the center area of the ceiling.
* The ideal mounting height for the SDCO Detector is 2.4 meters to 3 meters. Mounting above 3 meters can affect detection performance.
* Do not locate the detector in the following locations:
* The Kitchen – Smoke from cooking might cause an unwanted alarm.
* Near a ventilating fan, fluorescent lamp or air-conditioning equipment – air drafts from them may affect the sensitivity of the detector.
* Near ceiling beams or over a cabinet – stagnant air in these areas may affect the sensitivity of the detector.
* In the peak of an “A” frame type of ceiling.

Installation Recommendation

* **Limitations**
* Do not install the SDCO Detector exposed to direct sunlight.
* Avoid installing the SDCO Detector in areas where devices may cause rapid change of temperature in the detection area, i.e. air conditioner, heaters, etc.
* Avoid large obstacles in the detection area.
* Do not point directly at sources of heat e.g. Fires or boilers, and not above radiators.

### Mounting the SDCO Detector

**Step 1.** Place the SDCO Detector at desired mounting location and use the Range Test function to make sure the SDCO Detector can be received by the Control Panel at mounting location.

**Step 2.** The SDCO Detector has a mounting bracket for ceiling installation. The bracket provides bidirectional flexibility.

**Step 3.** Use the 4 holes on the bracket as a template to drill holes and insert wall plugs if required.

**Step 4.** The user can either rotate the mounting bracket clockwise or counterclockwise to lock the hook. Ensure the wall plugs are flush with the mounting surface.

**Step 5.** When the position is satisfactory, then screw the mounting bracket onto the ceiling.

**Step 6.** Wipe away dust thoroughly, or it can make the sensor dirty and prevent it from operating properly in case of an emergency.

**Step 7.** The SDCO has three notches on its back cover for easy identification, as shown below.

![](<.gitbook/assets/3 (27).png>)

**Step 8.** Hold the SDCO Detector with extra care and align the three notches with the hooks on the mounting bracket.

**Step 9.** Rotate the SDCO Detector clockwise to lock the hook. Installation is now complete.
