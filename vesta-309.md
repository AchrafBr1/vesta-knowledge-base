# VESTA-309

**SDCO-3-RhTHM-ZW-SC-AC-OTA)**

## **Smoke and Carbon Monoxide Detector**

SDCO-3-RhTHM-ZW-SC-AC-OTA is a Z-Wave Smoke and Carbon Monoxide Detector with built-in PIR Sensor, temperature, humidity, and heat detection, as well as voice prompts and allows access to the “S2 Unauthenticated” class and supports both of Z-Wave SmartStart Inclusion and classic Inclusion. It is capable of sending wireless signals to the Z-Wave gateway/control panel upon detection of smoke particles or Carbon Monoxide. The device is also serially connected with other sensors in the Z-Wave gateway to serve as an extra siren. When any other sensor in the Z-Wave network is activated and sends an alarm signal, the Smoke Detector will also raise alarm with its built-in buzzer as a siren to help sound warning (for serial connection models).

The SDCO-3 is designed to be mounted on ceiling or top of stairwells when smoke would concentrate to raise alarm timely and protect your home from fire hazards.

The SDCO Detector is a Z-Wave enabled device and is fully compatible with any Z-Wave enabled network. Z-Wave is a wireless communication protocol that uses a low-power RF radio.

![](<.gitbook/assets/1 (83).png>)

## _**Parts Identification**_

1. **Speaker**
2. **Button**
   * Press the button once to send an alarm test, alarm test deactivated, and temperature and humidity signals to test the Smoke and Carbon Monoxide Detector.
   * Press the button for 5 seconds, release the button until the amber LED turns on. Then the amber LED will begin to flash to indicate it has entered snooze mode. See Temporary Snooze Mode under the Features section for more details.
   * Press the button once during alarm to silence the alarm.
   * Press the button 3 times within 1.5 seconds to send an inclusion code.
   * Press and hold the button for 10 seconds. Release the button when you hear 2 beeps to enter smoke calibration and CO self-diagnosis process.
   * Press and hold the button for 20 seconds. Release the button when you hear 3 beeps to perform factory reset.
   * Press the button twice before inserting new batteries.
3. **PIR Motion Sensor**
4. **LED Indicator**

**Red LED**

* Turns ON briefly: Transmitting signal.
* Quick flash: Alarming.
* Flashes every second: In Alarm Silence Mode.
* Flashes every 2 seconds: Under warm-up and calibration process.
* Flashes quickly for 3 times every 8 seconds: Smoke is detected during fire verification period.
* Flashes quickly for 2 times every 5 seconds: When in snooze mode

**Amber LED**

* Flash every second: Device power on/Calibration failed.
* Flashes twice every 5 seconds: Device malfunction.
* Flashes every 45 seconds: Low battery condition

**Both Red and Amber LED (Orange when looking from the outside)**

* Turns ON: Temperature/ Humidity sensor failed.
* Flashes every 4 seconds: Battery exhausted.

5. **Buzzer**
6. **Mounting Holes**
7. **Mounting Bracket**
8. **Tamper Switch**
9. **Battery Compartment Cover**
10. **Battery Switch (Inside)**
11. **Pre Punched Hole for Wiring**
12. **Battery Compartment Cover Fixing Screw**
13. **Notches**
14. **Firmware Update Port (USB Type-C)**
    * For firmware update with customized cable only. **Please note:** Misuse of normal USB Type C cable can result in device malfunction.

## **Features**

### _**Battery and Low Battery Detection**_

* The SDCO-3-RhTHM-ZW-SC-AC-OTA model uses AC 100-240V as its power source and has three 600mAh AAA Ni-MH rechargeable batteries as its backup battery in case of power failure. The battery is included in the package.
* When the rechargeable battery is charging, the SDCO Detector will report its battery percentage to the Gateway/Control Panel respectively at 100%, 90%, 80%, 70%, 60%, 50%, 40%, 30%, and 20% (low battery).
* If an AC power failure is detected, the SDCO Detector will send an AC failure report to the Control Panel.
* When the SDCO Detector is low in battery, a low battery signal will be transmitted along with regular signal transmissions. The Amber LED will flash with accompanying low-volume beep once every 45 seconds.
* Both Red and Amber LED will flash once every 4 seconds when the battery is exhausted.

### _**Tamper Switch**_

* The SDCO Detector is protected by a tamper switch which is compressed when the SDCO Detector is hooked onto the mounting bracket. When the SDCO Detector is removed from the mounting bracket, the tamper switch will be activated and the SDCO Detector will send a tamper open signal to the system control panel to remind the user of this condition.
* The SDCO Detector will send a tamper close signal to the Control Panel after the device is hooked onto the mounting bracket. Please note that the SDCO Detector has to be included in the Z-Wave network first.

### _**Sensitivity Mode**_

* The device’s sensitivity level can be adjusted using Z-Wave’s Configuration Command. Up to eight levels of sensitivity can be configured (Default: 0x04). Set 0x01 for the highest sensitivity level. Please refer to page 11 **“Configurations”** section for details.
* _**Temporary Snooze Mode**_
  * This function allows you to pause the motion detection function for a specified period of time to avoid unwanted motion alerts without having to disarm the device.
  * By default, the function is disabled, and it can activate by pressing the button for 5 seconds, which enables the mode for 5 minutes. You may also activate the mode using Z-Wave’s Configuration Command, and up to 36 hours can be configured. The snooze mode will be terminated as soon as you press any button or operate the device. Please refer to page 12 **“Configurations”** section for details.

## _**Adding Device (Inclusion)**_

The device supports both classic inclusion process and SmartStart inclusion process.

### **Classic Inclusion**

This product can be included and operated in any Z-Wave network with other Z-Wave certified devices from other manufactures and/or applications. All non-battery operated nodes within the network will act as repeaters regardless of vendor to increase network reliability.

* To add the SDCO Detector into the Control Panel, you have to connect it to AC (mains) power first. Please follow below steps to proceed.

**Step 1.** Before you start, find the circuit breaker or fuse box.

**Step 2.** Once you have found it, open the door and turn off the main power switch.

**Step 3.** Two Wago 221 Splicing Connectors are provided. Take out one connector. Pull the lever up and insert the white wire. **Step 4.** Push the lever back down. The transparent housing allows you to check if the wire is connected properly. **Make sure the wire is tightly held in place before you proceed.**

**Step 5.** Repeat Steps 3 and 4 to insert the black wire. Inserting the two wires to the same side (right), as shown below, of the two connectors provides an easier installation in the following steps.

**Step 6.** Insert the AC wires to the two connectors respectively, as shown below. If you turn the Battery Switch to ON position, the rechargeable battery will begin to charge.



![Figure 1. Insert the white and the black wires.](<.gitbook/assets/8 (68).png>)

![Figure 2. Check if the wires are connected properly.](<.gitbook/assets/9 (66).png>)



![Figure 3. Insert the AC wires.](<.gitbook/assets/10 (62).png>)

**Step 7.** Turn the SDCO Detector over. You will hear “Welcome, Smoke Alarm and Carbon Monoxide Detector”, indicating it is ready for further setup (for serial connected models only).

* The SDCO Detector allows users to set up a location prompt for an area, to view the full list of locations and setup instructions, please refer to “_**Voice Prompt**_” Section for details. It is recommended to perform warm-up and calibration process **before** including your device into the Z-Wave coordinator.

**\<Warm-up and calibration>**

1. The SDCO Detector will emit 2 short beeps, and begin warm up process for **1** minute. LED will flash every 2 seconds.
2. When 1-minute warm up period expires, the SDCO Detector will emit a beep to indicate it now enters calibration process. The calibration process takes 1\~7 minutes; the LED will continue to flash during calibration.
3. When calibration is complete, the SDCO Detector will emit a 2-tone sound and LED will stop flashing to indicate it is now under normal operation. If calibration fails, the SDCO Detector will sound continuous beeps.

**\<Including to the Z-Wave coordinator>**

1. Put the Z-Wave gateway or control panel into Inclusion mode (please refer to the Z-Wave gateway or control panel manual).
2. Within 1.5 seconds, press the button 3 times.
3. Refer to the operation manual of the Z-Wave gateway or control panel to complete the inclusion process.
4. If the sensor has already been included into another Z-Wave Gateway/Control Panel, or if the sensor is unable to be included into the current Z-Wave Gateway/Control Panel, please exclude it first (see Exclusion) before attempting to include it into the current Z-Wave Gateway/Control Panel.

### **SmartStart Inclusion**

![](<.gitbook/assets/11 (30).jpeg>)

Z-Wave SmartStart utilizes the DSK of the device to enhance and simplify the inclusion process. DSK is Device Specific Key used for authentication communication. The DSK information is stored in the QR code format that is printed on a label and adhered to the exterior of the device.

With a Z-wave Controller providing SmartStart inclusion, the SmartStart enabled device can be added into a Z-Wave network by scanning the Z-Wave QR Code on the product. Without any further action the device will be added automatically within 10 minutes of being switched on in the network vicinity.

* Put the Z-Wave gateway or control panel into **Inclusion mode** (please refer to the Z-Wave gateway or control panel manual).
* Scan the QR Code on the SDCO Detector to retrieve **DSK**.
* Power on the SDCO Detector, a SmartStart inclusion request will be automatically sent to the gateway.
* The gateway will automatically include the device upon recognition of the device by matching the inclusion request with the DSK obtained
  * The DSK of the device is used only during inclusion.
  * The DSK can be read without powering ON the SDCO Detector, so it is possible to prepare the gateway to include the device prior to installing and powering up the SDCO Detector.
  * If the device has already been added (included) into another Z-Wave Gateway/Control Panel, please exclude it first (see _**Removing Device**_) before attempting to include it into the current Z-Wave Gateway/Control Panel. The device will not send a

SmartStart inclusion request if it’s already in a Z-Wave Gateway/Control Panel.

## _**Removing Device (Exclusion)**_

The SDCO Detector must be removed from existing Z-Wave network before being included into another.

* Put the Z-Wave gateway or control panel into Exclusion mode (please refer to the Z-Wave gateway or control panel manual).
* Within 1.5 seconds, press the button 3 times and the SDCO Detector will be removed from the Z-Wave network.

## _**Voice Prompt (for serial connection models)**_

The SDCO Detector allows the user to set up a location prompt for an area (e.g., kitchen or basement). When an alarm is triggered, the SDCO Detector will play the pre-programmed voice prompt to alert the user to evacuate. For first-time setup, please follow the steps below:

**Step 1.** Turn on the battery switch.

**Step 2.** Prompt #1 “Welcome, Smoke Alarm and Carbon Monoxide Detector” will be played.

**Step 3.** Prompt #2 “No location programmed” will be played.

**Step 4.** Prompt #3 “To select location, press and hold the button now” will be played.

**Step 5.** Keep holding the button and prompt #4 “To program location, press and hold the button after location is heard” will be played. **Step 6.** Keep holding the button and prompt #6 “Location” will be played followed by locations for selection (from Prompt #11-31).

**Step 7.** To setup a desired location prompt, simply release the button.

**Step 8.** The device will play prompt #7 “Programmed” after you release the button and emit 2 beeps for confirmation.

<figure><img src=".gitbook/assets/10 (4) (1) (1).png" alt=""><figcaption></figcaption></figure>

<figure><img src=".gitbook/assets/11 (2) (1).png" alt=""><figcaption></figcaption></figure>

* When a CO, smoke, and/ or temperature alarm is triggered, the siren will be activated according to the time length below and followed by voice prompts to notify the user to evacuate.

<figure><img src=".gitbook/assets/12 (2).png" alt=""><figcaption></figcaption></figure>

## _**Fire Verification**_

* Fire verification can be used to set up verification timer using Z-Wave’s Configuration Command for the SDCO Detector. When fire verification timer is set, the SDCO Detector will begin to count down fire verification timer when the device is triggered. Up to 150 seconds can be set (Default: 0 second). Please refer to page 10 **“Configurations”** section for details.
* If fire verification function is enabled, the Red LED will flash quickly for 3 times every 8 seconds if smoke is detected during this period. After fire verification timer expires, the SDCO Detector will activate fire alarm if smoke concentration exceeds the detection threshold.

## _**Alarm Detection**_

The SDCO Detector will activate fire alarm when either of its smoke detection or high heat detection function is triggered. When an alarm is activated, the SDCO Detector will transmit alarm signal and raise alarm with its built in buzzer, the Red LED will flash rapidly.

**Smoke Detection:**

* The SDCO Detector checks smoke concentration every 8 seconds
* Whenever the smoke concentration exceeds the detection threshold, SDCO Detector will send active signal to the Control Panel, and activate the alarm.
* If the smoke concentration persists, the SDCO Detector will continue to send the active signal every minute to the Control Panel.
* If no smoke is detected for 20 continuous detection times, the SDCO Detector will transmit a restore signal.

**Heat Detection:**

* The SDCO Detector checks temperature every 10 seconds.
* The alarm will be activated in the following conditions:
  * When the temperature rises by 8.25°C per minute (Rate of Rise).
  * When the temperature exceeds 57.25°C (High Heat).
* If no high heat is detected for 16 continuous detection times, the SDCO Detector will transmit a restore signal.
* If the alarm was triggered by High Heat condition (57.25°C), the temperature must drop below 49°C for detector to stop alarming.

**Carbon Monoxide Detection:**

1. The CO sensor will check the CO concentration level every 16 seconds, if the concentration level exceeds the detection threshold, the SDCO Detector will transmit alarm signal and raise alarm with its built in buzzer.
2. The CO sensor features self-diagnosis function and will regularly check the health or status of the sensor every 12 hours.
3. The alarm will be activated after CO concentration is detected according to time length in the following table: (compliant with EN-50291 standard)

<figure><img src=".gitbook/assets/10 (1) (1) (1) (1) (1) (1).png" alt=""><figcaption></figcaption></figure>

4\. The alarm will be activated after CO concentration is detected according to time length in the following table: (compliant with UL-2034 standard)

<figure><img src=".gitbook/assets/11 (1) (1) (1) (1) (1) (1) (1).png" alt=""><figcaption></figcaption></figure>

5. Once the CO concentration level exceeds the threshold and persists for the time length as listed in the above table, the SDCO Detector will transmit the signal to Z-Wave coordinator and raise alarm with its built-in siren.
6. If CO drops below 30ppm for 10 continuous detection times, the SDCO will transmit a restore signal.

**Temperature and Humidity Detection:**

The Temperature and Humidity Sensor will transmit temperature and humidity signals regularly according to setting. The factory default interval is 30 to 33 minutes.

* The SDCO Detector will send temperature signal when temperature changes by +/- 2°C.
* You can also press the button once to transmit a temperature signal manually.

## _**IR Detection**_

* The SDCO Detector will transmit signal to the Control Panel if any movement is picked up within the IR detection coverage. The buzzer will not sound and the LED will not flash. Please refer to your Control Panel for details.
* In 60 seconds, if there is no further motion detection or alerts, the IR will be restored and return to normal operation.

## _**Testing the SDCO Detector**_

By pressing the button on the SDCO Detector, you can test if the SDCO Detector is functioning normally.

* If the SDCO Detector functions normally, the Red LED will flash once followed by a 2-tone beep.
* If three 2-tone beeps (DO-DI DO-DI DO-DI) are emitted, it means the Smoke Sensor is out-of-order.
* If 5 beeps (DO-Bi-Bi-Bi-DO) are emitted, it means the Heat Sensor is out-of-order.
* If 7 beeps (Bi-Bi-Bi-DO-Bi-Bi-Bi) are emitted, it means the CO Sensor is out-of-order.

## _**Alarm Silence**_

* There are two ways to manually put the SDCO into Alarm Silence mode: pressing the button or sending **Scene/Siren Control or Siren On/ Off Control** command. By either method, the SDCO will enter Alarm Silence mode. After the period, a restore signal will be sent. Please refer to page 8 **“Smoke Emergency/Smoke Emergency Cleared**_**, Heat Emergency Cleared, and CO Emergency/**_**&#x20;CO Emergency Cleared”** section for details.

**Pressing the Button:**

* When the Smoke Detector is alarming, pressing the button will put the Smoke Detector into Alarm Silence mode to silence the alarm.

**Sending Scene/Siren Control or Siren On/Off Control command:**

* Scene/Siren Control command allows you to program different alarm types with location indication. **Please note this command CANNOT be used to stop the siren and voice prompts of a real alarm.**
* To turn off the siren and voice prompts by using this command, set Basic Set: 0x00. The SDCO Detector will then enter Alarm Silence mode.
* Siren On/Off Control command allows you to control the siren of a smoke alarm. **Please note this command CANNOT be used to stop the siren and voice prompts of a real alarm.**
* To turn off the siren by using this command, set Basic Set: 0x00. The SDCO Detector will then enter Alarm Silence mode.
* During the Alarm Silence period, the Red LED will flash once per second. The Smoke Detector will continue to monitor smoke concentration during the alarm silence period:

1. After the Alarm Silence period has expired, if the smoke concentration has dropped below alarm threshold, the Smoke Detector will emit a 2-tone beep and return to normal operation without sounding alarm.
2. If smoke concentration still exceeds alarm threshold, the Smoke Detector will start alarming again.
3. If smoke concentration continues to rise during Alarm Silence period and exceeds a second alarm threshold, the SDCO Detector will start alarming again. An alarm activated by exceeding the second alarm threshold could be silenced by pressing the button.

## _**Recalibration**_

The SDCO Detector will calibrate its smoke detector sensor every time when power is applied to ensure optimal smoke sensitivity. After installation, the operation condition of the Smoke Detector may vary after some time, which may affect its smoke detection function and requires recalibration. There are two ways to recalibrate the Smoke Detector: auto calibration and manual calibration.

**Auto Calibration:**

* After being powering up, the Smoke Detector will perform auto-calibration after 4 hours.
* After the first auto-calibration, the Smoke Detector will perform auto calibration every month. During the auto-calibration process, the Smoke Detector will not emit any sound.
* If auto-calibration fails, the Amber LED will flash every second along with continuous beeps.
* When Smoke Detector auto calibration fails, the smoke alarm function will still work normally using the threshold value taken from the last successful calibration.

**Manual Calibration:**

* Manual calibration can be performed any time as desired:
  1. Press and hold the button for 10 seconds and release when the Smoke Detector emits 2 beeps.
  2. The Smoke Detector will enter calibration process. The LED Indicator will flash every 2 seconds.
  3. After the Smoke Detector finishes recalibration, it will emit two quick beeps to indicate. The LED will turn off.
  4. If calibration process fails, Smoke Detector will emit alarm sound. Please remove and reinsert battery to restart process again.

## _**Identifying the Device**_

The function is available for you to identify the SDCO Detector among your devices by sending Z-Wave commands to the Gateway. If the device receives signal successfully, the device LED will begin to flash. The number of flashing cycles is programmable by using Z-Wave Indicator CC commands. Please refer to “_**Command Class Data Format”**_ section for details.

## _**Factory Reset**_

_(Only use factory reset when network Control Panel/Gateway is missing or inoperable)._

* Press and hold the button on the SDCO Detector for 20 seconds. Release the button when you hear 3 beeps to perform factory reset.

{% hint style="warning" %}
Note:

Factory resetting the SDCO will restore it to factory default settings (excluded from the Z-Wave network). The Z-Wave gateway or control panel will still keep its Z-Wave settings. Please refer to the gateway or control panel manual on how to remove the SDCO’s Z-Wave settings.
{% endhint %}

## **Maintenance & Cleaning**

Regular maintenance and cleaning will help keep your SDCO Detector in good working order.

* Test the SDCO Detector weekly to verify that the alarm sounds and indicators are working properly.
* Clean the SDCO Detector at least once every 6 months.
  * Gently vacuum off the dirt/dust/small particles accumulated in the smoke detection chamber and slots.
  * Clean the casing by swiping it thoroughly with a damp cloth and dry it. Do not get water inside the alarm.
  * Never use cleaning agents, detergents or solvents on the detector.
* Avoid spraying air freshener, hair spray, or other aerosols near the SDCO Detector.
* Do not paint nor modify the detector under any circumstances.

## **Expiration**

The SDCO Detector has a maximum life time of **10 years** from the date of installation. You should replace the SDCO Detector immediately after 10 years of service.

It is recommended writing the “Replace by” date (10 years from installation date) on the back of the detector prior to installation.

## **Installation**

### _**Installation Guideline**_

* It is recommended installing the device in the center area of the ceiling. When mounted on the ceiling, the PIR has better detection performance against horizontal movement.
* The ideal mounting height for the SDCO Detector is 2.4 meters to 3 meters. Mounting above 3 meters may affect detection performance.
* Do not install the detector in the following locations:
  * The Kitchen – Smoke from cooking might cause an unwanted alarm.
  * Near a ventilating fan, fluorescent lamp or air conditioner – air drafts from them may affect the sensitivity of the detector.
  * Near ceiling beams or over a cabinet – stagnant air in these areas may affect the sensitivity of the detector.
  * In the peak of an “**A**” frame type of ceiling.

<figure><img src=".gitbook/assets/10 (3) (1) (1) (1).png" alt=""><figcaption></figcaption></figure>

* The SDCO Detector can support detection coverage within a radius of 4 meters.

<figure><img src=".gitbook/assets/10 (2) (1) (1) (1) (1).png" alt=""><figcaption></figcaption></figure>

### _**Installation Recommendation**_

* **Limitations**
  * Do not expose the SDCO Detector to direct sunlight.
  * Avoid installing the SDCO Detector in areas where devices such as air conditioners or heaters may cause rapid change in temperature in the detection area.
  * Avoid large obstacles in the detection area.
  * Do not point directly at sources of heat, e.g., fires or boilers, and not above radiators.

## _**Mounting the SDCO Detector**_

**Step 1.** Before you start, find the circuit breaker or fuse box.

**Step 2.** Once you have found it, open the door and turn off the main power switch.

**Step 3.** Place the SDCO Detector at desired mounting location and use Range Test to make sure the SDCO can be received by the Control Panel at mounting location.

**Step 4.** Two Wago 221 Splicing Connectors are provided. Take out one connector. Pull the lever up and insert the white wire.

**Step 5.** Push the lever back down. The transparent housing allows you to check if the wire is connected properly. **Make sure the wire is tightly held in place before you proceed.**

**Step 6.** Repeat Step 4 and Step 5 to insert the black wire. Inserting the two wires to the same side (right), as shown below, of the two connectors provides an easier installation in the following steps.

**Step 7.** Insert the AC wires to the two connectors respectively, as shown below.

<figure><img src=".gitbook/assets/10 (4) (1) (1) (1).png" alt=""><figcaption></figcaption></figure>

**Step 8.** The SDCO Detector has a mounting bracket for ceiling installation. The bracket provides bidirectional flexibility.

**Step 9.** Use the 4 holes on the bracket as template to drill holes and insert wall plugs if required.

**Step 10.** The user can either rotate the mounting bracket clockwise or counterclockwise to lock the hook. Ensure the wall plugs are flush with the mounting surface.

**Step 11.** Once the position is satisfactory, screw the mounting bracket onto the ceiling.

**Step 12.** Wipe away dust thoroughly, or it can make the sensor dirty and prevent it from operating properly in case of an emergency.

**Step 13.** Use a Phillips screwdriver to remove the battery compartment fixing screw. Remove the battery compartment cover and attach the cable to the PCB board of the SDCO Detector. The foolproof design provides an easy installation procedure.

<figure><img src=".gitbook/assets/10 (5) (1) (1).png" alt=""><figcaption></figcaption></figure>

**Step 14.** Put the two Splicing Connectors in the space next to the rechargeable battery.

**Step 15.** Replace the battery compartment cover in its proper place and tighten the fixing screw. The pre-punched hole on the cover enhances its flexibility.

**Step 16.** The SDCO has three notches on its back cover (as shown below) for hooking the device on the mounting bracket.

**Step 17.** Hold the SDCO Detector with extra care and hook the detector onto the mounting bracket.

**Step 18.** Rotate the SDCO Detector clockwise to lock the hook. Installation is now complete.

**Step 19.** Turn on the main power switch for further operation.

## **Z-Wave Information**

**Device Type:** Sensor Notification Smoke Alarm

**Role Type:** Always On Slave (AOS)

**Manufacturer ID:** 0x018E

**Product Type ID :** 0x0003

**Product ID:** 0x0115

**Max Association Group:** 3

**Supported Command Class :**

<figure><img src=".gitbook/assets/10 (6) (1) (1).png" alt=""><figcaption></figcaption></figure>

<figure><img src=".gitbook/assets/11 (2) (1) (1).png" alt=""><figcaption></figcaption></figure>

### _**Z-Wave’s Groups (Association Command Class Version 2)**_

Group 1 for “LifeLine”: (max node : 5)

Battery CC (COMMAND\_CLASS\_BATTERY)

SensorMutilevel CC, V11 (COMMAND\_CLASS\_SENSOR\_MULTILEVEL)

Notification CC,V8 (COMMAND\_CLASS\_NOTIFICATION)

Basic CC(COMMAND\_CLASS\_BASIC)

Device Reset Locally CC (COMMAND\_CLASS\_DEVICE\_RESET\_LOCALLY)

Group 2 for “Sensor Basic set”: (max node : 5)

Basic CC (COMMAND\_CLASS\_BASIC)

When the Smoke Detector is active, it will send Basic Set (0xFF) in Group 2.

When the Smoke Detector is restored, it will send Basic Set (0x00) in Group 2.

Group 3 for “Scene set”: (max node : 5)

Scene Activation CC (COMMAND\_CLASS\_SCENE\_ACTIVATION)

After Group 3 is added, it will send Scene Activation Command when SC, HD or CO alarms.

After Group 3 is added, it will send Scene Activation Command when SC, HD or CO is restored.

Please refer to _Table 2_ Siren Control, it will send 00 00 when the Smoke Detector is restored.

### _**Command Class Data Format**_

#### **AC Failure/Restore: \[COMMAND\_CLASS\_NOTIFICATION] \[NOTIFICATION\_REPORT]**

* When an AC power failure is detected, the SDCO will send an AC failure signal to the Control Panel. When AC power is restored, the SDCO will send a restore signal to the Control Panel.
* AC Failure: 00 00 00 FF 08 02 00 00
* AC Restore: 00 00 00 FF 08 03 00 00

#### **Battery: \[COMMAND\_CLASS\_BATTERY] \[BATTERY\_REPORT]**

* 0x64 --- 100% Battery Full
* 0x5A --- 90% Battery
* 0x50 --- 80% Battery
* 0x46 --- 70% Battery
* 0x3C --- 60% Battery
* 0x32 --- 50% Battery
* 0x28 --- 40% Battery
* 0x1E --- 30% Battery
* 0x14 --- 20% Low Battery
* 0xFF --- Battery Dead (Cut Off)
* Cut Off --- The device will stop working and both Red and Amber LEDs will flash every 4 seconds.
* If the battery switch is set as OFF, the SDCO will send 00% to notify the user. Please note when set as OFF, the battery will not be charged when AC power is connected and nor will it serve as a backup power source when AC power is missing.
* When AC power is applied, the rechargeable battery will be charging at the same time, and the SDCO will report its battery percentage to the Gateway/Control Panel respectively at 20%, 30%, 40%, 50%, 60%, 70%, 80%, 90%, and 100%.
* When AC power is removed or power failure takes place, the SDCO will use its built-in rechargeable battery and report its battery percentage. After AC power is reapplied, the SDCO will report its battery percentage detected. When the battery voltage detected is 4.3V or above, the SDCO will report its battery percentage at 60% and begin to charge the battery. When the battery voltage detected is under 4.3V, the SDCO will report its battery percentage respectively and begin to charge the battery.

#### **Temperature/Humidity Report: \[COMMAND\_CLASS\_SENSOR\_MULTILEVEL] \[SENSOR\_MULTILEVEL\_REPORT]**

* The user can press the button once to send temperature and humidity information to the Control Panel.
* Temperature: 01 42 08 CC
* If temperature signal 01 42 **08 CC** is transmitted:

**08CC** can be viewed as 0x**08CC** in Hexadecimal number. You can convert hexadecimal to decimal and divide by 100 to check the temperature data (in Celsius).

0x08CC=2252=25.52℃.

* Humidity: 05 02 00 3C
* If humidity signal 05 02 **00 3C** is transmitted:

**003C** can be viewed as 0x**003C** in Hexadecimal number. You can convert hexadecimal to decimal to check the humidity level (in percentage).

003C=0x003C=60%

#### **Smoke Alarm Test/Smoke Alarm Test Deactivated:: \[COMMAND\_CLASS\_NOTIFICATION] \[NOTIFICATION\_REPORT]**

* The user can press the Button once to send smoke alarm test and smoke alarm test deactivated signals to the Control Panel.
* Smoke Alarm Test: 00 00 00 FF 01 03 00
* Smoke Alarm Test Deactivated: 00 00 00 FF 01 00 01 03
* 01=alarm type; 03=smoke alarm test

#### **Smoke Emergency/Smoke Emergency Cleared: \[COMMAND\_CLASS\_NOTIFICATION] \[NOTIFICATION\_REPORT]**

Smoke Alarm: 00 00 00 FF 01 01 0B 77 06 00 42 61 73 65 6D 65 6E 74

Note: 0B 77 06 00 42 61 73 65 6D 65 6E 74 is when the location is “Basement”.

* A smoke alarm will be activated after the smoke concentration exceeds the detection threshold, or either manually activated by sending commands, the SDCO can be silenced and enter Alarm Silence mode. Please refer to “_**Alarm Silence**” section for details._ The SDCO will send an alarm silence report in the following three conditions:
* When the smoke concentration has dropped below alarm threshold, the SDCO will send: 00 00 00 FF 01 06 01 01
* When the user presses the button to stop the alarm, the SDCO will send: 00 00 00 FF 01 06 01 02
* When the user sends a siren off command to stop the alarm, the SDCO will send: 00 00 00 FF 01 06 01 03 Please refer to “Siren On/Off Control Command” for details
* Note: If multiple alarms are activated, the alarm silence events will be sent respectively
* After the SDCO is silenced, if no smoke is detected for 20 continuous detection times, the SDCO will transmit a restore signal:  \
  00 00 00 FF 01 00 01 01.

#### **Heat Emergency/Heat Emergency Cleared: \[COMMAND\_CLASS\_NOTIFICATION] \[NOTIFICATION\_REPORT]**

Heat Alarm: 00 00 00 FF 04 01 0B 77 06 00 42 61 73 65 6D 65 6E 74

Note: 0B 77 06 00 42 61 73 65 6D 65 6E 74 is when the location is “Basement”

* A heat alarm will be activated after the SDCO meets the Rate of Rise or High Heat condition, or either manually activated by sending commands, the SDCO can be silenced and enter Alarm Silence mode. Please refer to “_**Alarm Silence**” section for details._ The SDCO will send an alarm silence report in the following three conditions:
* When the temperature has dropped below alarm threshold, the SDCO will send: 00 00 00 FF 04 09 01 01
* When the user presses the button to stop the alarm, the SDCO will send: 00 00 00 FF 04 09 01 02
* When the user sends a siren off command to stop the alarm, the SDCO will send: 00 00 00 FF 01 06 01 03 Please refer to “Siren On/Off Control Command” for details.ù
* Note: If multiple alarms are activated, the alarm silence events will be sent respectively.
* After the SDCO is silenced, if no high heat is detected for 16 continuous detection times, the SDCO will transmit a restore signal: 00 00 00 FF 04 00 01 01.

#### **CO Emergency/CO Emergency Cleared: \[COMMAND\_CLASS\_NOTIFICATION] \[NOTIFICATION\_REPORT]**

CO Alarm: 00 00 00 FF 02 01 0B 77 06 00 42 61 73 65 6D 65 6E 74

Note: 0B 77 06 00 42 61 73 65 6D 65 6E 74 is when the location is “Basement”.

* A CO alarm will be activated after the CO concentration exceeds the detection threshold, or either manually activated by sending commands, the SDCO can be silenced and enter Alarm Silence mode. Please refer to “_**Alarm Silence**” section for details._ The SDCO will send an alarm silence report in the following three conditions:
* When the CO concentration has dropped below 30ppm, the SDCO will send: 00 00 00 FF 02 06 01 01
* When the user presses the button to stop the alarm, the SDCO will send: 00 00 00 FF 02 06 01 02

**Please note an alarm activated by exceeding the second alarm threshold can be silenced by pressing the button.**

* When the user sends a siren off command to stop the alarm, the SDCO will send: 00 00 00 FF 01 06 01 03
* Note: If multiple alarms are activated, the alarm silence events will be sent respectively.
* After the SDCO is silenced, if CO drops below 30ppm for 10 continuous detection times, the SDCO will transmit a restore signal: 00 00 00 FF 02 00 01 01.

#### **Location:**

* When a smoke alarm, heat alarm, or CO alarm is triggered, it will send notification with the location name. For serial connected models, pre-programmed location will also be transmitted.
* If a smoke alarm is triggered in the basement, 00 00 00 FF 01 01 **0B 77 06 00 42 61 73 65 6D 65 6E 74** will be sent, as shown in Table 1 below

_**Table 1**_

<figure><img src=".gitbook/assets/10 (7) (1).png" alt=""><figcaption></figcaption></figure>

<figure><img src=".gitbook/assets/11 (3).png" alt=""><figcaption></figcaption></figure>

#### **Tamper Open/Close report: \[COMMAND\_CLASS\_NOTIFICATION] \[NOTIFICATION\_REPORT]**

* The SDCO is protected by a tamper switch which is compressed when the SDCO is hooked onto the mounting bracket. When the SDCO is removed from the mounting bracket, the tamper switch will be activated and the SDCO will send a tamper open signal to the system control panel to remind the user of this condition.
* Tamper Open :00 00 00 FF 07 03 00 00
* After the SDCO is hooked onto the mounting bracket, it will send a tamper close signal to the control panel.
* &#x20;Tamper Close:00 00 00 FF 07 00 01 03

#### **PIR Sensor**

* The SDCO will transmit signal to the Control Panel if any movement is picked up within the IR detection coverage.
* PIR Active: 00 00 00 FF 07 07 0B 77 06 00 42 61 73 65 6D 65 6E 74
* Note: 00 00 00 FF 07 07 0B 77 06 00 42 61 73 65 6D 65 6E 74 is when the location is “Basement”.
* PIR Restore: 00 00 00 FF 07 00 01 07

#### **Scene/Siren Control: \[COMMAND\_CLASS\_SCENE\_ACTIVATION] \[SCENE\_ACTIVATION\_SET] (for serial connected models):**

* Scene ID: Alarm type (Table 2)
* Dimming Duration: 0x00\~0x14

_**Table 2**_

<figure><img src=".gitbook/assets/10 (8) (1).png" alt=""><figcaption></figcaption></figure>

* Location name /Bit4\~0/Num, as shown in Table 3 below

_**Table 3**_

<figure><img src=".gitbook/assets/10 (9) (1).png" alt=""><figcaption></figcaption></figure>

<figure><img src=".gitbook/assets/11 (4).png" alt=""><figcaption></figcaption></figure>

* To activate the door chime, set Scene ID: 0x00 and Dimming Duration: 0xF1.
* To stop the siren and voice prompts generated by this command, set Scene ID: 0x00 and Dimming Duration: 0x00. **Please note this command CANNOT be used to stop the siren and voice prompts of a real alarm.**
* To stop the siren and voice prompts of a real alarm, set Scene ID: 0xFF and Dimming Duration: 0x00.

#### **Siren On/Off Control: \[COMMAND\_CLASS\_BASIC] \[BASIC\_SET]**

* The siren of SDCO can be controlled by using Basic Set On/Off commands (for smoke alarm only, without location indication).
* To turn on the siren by using this command, set Basic Set: 0xFF. The sounding pattern of the siren is the same as that of a smoke alarm.
* To turn off the siren by using this command, set Basic Set: 0x00. **Please note this command CANNOT be used to stop the siren of a real alarm.** The SDCO will enter Alarm Silence mode and will send alarm restore signal after the period.

#### **Indicator** Control **: \[COMMAND\_CLASS\_INDICATOR] \[INDICATOR\_SET]**

* The LED indicator of SDCO can be controlled by using Indicator Set commands.
* The following commands can be used to set the indicator command:

<figure><img src=".gitbook/assets/10 (10) (1).png" alt=""><figcaption></figcaption></figure>

* Indicator set on (0xFF) --- indicator function on
* Indicator set off (0x00) --- indicator function off
* Indicator Object Count (0x01) --- to control LED indicator ID 1
* Indicator ID (0x43) --- button indication

<figure><img src=".gitbook/assets/10 (11).png" alt=""><figcaption></figcaption></figure>

* Indicator ID (0x44) --- MCU reboot

<figure><img src=".gitbook/assets/11 (5).png" alt=""><figcaption></figcaption></figure>

* Property ID (0x00-0xFE) --- LED on\_off times

<figure><img src=".gitbook/assets/12 (1) (1) (1) (1) (1).png" alt=""><figcaption></figcaption></figure>



* If you would like the SDCO to flash 5 times to show its location, send: 0xFF 01 43 04 05
* If you would like the SDCO to stop flashing once you are aware of its location, send: 0x00 01 43 04 05
* For more details, please refer to “_**SDS-13781-1 Z-Wave Application Command Class Specification**_”.

#### **Configurations: \[COMMAND\_CLASS\_CONFIGURATION] \[CONFIGURATION\_SET]**

 Parameter Number: 0x01\~0x0A

 Size: 0x01

 Reserved: 0x00

 Default: 0x00

 Configuration Value: 0xXX

<figure><img src=".gitbook/assets/13 (1) (1).png" alt=""><figcaption></figcaption></figure>

<figure><img src=".gitbook/assets/10 (12).png" alt=""><figcaption></figcaption></figure>

 _**Table 4**_ 0x09 (Hardware Fault)

<figure><img src=".gitbook/assets/11 (6).png" alt=""><figcaption></figcaption></figure>

 SD Broken: If Bit0=1, it will send a Notification Command “00 00 00 FF 01 FE 00”\
 HD Broken: If Bit1=1, it will send a Notification Command “00 00 00 FF 04 FE 00”\
 CO Broken: If Bit2=1, it will send a Notification Command “00 00 00 FF 02 FE 00”

 Table 5 0x10 (Temporary Snooze)

<figure><img src=".gitbook/assets/12 (2) (1).png" alt=""><figcaption></figcaption></figure>

#### **Factory Reset**

If the device is learned and the Test Button is pressed and held for 20 seconds along with 3 beeps for the Factory Reset, it will send

\[COMMAND\_CLASS\_DEVICE\_RESET\_LOCALLY] \[DEVICE\_RESET\_LOCALLY\_NOTIFICATION]

 The device will be automatically excluded for the new version of PC Controller.
