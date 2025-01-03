# VESTA 309

![](<.gitbook/assets/0 (70).png>)**Smoke and Carbon Monoxide Detector (SDCO-3-RhTHM-ZW-SC-AC-OTA) Introduction**

SDCO-3-RhTHM-ZW-SC-AC-OTA is a Z-Wave Smoke and Carbon Monoxide Detector with built-in PIR Sensor, temperature, humidity, and heat detection, as well as voice prompts and allows access to the “S2 Unauthenticated” class and supports both of Z-Wave SmartStart Inclusion and classic Inclusion. It is capable of sending wireless signals to the Z-Wave gateway/control panel upon detection of smoke particles or Carbon Monoxide. The device is also serially connected with other sensors in the Z-Wave gateway to serve as an extra siren. When any other sensor in the Z-Wave network is activated and sends an alarm signal, the Smoke Detector will also raise alarm with its built-in buzzer as a siren to help sound warning (for serial connection models).

The SDCO-3 is designed to be mounted on ceiling or top of stairwells when smoke would concentrate to raise alarm timely and protect your home from fire hazards.

The SDCO Detector is a Z-Wave enabled device and is fully compatible with any Z-Wave enabled network. Z-Wave is a wireless communication protocol that uses a low-power RF radio.

![](<.gitbook/assets/1 (83).png>)

_**Parts Identification**_

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

1

1. **Buzzer**
2. **Mounting Holes**
3. **Mounting Bracket**
4. **Tamper Switch**
5. **Battery Compartment Cover**
6. **Battery Switch (Inside)**
7. **Pre Punched Hole for Wiring**
8. **Battery Compartment Cover Fixing Screw**
9. **Notches**
10. **Firmware Update Port (USB Type-C)**
    * For firmware update with customized cable only. **Please note:** Misuse of normal USB Type C cable can result in device malfunction.

**Features**

![](<.gitbook/assets/2 (91).png>)

* _**Battery and Low Battery Detection**_
  * The SDCO-3-RhTHM-ZW-SC-AC-OTA model uses AC 100-240V as its power source and has three 600mAh AAA Ni-MH rechargeable batteries as its backup battery in case of power failure. The battery is included in the package.
  * When the rechargeable battery is charging, the SDCO Detector will report its battery percentage to the Gateway/Control Panel respectively at 100%, 90%, 80%, 70%, 60%, 50%, 40%, 30%, and 20% (low battery).
  * If an AC power failure is detected, the SDCO Detector will send an AC failure report to the Control Panel.
  * When the SDCO Detector is low in battery, a low battery signal will be transmitted along with regular signal transmissions. The Amber LED will flash with accompanying low-volume beep once every 45 seconds.
  * Both Red and Amber LED will flash once every 4 seconds when the battery is exhausted.
* _**Tamper Switch**_
  * The SDCO Detector is protected by a tamper switch which is compressed when the SDCO Detector is hooked onto the mounting bracket. When the SDCO Detector is removed from the mounting bracket, the tamper switch will be activated and the SDCO Detector will send a tamper open signal to the system control panel to remind the user of this condition.
  * The SDCO Detector will send a tamper close signal to the Control Panel after the device is hooked onto the mounting bracket. Please note that the SDCO Detector has to be included in the Z-Wave network first.
* _**Sensitivity Mode**_
  * The device’s sensitivity level can be adjusted using Z-Wave’s Configuration Command. Up to eight levels of sensitivity can be configured (Default: 0x04). Set 0x01 for the highest sensitivity level. Please refer to page 11 **“Configurations”** section for details.
* _**Temporary Snooze Mode**_
  * This function allows you to pause the motion detection function for a specified period of time to avoid unwanted motion alerts without having to disarm the device.
  * By default, the function is disabled, and it can activate by pressing the button for 5 seconds, which enables the mode for 5 minutes. You may also activate the mode using Z-Wave’s Configuration Command, and up to 36 hours can be configured. The snooze mode will be terminated as soon as you press any button or operate the device. Please refer to page 12 **“Configurations”** section for details.
* _**Adding Device (Inclusion)**_

![](<.gitbook/assets/3 (88).png>) ![](<.gitbook/assets/4 (94).png>) ![](<.gitbook/assets/5 (95).png>) ![](<.gitbook/assets/6 (73).png>)

The device supports both classic inclusion process and SmartStart inclusion process.

**Classic Inclusion**

This product can be included and operated in any Z-Wave network with other Z-Wave certified devices from other manufactures and/or applications. All non-battery operated nodes within the network will act as repeaters regardless of vendor to increase network reliability.

* To add the SDCO Detector into the Control Panel, you have to connect it to AC (mains) power first. Please follow below steps to proceed.

**Step 1.** Before you start, find the circuit breaker or fuse box.

**Step 2.** Once you have found it, open the door and turn off the main power switch.

**Step 3.** Two Wago 221 Splicing Connectors are provided. Take out one connector. Pull the lever up and insert the white wire. **Step 4.** Push the lever back down. The transparent housing allows you to check if the wire is connected properly. **Make sure the**

**wire is tightly held in place before you proceed.**

**Step 5.** Repeat Steps 3 and 4 to insert the black wire. Inserting the two wires to the same side (right), as shown below, of the two connectors provides an easier installation in the following steps.

**Step 6.** Insert the AC wires to the two connectors respectively, as shown below. If you turn the Battery Switch to ON position, the rechargeable battery will begin to charge.

![](<.gitbook/assets/7 (67).png>)

_Figure 1. Insert the white and the black wires._

![](<.gitbook/assets/8 (68).png>)

_Figure 2. Check if the wires are connected properly._

![](<.gitbook/assets/9 (66).png>)

_Figure 3. Insert the AC wires._

![](<.gitbook/assets/10 (62).png>)

2

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

**SmartStart Inclusion**

![](<.gitbook/assets/11 (30).jpeg>)

Z-Wave SmartStart utilizes the DSK of the device to enhance and simplify the inclusion process. DSK is Device Specific Key used for authentication communication. The DSK information is stored in the QR code format that is printed on a label and adhered to the exterior of the device.

With a Z-wave Controller providing SmartStart inclusion, the SmartStart enabled device can be added into a Z-Wave network by scanning the Z-Wave QR Code on the product. Without any further action the device will be added automatically within 10 minutes of being switched on in the network vicinity.

*
  * Put the Z-Wave gateway or control panel into **Inclusion mode** (please refer to the Z-Wave gateway or control panel manual).
  * Scan the QR Code on the SDCO Detector to retrieve **DSK**.
  * Power on the SDCO Detector, a SmartStart inclusion request will be automatically sent to the gateway.
  * The gateway will automatically include the device upon recognition of the device by matching the inclusion request with the DSK obtained
    * The DSK of the device is used only during inclusion.
    * The DSK can be read without powering ON the SDCO Detector, so it is possible to prepare the gateway to include the device prior to installing and powering up the SDCO Detector.
    * If the device has already been added (included) into another Z-Wave Gateway/Control Panel, please exclude it first (see _**Removing Device**_) before attempting to include it into the current Z-Wave Gateway/Control Panel. The device will not send a

SmartStart inclusion request if it’s already in a Z-Wave Gateway/Control Panel.

* _**Removing Device (Exclusion)**_

![](<.gitbook/assets/12 (53).png>)

The SDCO Detector must be removed from existing Z-Wave network before being included into another.

*
  * Put the Z-Wave gateway or control panel into Exclusion mode (please refer to the Z-Wave gateway or control panel manual).
  * Within 1.5 seconds, press the button 3 times and the SDCO Detector will be removed from the Z-Wave network.
* _**Voice Prompt (for serial connection models)**_

![](<.gitbook/assets/13 (42).png>)

The SDCO Detector allows the user to set up a location prompt for an area (e.g., kitchen or basement). When an alarm is triggered, the SDCO Detector will play the pre-programmed voice prompt to alert the user to evacuate. For first-time setup, please follow the steps below:

**Step 1.** Turn on the battery switch.

**Step 2.** Prompt #1 “Welcome, Smoke Alarm and Carbon Monoxide Detector” will be played.

**Step 3.** Prompt #2 “No location programmed” will be played.

**Step 4.** Prompt #3 “To select location, press and hold the button now” will be played.

**Step 5.** Keep holding the button and prompt #4 “To program location, press and hold the button after location is heard” will be played. **Step 6.** Keep holding the button and prompt #6 “Location” will be played followed by locations for selection

(from Prompt #11-31).

**.Step 7.** To setup a desired location prompt, simply release the button.

**. ..** **.Step 8.** The device will play prompt #7 “Programmed” after you release the button and emit 2 beeps for confirmation.

| No | Voice Prompt                                                            | Condition                             |   |   |
| -- | ----------------------------------------------------------------------- | ------------------------------------- | - | - |
| 1  | Welcome, Smoke Alarm and Carbon Monoxide Detector                       | Played when the device is powered on. |   |   |
| 2  | No location programmed                                                  | Played for first time setup.          |   |   |
| 3  | To select location, press and hold the button now.                      | Played for location setup.            |   |   |
| 4  | To program location, press and hold the button after location is heard. | Played for location setup.            |   |   |
|    |                                                                         |                                       |   |   |
| 5  | No location programmed                                                  | Played for location setup.            |   |   |
| 6  | Location                                                                | Played for location setup.            |   |   |
| 7  | Programmed                                                              | Played for location setup.            |   |   |

3

| 8  | Emergency, Carbon Monoxide in \[location name]. | Played when an alarm is triggered.   |   |
| -- | ----------------------------------------------- | ------------------------------------ | - |
| 9  | Emergency, Smoke in \[location name].           | Played when an alarm is triggered.   |   |
|    |                                                 |                                      |   |
| 10 | Evacuate                                        | Played when an alarm is triggered.   |   |
| 11 | Basement                                        | Played for location selection.       |   |
| 12 | Hall                                            | Played for location selection.       |   |
| 13 | Office                                          | Played for location selection.       |   |
| 14 | Master Bedroom                                  | Played for location selection.       |   |
| 15 | Bedroom                                         | Played for location selection.       |   |
| 16 | Guest Bedroom                                   | Played for location selection.       |   |
| 17 | Kitchen                                         | Played for location selection.       |   |
| 18 | Dining Room                                     | Played for location selection.       |   |
| 19 | Living Room                                     | Played for location selection.       |   |
| 20 | Laundry                                         | Played for location selection.       |   |
| 21 | Attic                                           | Played for location selection.       |   |
| 22 | Nursery                                         | Played for location selection.       |   |
| 23 | Toilet                                          | Played for location selection.       |   |
|    |                                                 |                                      |   |
| 24 | Technical room                                  | Played for location selection.       |   |
|    |                                                 |                                      |   |
| 25 | Wardrobe                                        | Played for location selection.       |   |
|    |                                                 |                                      |   |
| 26 | Attic living room                               | Played for location selection.       |   |
|    |                                                 |                                      |   |
| 27 | Basement Living Room                            | Played for location selection.       |   |
| 28 | Staircase                                       | Played for location selection.       |   |
| 29 | Garage                                          | Played for location selection.       |   |
| 30 | Rental Apartment                                | Played for location selection.       |   |
| 31 | No Location                                     | Played when no location is selected. |   |

* When a CO, smoke, and/ or temperature alarm is triggered, the siren will be activated according to the time length below and followed by voice prompts to notify the user to evacuate.

|               | Alarm Type |   |                                                 |                                                 | Alarm and Voice Warning Pattern |                                                |                                                 |                                         |                                        |           | Condition |   |   |   |   |   |   |   |   |   |   |
| ------------- | ---------- | - | ----------------------------------------------- | ----------------------------------------------- | ------------------------------- | ---------------------------------------------- | ----------------------------------------------- | --------------------------------------- | -------------------------------------- | --------- | --------- | - | - | - | - | - | - | - | - | - | - |
|               |            |   |                                                 | **(Repeat)**                                    |                                 |                                                | Played after the intermittent warning sound     |                                         |                                        |           |           |   |   |   |   |   |   |   |   |   |   |
|               |            |   |                                                 |                                                 |                                 |                                                |                                                 |                                         |                                        |           |           |   |   |   |   |   |   |   |   |   |   |
|               | Smoke/Heat |   |                                                 | Beep---Beep---Beep------Beep---Beep---Beep      |                                 |                                                | when a smoke or heat alarm is triggered. Please |                                         |                                        |           |           |   |   |   |   |   |   |   |   |   |   |
|               |            |   | Emergency, Smoke in \[location name].           | Location                                        | .                               |                                                |                                                 | note the location prompt will be played |                                        |           |           |   |   |   |   |   |   |   |   |   |   |
|               |            |   |                                                 |                                                 |                                 |                                                |                                                 |                                         |                                        |           |           |   |   |   |   |   |   |   |   |   |   |
|               |            |   |                                                 | Evacuate.                                       |                                 |                                                |                                                 |                                         |                                        |           |           |   |   |   |   |   |   |   |   |   |   |
|               |            |   |                                                 |                                                 |                                 | according to the preprogrammed location name.  |                                                 |                                         |                                        |           |           |   |   |   |   |   |   |   |   |   |   |
|               |            |   |                                                 |                                                 |                                 |                                                |                                                 |                                         |                                        |           |           |   |   |   |   |   |   |   |   |   |   |
|               |            |   |                                                 | **(Repeat)**                                    |                                 |                                                | Played after the intermittent warning sound     |                                         |                                        |           |           |   |   |   |   |   |   |   |   |   |   |
|               |            |   |                                                 |                                                 |                                 |                                                |                                                 |                                         |                                        |           |           |   |   |   |   |   |   |   |   |   |   |
|               | CO         |   |                                                 | Beep-Beep-Beep-Beep                             |                                 |                                                | when a Carbon Monoxide alarm is triggered.      |                                         |                                        |           |           |   |   |   |   |   |   |   |   |   |   |
|               |            |   | Emergency, Carbon Monoxide in \[location name]. |                                                 |                                 | Please note the location prompt will be played |                                                 |                                         |                                        |           |           |   |   |   |   |   |   |   |   |   |   |
|               |            |   |                                                 |                                                 |                                 |                                                |                                                 |                                         |                                        |           |           |   |   |   |   |   |   |   |   |   |   |
|               |            |   |                                                 | Location. Evacuate.                             |                                 |                                                |                                                 |                                         |                                        |           |           |   |   |   |   |   |   |   |   |   |   |
|               |            |   |                                                 |                                                 |                                 | according to the preprogrammed location name.  |                                                 |                                         |                                        |           |           |   |   |   |   |   |   |   |   |   |   |
|               |            |   |                                                 |                                                 |                                 |                                                |                                                 |                                         |                                        |           |           |   |   |   |   |   |   |   |   |   |   |
|               |            |   |                                                 | **(Repeat)**                                    |                                 |                                                |                                                 |                                         |                                        |           |           |   |   |   |   |   |   |   |   |   |   |
|               |            |   |                                                 | Beep---Beep---Beep---Beep-Beep-Beep-Beep-----   |                                 |                                                | Played after the intermittent warning sound     |                                         |                                        |           |           |   |   |   |   |   |   |   |   |   |   |
|               |            |   |                                                 | Beep---Beep---Beep                              |                                 |                                                | when a smoke/heat, and Carbon Monoxide          |                                         |                                        |           |           |   |   |   |   |   |   |   |   |   |   |
| Smoke/Heat+CO |            |   | Emergency, Smoke in \[location name]. Location. |                                                 |                                 | alarm is detected. Please note the location    |                                                 |                                         |                                        |           |           |   |   |   |   |   |   |   |   |   |   |
|               |            |   |                                                 |                                                 |                                 |                                                |                                                 |                                         |                                        |           |           |   |   |   |   |   |   |   |   |   |   |
|               |            |   |                                                 | Evacuate.                                       |                                 |                                                |                                                 |                                         | prompt will be played according to the |           |           |   |   |   |   |   |   |   |   |   |   |
|               |            |   |                                                 | Emergency, Carbon Monoxide in \[location name]. |                                 |                                                | preprogrammed location name.                    |                                         |                                        |           |           |   |   |   |   |   |   |   |   |   |   |
|               |            |   |                                                 | Location. Evacuate.                             |                                 |                                                |                                                 |                                         |                                        |           |           |   |   |   |   |   |   |   |   |   |   |
|               |            |   |                                                 |                                                 |                                 |                                                |                                                 |                                         |                                        |           |           |   |   |   |   |   |   |   |   |   |   |
|               |            |   |                                                 | **(Repeat)**                                    |                                 |                                                | Played                                          | a warning sound                         | when                                   | a Burglar |           |   |   |   |   |   |   |   |   |   |   |
|               | Burglar    |   |                                                 | Alarm sound for 6.5 seconds                     |                                 |                                                |                                                 |                                         |                                        |           |           |   |   |   |   |   |   |   |   |   |   |
|               |            |   |                                                 |                                                 | alarm is detected.              |                                                |                                                 |                                         |                                        |           |           |   |   |   |   |   |   |   |   |   |   |
|               |            |   |                                                 |                                                 |                                 |                                                |                                                 |                                         |                                        |           |           |   |   |   |   |   |   |   |   |   |   |
|               |            |   |                                                 |                                                 |                                 |                                                |                                                 |                                         |                                        |           |           |   |   |   |   |   |   |   |   |   |   |
|               |            |   |                                                 | **(Repeat)**                                    |                                 |                                                | Played                                          |                                         | beeps when a                           | Water     | alarm is  |   |   |   |   |   |   |   |   |   |   |
|               | Water      |   |                                                 | Beep-Beep-Beep-Beep for 6.5 seconds             |                                 |                                                |                                                 |                                         |                                        |           |           |   |   |   |   |   |   |   |   |   |   |
|               |            |   |                                                 |                                                 | detected.                       |                                                |                                                 |                                         |                                        |           |           |   |   |   |   |   |   |   |   |   |   |
|               |            |   |                                                 |                                                 |                                 |                                                |                                                 |                                         |                                        |           |           |   |   |   |   |   |   |   |   |   |   |
|               |            |   |                                                 |                                                 |                                 |                                                |                                                 |                                         |                                        |           |           |   |   |   |   |   |   |   |   |   |   |

![](<.gitbook/assets/14 (41).png>)

* _**Fire Verification**_
  * Fire verification can be used to set up verification timer using Z-Wave’s Configuration Command for the SDCO Detector. When fire verification timer is set, the SDCO Detector will begin to count down fire verification timer when the device is triggered. Up to 150 seconds can be set (Default: 0 second). Please refer to page 10 **“Configurations”** section for details.
  * If fire verification function is enabled, the Red LED will flash quickly for 3 times every 8 seconds if smoke is detected during this period. After fire verification timer expires, the SDCO Detector will activate fire alarm if smoke concentration exceeds the detection threshold.
* _**Alarm Detection**_

![](<.gitbook/assets/15 (42).png>)

The SDCO Detector will activate fire alarm when either of its smoke detection or high heat detection function is triggered. When an alarm is activated, the SDCO Detector will transmit alarm signal and raise alarm with its built in buzzer, the Red LED will flash rapidly.

**Smoke Detection:**

* The SDCO Detector checks smoke concentration every 8 seconds

4

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

 The CO sensor will check the CO concentration level every 16 seconds, if the concentration level exceeds the detection threshold, the SDCO Detector will transmit alarm signal and raise alarm with its built in buzzer.

 The CO sensor features self-diagnosis function and will regularly check the health or status of the sensor every 12 hours.

 The alarm will be activated after CO concentration is detected according to time length in the following table: (compliant with EN-50291 standard)

| **CO concentration level** | **Time taken before alarming** |
| -------------------------- | ------------------------------ |
| 30 +/- 10% ppm             | N/A                            |
| 50 +/- 10% ppm             | 60\~90 minutes                 |
| 100 +/- 10% ppm            | 10\~40 minutes                 |
| 300 +/- 10% ppm            | Under 3 minutes                |

 The alarm will be activated after CO concentration is detected according to time length in the following table: (compliant with UL-2034 standard)

| **CO concentration level** | **Time taken before alarming** |                 |
| -------------------------- | ------------------------------ | --------------- |
| 30                         | +/- 3% ppm                     | N/A             |
| 70                         | +/- 5% ppm                     | N/A             |
| 70                         | +/- 5% ppm                     | 60\~240 minutes |
| 150 +/- 5% ppm             | 10\~50 minutes                 |                 |
| 400                        | +/- 10% ppm                    | 4\~15 minutes   |

 Once the CO concentration level exceeds the threshold and persists for the time length as listed in the above table, the SDCO Detector will transmit the signal to Z-Wave coordinator and raise alarm with its built-in siren.

 If CO drops below 30ppm for 10 continuous detection times, the SDCO will transmit a restore signal.

**Temperature and Humidity Detection:**

The Temperature and Humidity Sensor will transmit temperature and humidity signals regularly according to setting. The factory default interval is 30 to 33 minutes.

*
  * The SDCO Detector will send temperature signal when temperature changes by +/- 2°C.
  * You can also press the button once to transmit a temperature signal manually.
* _**IR Detection**_
  * The SDCO Detector will transmit signal to the Control Panel if any movement is picked up within the IR detection coverage. The buzzer will not sound and the LED will not flash. Please refer to your Control Panel for details.
  * In 60 seconds, if there is no further motion detection or alerts, the IR will be restored and return to normal operation.
* _**Testing the SDCO Detector**_

![](<.gitbook/assets/16 (44).png>) ![](<.gitbook/assets/17 (34).png>)

By pressing the button on the SDCO Detector, you can test if the SDCO Detector is functioning normally.

*
  * If the SDCO Detector functions normally, the Red LED will flash once followed by a 2-tone beep.
  * If three 2-tone beeps (DO-DI DO-DI DO-DI) are emitted, it means the Smoke Sensor is out-of-order.
  * If 5 beeps (DO-Bi-Bi-Bi-DO) are emitted, it means the Heat Sensor is out-of-order.
  * If 7 beeps (Bi-Bi-Bi-DO-Bi-Bi-Bi) are emitted, it means the CO Sensor is out-of-order.
* _**Alarm Silence**_
  * There are two ways to manually put the SDCO into Alarm Silence mode: pressing the button or sending **Scene/Siren Control or Siren On/ Off Control** command. By either method, the SDCO will enter Alarm Silence mode. After the period, a restore signal will be sent. Please refer to page 8 **“Smoke Emergency/Smoke Emergency Cleared**_**, Heat Emergency Cleared, and CO Emergency/**_**&#x20;CO Emergency Cleared”** section for details.

![](<.gitbook/assets/18 (38).png>)

**Pressing the Button:**

* When the Smoke Detector is alarming, pressing the button will put the Smoke Detector into Alarm Silence mode to silence the alarm.

**Sending Scene/Siren Control or Siren On/Off Control command:**

* Scene/Siren Control command allows you to program different alarm types with location indication. **Please note this command CANNOT be used to stop the siren and voice prompts of a real alarm.**
* To turn off the siren and voice prompts by using this command, set Basic Set: 0x00. The SDCO Detector will then enter Alarm Silence mode.
* Siren On/Off Control command allows you to control the siren of a smoke alarm. **Please note this command CANNOT be used to stop the siren and voice prompts of a real alarm.**
* To turn off the siren by using this command, set Basic Set: 0x00. The SDCO Detector will then enter Alarm Silence mode.
* During the Alarm Silence period, the Red LED will flash once per second. The Smoke Detector will continue to monitor smoke concentration during the alarm silence period:
  1. After the Alarm Silence period has expired, if the smoke concentration has dropped below alarm threshold, the Smoke Detector will emit a 2-tone beep and return to normal operation without sounding alarm.

5

*
  1. If smoke concentration still exceeds alarm threshold, the Smoke Detector will start alarming again.
  2. If smoke concentration continues to rise during Alarm Silence period and exceeds a second alarm threshold, the SDCO Detector will start alarming again. An alarm activated by exceeding the second alarm threshold could be silenced by pressing the button.
* _**Recalibration**_

![](<.gitbook/assets/19 (38).png>)

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
* _**Identifying the Device**_

![](<.gitbook/assets/20 (29).png>)

The function is available for you to identify the SDCO Detector among your devices by sending Z-Wave commands to the Gateway. If the device receives signal successfully, the device LED will begin to flash. The number of flashing cycles is programmable by using Z-Wave Indicator CC commands. Please refer to “_**Command Class Data Format”**_ section for details.

* _**Factory Reset**_

_(Only use factory reset when network Control Panel/Gateway is missing or inoperable)._

* Press and hold the button on the SDCO Detector for 20 seconds. Release the button when you hear 3 beeps to perform factory reset.

_\<NOTE>_

* Factory resetting the SDCO will restore it to factory default settings (excluded from the Z-Wave network). The Z-Wave gateway or control panel will still keep its Z-Wave settings. Please refer to the gateway or control panel manual on how to remove the SDCO’s Z-Wave settings.

**Maintenance & Cleaning**

Regular maintenance and cleaning will help keep your SDCO Detector in good working order.

* Test the SDCO Detector weekly to verify that the alarm sounds and indicators are working properly.
* Clean the SDCO Detector at least once every 6 months.
  * Gently vacuum off the dirt/dust/small particles accumulated in the smoke detection chamber and slots.
  * Clean the casing by swiping it thoroughly with a damp cloth and dry it. Do not get water inside the alarm.
  * Never use cleaning agents, detergents or solvents on the detector.
* Avoid spraying air freshener, hair spray, or other aerosols near the SDCO Detector.
* Do not paint nor modify the detector under any circumstances.

**Expiration**

The SDCO Detector has a maximum life time of **10 years** from the date of installation. You should replace the SDCO Detector immediately after 10 years of service.

It is recommended writing the “Replace by” date (10 years from installation date) on the back of the detector prior to installation.

**Installation**

* _**Installation Guideline**_
  * It is recommended installing the device in the center area of the ceiling. When mounted on the ceiling, the PIR has better detection performance against horizontal movement.
  * The ideal mounting height for the SDCO Detector is 2.4 meters to 3 meters. Mounting above 3 meters may affect detection performance.
  * Do not install the detector in the following locations:
    * The Kitchen – Smoke from cooking might cause an unwanted alarm.
    * Near a ventilating fan, fluorescent lamp or air conditioner – air drafts from them may affect the sensitivity of the detector.
    * Near ceiling beams or over a cabinet – stagnant air in these areas may affect the sensitivity of the detector.
    * In the peak of an “**A**” frame type of ceiling.
  * The SDCO Detector can support detection coverage within a radius of 4 meters.

6

* _**Installation Recommendation**_
  * **Limitations**
    * Do not expose the SDCO Detector to direct sunlight.
    * Avoid installing the SDCO Detector in areas where devices such as air conditioners or heaters may cause rapid change in temperature in the detection area.
    * Avoid large obstacles in the detection area.
    * Do not point directly at sources of heat, e.g., fires or boilers, and not above radiators.
* _**Mounting the SDCO Detector**_

**Step 1.** Before you start, find the circuit breaker or fuse box.

**Step 2.** Once you have found it, open the door and turn off the main power switch.

**Step 3.** Place the SDCO Detector at desired mounting location and use Range Test to make sure the SDCO can be received by the Control Panel at mounting location.

**Step 4.** Two Wago 221 Splicing Connectors are provided. Take out one connector. Pull the lever up and insert the white wire.

**Step 5.** Push the lever back down. The transparent housing allows you to check if the wire is connected properly. **Make sure the wire is tightly held in place before you proceed.**

**Step 6.** Repeat Step 4 and Step 5 to insert the black wire. Inserting the two wires to the same side (right), as shown below, of the two connectors provides an easier installation in the following steps.

**Step 7.** Insert the AC wires to the two connectors respectively, as shown below.

_Figure 1. Insert the white and the black wires._

_Figure 2. Check if the wires_

_are connected properly._

_Figure 3. Insert the AC wires._

**Step 8.** The SDCO Detector has a mounting bracket for ceiling installation. The bracket provides bidirectional flexibility.

**Step 9.** Use the 4 holes on the bracket as template to drill holes and insert wall plugs if required.

**Step 10.** The user can either rotate the mounting bracket clockwise or counterclockwise to lock the hook. Ensure the wall plugs are flush with the mounting surface.

**Step 11.** Once the position is satisfactory, screw the mounting bracket onto the ceiling.

**Step 12.** Wipe away dust thoroughly, or it can make the sensor dirty and prevent it from operating properly in case of an emergency.

**Step 13.** Use a Phillips screwdriver to remove the battery compartment fixing screw. Remove the battery compartment cover and attach the cable to the PCB board of theSDCO Detector. The foolproof design provides an easy installation procedure.

**Step 14.** Put the two Splicing Connectors in the space next to the rechargeable battery.

**Step 15.** Replace the battery compartment cover in its proper place and tighten the fixing screw. The pre-punched hole on the cover enhances its flexibility.

**Step 16.** The SDCO has three notches on its back cover (as shown below) for hooking the device on the mounting bracket.

**Step 17.** Hold the SDCO Detector with extra care and hook the detector onto the mounting bracket.

**Step 18.** Rotate the SDCO Detector clockwise to lock the hook. Installation is now complete.

**Step 19.** Turn on the main power switch for further operation.

**Z-Wave Information**

**Device Type:** Sensor Notification Smoke Alarm

**Role Type:** Always On Slave (AOS)

**Manufacturer ID:** 0x018E

**Product Type ID :** 0x0003

**Product ID:** 0x0115

**Max Association Group:** 3

**Supported Command Class :**

| **Command Class**      | **Version** | **Required Security Class**    |
| ---------------------- | ----------- | ------------------------------ |
|                        |             |                                |
| Association            | 2           | Highest Granted Security Class |
|                        |             |                                |
| Association Group Info | 3           | Highest Granted Security Class |
|                        |             |                                |
| Basic                  | 2           | Highest Granted Security Class |
|                        |             |                                |
| Battery                | 1           | Highest Granted Security Class |
|                        |             |                                |
| Sensor Multilevel      | 11          | Highest Granted Security Class |
|                        |             |                                |
| Scene Activation       | 1           | Highest Granted Security Class |
|                        |             |                                |
|                        |             | 7                              |

| Notification               | 8 | Highest Granted Security Class |
| -------------------------- | - | ------------------------------ |
|                            |   |                                |
| Device Reset Locally       | 1 | Highest Granted Security Class |
|                            |   |                                |
| Firmware Update Meta Data  | 5 | Highest Granted Security Class |
|                            |   |                                |
| Manufacture Specific       | 2 | Highest Granted Security Class |
|                            |   |                                |
| Multi Channel              | 4 | Highest Granted Security Class |
|                            |   |                                |
| Multi Channel Association  | 3 | Highest Granted Security Class |
|                            |   |                                |
| Power level                | 1 | Highest Granted Security Class |
|                            |   |                                |
| Switch Binary              | 2 | Highest Granted Security Class |
|                            |   |                                |
| Configuration              | 1 | Highest Granted Security Class |
|                            |   |                                |
| Thermostat Operating State | 2 | Highest Granted Security Class |
|                            |   |                                |
| Version                    | 3 | Highest Granted Security Class |
|                            |   |                                |
| Transport Service          | 2 | None                           |
|                            |   |                                |
| Z-Wave Plus Info           | 2 | None                           |
|                            |   |                                |
| Security                   | 1 | None                           |
|                            |   |                                |
| Security 2                 | 1 | None                           |
|                            |   |                                |
| Supervision                | 1 | None                           |
|                            |   |                                |

* _**Z-Wave’s Groups (Association Command Class Version 2)**_

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

* _**Command Class Data Format**_
  * **AC Failure/Restore: \[COMMAND\_CLASS\_NOTIFICATION] \[NOTIFICATION\_REPORT]**
* When an AC power failure is detected, the SDCO will send an AC failure signal to the Control Panel. When AC power is restored, the SDCO will send a restore signal to the Control Panel.

|  | AC Failure: | 00 00 00 FF 08 02 00 00 |
| - | ----------- | ----------------------- |
|  | AC Restore: | 00 00 00 FF 08 03 00 00 |

* **Battery: \[COMMAND\_CLASS\_BATTERY] \[BATTERY\_REPORT]**
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

8

*
  * When AC power is applied, the rechargeable battery will be charging at the same time, and the SDCO will report its battery percentage to the Gateway/Control Panel respectively at 20%, 30%, 40%, 50%, 60%, 70%, 80%, 90%, and 100%.
  * When AC power is removed or power failure takes place, the SDCO will use its built-in rechargeable battery and report its battery percentage. After AC power is reapplied, the SDCO will report its battery percentage detected. When the battery voltage detected is 4.3V or above, the SDCO will report its battery percentage at 60% and begin to charge the battery. When the battery voltage detected is under 4.3V, the SDCO will report its battery percentage respectively and begin to charge the battery.
* **Temperature/Humidity Report: \[COMMAND\_CLASS\_SENSOR\_MULTILEVEL] \[SENSOR\_MULTILEVEL\_REPORT]**
  * The user can press the button once to send temperature and humidity information to the Control Panel.

|  Temperature: | 01 42 08 CC |
| -------------- | ----------- |

* If temperature signal 01 42 **08 CC** is transmitted:

**08CC** can be viewed as 0x**08CC** in Hexadecimal number. You can convert hexadecimal to decimal and divide by 100 to check the temperature data (in Celsius).

0x08CC=2252=25.52℃.

*
  * If humidity signal 05 02 **00 3C** is transmitted:

**003C** can be viewed as 0x**003C** in Hexadecimal number. You can convert hexadecimal to decimal to check the humidity level (in percentage).

003C=0x003C=60%

* **Smoke Alarm Test/Smoke Alarm Test Deactivated:: \[COMMAND\_CLASS\_NOTIFICATION] \[NOTIFICATION\_REPORT]**
  * The user can press the Button once to send smoke alarm test and smoke alarm test deactivated signals to the Control Panel.
  * Smoke Alarm Test: 00 00 00 FF 01 03 00
  * Smoke Alarm Test Deactivated: 00 00 00 FF 01 00 01 03
  * 01=alarm type; 03=smoke alarm test
* **Smoke Emergency/Smoke Emergency Cleared: \[COMMAND\_CLASS\_NOTIFICATION] \[NOTIFICATION\_REPORT]**

 Smoke Alarm: 00 00 00 FF 01 01 0B 77 06 00 42 61 73 65 6D 65 6E 74

Note: 0B 77 06 00 42 61 73 65 6D 65 6E 74 is when the location is “Basement”.

* A smoke alarm will be activated after the smoke concentration exceeds the detection threshold, or either manually activated by sending commands, the SDCO can be silenced and enter Alarm Silence mode. Please refer to “_**Alarm Silence**” section for details._ The SDCO will send an alarm silence report in the following three conditions:

|  When the smoke concentration has dropped below alarm threshold, the SDCO will send: | 00 00 00 FF 01 06 01 01 |   |   |   |   |
| ------------------------------------------------------------------------------------- | ----------------------- | - | - | - | - |
|  When the user presses the button to stop the alarm, the SDCO will send:             |                         |   |   |   |   |
| 00 00 00 FF 01 06 01 02                                                               |                         |   |   |   |   |
|  When the user sends a siren off command to stop the alarm, the SDCO will send:      |                         |   |   |   |   |
| 00 00 00 FF 01 06 01 03                                                               |                         |   |   |   |   |
| Please refer to “**Siren On/Off Control Command**” for details.                       |                         |   |   |   |   |

*
  * Note: If multiple alarms are activated, the alarm silence events will be sent respectively.
  * After the SDCO is silenced, if no smoke is detected for 20 continuous detection times, the SDCO will transmit a restore signal: 00 00 00 FF 01 00 01 01.
* **Heat Emergency/Heat Emergency Cleared: \[COMMAND\_CLASS\_NOTIFICATION] \[NOTIFICATION\_REPORT]**

|  Heat Alarm: | 00 00 00 FF | 04 01 | 0B 77 06 00 42 61 73 65 6D 65 6E 74                   |
| ------------- | ----------- | ----- | ----------------------------------------------------- |
| Note:         | 0B 77 06 00 | 42 61 | 73 65 6D 65 6E 74 is when the location is “Basement”. |

* A heat alarm will be activated after the SDCO meets the Rate of Rise or High Heat condition, or either manually activated by sending commands, the SDCO can be silenced and enter Alarm Silence mode. Please refer to “_**Alarm Silence**” section for details._ The SDCO will send an alarm silence report in the following three conditions:

|  When the temperature has dropped below alarm threshold, the SDCO will send:    | 00 00 00 FF 04 09 01 01 |   |   |   |   |
| -------------------------------------------------------------------------------- | ----------------------- | - | - | - | - |
|  When the user presses the button to stop the alarm, the SDCO will send:        |                         |   |   |   |   |
| 00 00 00 FF 04 09 01 02                                                          |                         |   |   |   |   |
|  When the user sends a siren off command to stop the alarm, the SDCO will send: |                         |   |   |   |   |
| 00 00 00 FF 01 06 01 03                                                          |                         |   |   |   |   |
| Please refer to “**Siren On/Off Control Command**” for details.                  |                         |   |   |   |   |

*
  * Note: If multiple alarms are activated, the alarm silence events will be sent respectively.
  * After the SDCO is silenced, if no high heat is detected for 16 continuous detection times, the SDCO will transmit a restore signal: 00 00 00 FF 04 00 01 01.
* **CO Emergency/CO Emergency Cleared: \[COMMAND\_CLASS\_NOTIFICATION] \[NOTIFICATION\_REPORT]**

 CO Alarm: 00 00 00 FF 02 01 0B 77 06 00 42 61 73 65 6D 65 6E 74

Note: 0B 77 06 00 42 61 73 65 6D 65 6E 74 is when the location is “Basement”.

* A CO alarm will be activated after the CO concentration exceeds the detection threshold, or either manually activated by sending commands, the SDCO can be silenced and enter Alarm Silence mode. Please refer to “_**Alarm Silence**” section for details._ The SDCO will send an alarm silence report in the following three conditions:

|                                                                        | When the CO concentration has dropped below 30ppm, the SDCO will send: | 00 00 00 FF 02 06 01 01 |   |   |   |   |
| ----------------------------------------------------------------------- | ---------------------------------------------------------------------- | ----------------------- | - | - | - | - |
|                                                                        |                                                                        |                         |   |   |   |   |
| When the user presses the button to stop the alarm, the SDCO will send: | 00 00 00 FF 02 06 01 02                                                |                         |   |   |   |   |
|                                                                         |                                                                        |                         |   |   |   |   |

**Please note an alarm activated by exceeding the second alarm threshold can be silenced by pressing the button.**

|  When the user sends a siren off command to stop the alarm, the SDCO will send: | 00 00 00 FF 01 06 01 03 |   |   |   |
| -------------------------------------------------------------------------------- | ----------------------- | - | - | - |
|                                                                                  |                         |   |   |   |

*
  * Note: If multiple alarms are activated, the alarm silence events will be sent respectively.
  * After the SDCO is silenced, if CO drops below 30ppm for 10 continuous detection times, the SDCO will transmit a restore signal: 00 00 00 FF 02 00 01 01.
* **Location:**
  * When a smoke alarm, heat alarm, or CO alarm is triggered, it will send notification with the location name. For serial connected models, pre-programmed location will also be transmitted.
  * If a smoke alarm is triggered in the basement, 00 00 00 FF 01 01 **0B 77 06 00 42 61 73 65 6D 65 6E 74** will be sent, as shown in Table 1 below

_**Table 1**_

| 1 | V1 | Alarm Type  | 0x00 | Not implemented |
| - | -- | ----------- | ---- | --------------- |
|   |    |             |      |                 |
| 2 | V1 | Alarm Level | 0x00 | Not implemented |
|   |    |             |      |                 |

9

| 3  | Reserved                | 0x00 | Reserved field                     |
| -- | ----------------------- | ---- | ---------------------------------- |
|    |                         |      |                                    |
| 4  | Notification Status     | 0xFF | Unsolicited report is activated    |
|    |                         |      |                                    |
| 5  | Notification Type       | 0x01 | Smoke Alarm                        |
|    |                         |      |                                    |
| 6  | Event                   | 0x01 | Smoke Detected                     |
|    |                         |      |                                    |
| 7  | Event Parameters Length | 0x0B | Event Parm Length = 11             |
|    |                         |      |                                    |
| 8  | Event Parm 1            | 0x77 | Node Naming & Location CC id       |
|    |                         |      |                                    |
| 9  | Event Parm 2            | 0x06 | Node Location Report command id    |
|    |                         |      |                                    |
| 10 | Event Parm 3            | 0x00 | Cmd Parm: Char = ASCII             |
|    |                         |      |                                    |
| 11 | Event Parm 4            | 0x42 | Cmd Parm: Node Location Char 1 = B |
|    |                         |      |                                    |
| 12 | Event Parm 5            | 0x61 | Cmd Parm: Node Location Char 2 = a |
|    |                         |      |                                    |
| 13 | Event Parm 6            | 0x73 | Cmd Parm: Node Location Char 3 = s |
|    |                         |      |                                    |
| 14 | Event Parm 7            | 0x65 | Cmd Parm: Node Location Char 4 = e |
|    |                         |      |                                    |
| 15 | Event Parm 8            | 0x6D | Cmd Parm: Node Location Char 5 = m |
|    |                         |      |                                    |
| 16 | Event Parm 9            | 0x65 | Cmd Parm: Node Location Char 6 = e |
|    |                         |      |                                    |
| 17 | Event Parm 10           | 0x6E | Cmd Parm: Node Location Char 7 = n |
|    |                         |      |                                    |
| 18 | Event Parm 11           | 0x74 | Cmd Parm: Node Location Char 8 = t |
|    |                         |      |                                    |

* **Tamper Open/Close report: \[COMMAND\_CLASS\_NOTIFICATION] \[NOTIFICATION\_REPORT]**
  * The SDCO is protected by a tamper switch which is compressed when the SDCO is hooked onto the mounting bracket. When the SDCO is removed from the mounting bracket, the tamper switch will be activated and the SDCO will send a tamper open signal to the system control panel to remind the user of this condition.
  * Tamper Open :00 00 00 FF 07 03 00 00
  * After the SDCO is hooked onto the mounting bracket, it will send a tamper close signal to the control panel.

|  Tamper Close: | 00 00 00 FF 07 00 01 03 |
| --------------- | ----------------------- |

* **PIR Sensor**
  *
    * The SDCO will transmit signal to the Control Panel if any movement is picked up within the IR detection coverage.
  * PIR Active: 00 00 00 FF 07 07 0B 77 06 00 42 61 73 65 6D 65 6E 74
  * Note: 00 00 00 FF 07 07 0B 77 06 00 42 61 73 65 6D 65 6E 74 is when the location is “Basement”.
  * PIR Restore: 00 00 00 FF 07 00 01 07
* **Scene/Siren Control: \[COMMAND\_CLASS\_SCENE\_ACTIVATION] \[SCENE\_ACTIVATION\_SET] (for serial connected models):**
  * Scene ID: Alarm type (Table 2)
  * Dimming Duration: 0x00\~0x14

_**Table 2**_

| Bit5\~7 | Bit 4   | Bit 3       | Bit 2    | Bit 1    | Bit 0    |   |
| ------- | ------- | ----------- | -------- | -------- | -------- | - |
|         |         |             |          |          |          |   |
|         |         |             |          |          |          |   |
|         |         |             |          |          | SD Alarm |   |
| 0       | Burglar | Water Alarm | CO Alarm | HD Alarm |          |   |
|         |         |             |          |          |          |   |

* Location name /Bit4\~0/Num, as shown in Table 3 below

_**Table 3**_

*
  * English Prompt

| Num (hex) | Location Name  | Num (hex) | Location Name        |
| --------- | -------------- | --------- | -------------------- |
|           |                |           |                      |
| 0         | Basement       | B         | Nursery              |
| 1         | Hall           | C         | Toilet               |
| 2         | Office         | D         | Technical room       |
| 3         | Master Bedroom | E         | Wardrobe             |
| 4         | Bedroom        | F         | Attic living room    |
| 5         | Guest Bedroom  | 10        | Basement Living Room |
| 6         | Kitchen        | 11        | Staircase            |
| 7         | Dining Room    | 12        | Garage               |
| 8         | Living Room    | 13        | Rental Apartment     |
| 9         | Laundry        | 14        | No Location          |
| A         | Attic          |           |                      |

* Norwegian Prompt

Num (hex)

Location Name

Num (hex)

10

Location Name

| 0 | Living Room    | B  | Storage Room   |
| - | -------------- | -- | -------------- |
| 1 | Kitchen        | C  | Toilet         |
| 2 | Hallway        | D  | Technical Room |
| 3 | Master Bedroom | E  | Wardrobe       |
| 4 | Children Room  | F  | Upstairs       |
| 5 | Bedroom        | 10 | Downstairs     |
| 6 | Dining         | 11 | Staircase      |
| 7 | Laundry        | 12 | Garage         |
| 8 | Attic          | 13 | Rental Unit    |
| 9 | Office         | 14 | The Building   |
| A | Basement       |    |                |

*
  *
    * To activate the door chime, set Scene ID: 0x00 and Dimming Duration: 0xF1.
    * To stop the siren and voice prompts generated by this command, set Scene ID: 0x00 and Dimming Duration: 0x00. **Please note this command CANNOT be used to stop the siren and voice prompts of a real alarm.**
    * To stop the siren and voice prompts of a real alarm, set Scene ID: 0xFF and Dimming Duration: 0x00.
* **Siren On/Off Control: \[COMMAND\_CLASS\_BASIC] \[BASIC\_SET]**
  *
    * The siren of SDCO can be controlled by using Basic Set On/Off commands (for smoke alarm only, without location indication).
    * To turn on the siren by using this command, set Basic Set: 0xFF. The sounding pattern of the siren is the same as that of a smoke alarm.
    * To turn off the siren by using this command, set Basic Set: 0x00. **Please note this command CANNOT be used to stop the siren of a real alarm.** The SDCO will enter Alarm Silence mode and will send alarm restore signal after the period.
  * **Indicator** Control **: \[COMMAND\_CLASS\_INDICATOR] \[INDICATOR\_SET]**
    * The LED indicator of SDCO can be controlled by using Indicator Set commands.
    * The following commands can be used to set the indicator command:

|   | 7 |          |   | 6                                                       | 5                        | 4              | 3 |   | 2 |   | 1 | 0 |
| - | - | -------- | - | ------------------------------------------------------- | ------------------------ | -------------- | - | - | - | - | - | - |
|   |   |          |   |                                                         |                          |                |   |   |   |   |   |   |
|   |   |          |   | Command Class = COMMAND\_CLASS\_INDICATOR               |                          |                |   |   |   |   |   |   |
|   |   |          |   |                                                         |                          |                |   |   |   |   |   |   |
|   |   |          |   |                                                         | Command = INDICATOR\_SET |                |   |   |   |   |   |   |
|   |   |          |   |                                                         |                          |                |   |   |   |   |   |   |
|   |   |          |   | Indicator 0 Value (Indicator ID 0=00, Property ID 0=01) |                          |                |   |   |   |   |   |   |
|   |   |          |   |                                                         |                          |                |   |   |   |   |   |   |
|   |   | Reserved |   |                                                         | Indicator Object Count   |                |   |   |   |   |   |   |
|   |   |          |   |                                                         |                          |                |   |   |   |   |   |   |
|   |   |          |   |                                                         |                          | Indicator ID 1 |   |   |   |   |   |   |

Property ID 1

Value 1

* Indicator set on (0xFF) --- indicator function on
* Indicator set off (0x00) --- indicator function off
* Indicator Object Count (0x01) --- to control LED indicator ID 1
* Indicator ID (0x43) --- button indication

|   | Indicator ID |   |   | Description         |   |                                    | Appearance and use |   |   |
| - | ------------ | - | - | ------------------- | - | ---------------------------------- | ------------------ | - | - |
|   |              |   |   |                     |   |                                    |                    |   |   |
|   |              |   |   |                     |   |                                    |                    |   |   |
|   | 0x43         |   |   | BUTTON1\_INDICATION |   | Use to draw attention to button 1. |                    |   |   |

* Indicator ID (0x44) --- MCU reboot

|                                                 |   | Indicator ID |   |   | Description         |                     |                                   | Appearance and use |                                     |              |   |   |   |
| ----------------------------------------------- | - | ------------ | - | - | ------------------- | ------------------- | --------------------------------- | ------------------ | ----------------------------------- | ------------ | - | - | - |
|                                                 |   |              |   |   |                     |                     |                                   |                    |                                     |              |   |   |   |
|                                                 |   |              |   |   |                     |                     |                                   |                    |                                     |              |   |   |   |
|                                                 |   | 0x44         |   |   | BUTTON2\_INDICATION |                     | Use to draw attention to button 2 |                    |                                     |              |   |   |   |
|  Property ID (0x00-0xFE) --- LED on\_off times |   |              |   |   |                     |                     |                                   |                    |                                     |              |   |   |   |
|                                                 |   | Value        |   |   |                     | General Description |                                   |                    |                                     | Specific use |   |   |   |
|                                                 |   | 0x04         |   |   |                     | On\_Off\_Cycles     | Number of On\_Off\_Period to run  |                    |                                     |              |   |   |   |
|                                                 |   |              |   |   |                     |                     |                                   |                    | 0x00 – 0xFE = 0-254 times           |              |   |   |   |
|                                                 |   |              |   |   |                     |                     |                                   |                    | 0xFF = Run until stopped by On\_Off |              |   |   |   |
|                                                 |   |              |   |   |                     |                     |                                   |                    |                                     |              |   |   |   |

 If you would like the SDCO to flash 5 times to show its location, send: 0xFF 01 43 04 05

 If you would like the SDCO to stop flashing once you are aware of its location, send: 0x00 01 43 04 05  For more details, please refer to “_**SDS-13781-1 Z-Wave Application Command Class Specification**_”.

 **Configurations: \[COMMAND\_CLASS\_CONFIGURATION] \[CONFIGURATION\_SET]**

 Parameter Number: 0x01\~0x0A

 Size: 0x01

 Reserved: 0x00

 Default: 0x00

 Configuration Value: 0xXX

| Parameter Number  | Configuration Value |
| ----------------- | ------------------- |
|                   |                     |
| 0x01, Sensitivity | 0x01\~0x08 (0\~70), |
|                   | default: 0x04       |

0x02, Verification Period

0x00\~0x96 (0\~150 sec),

11

|                              | default 0x00                |
| ---------------------------- | --------------------------- |
|                              |                             |
| 0x03, SD Hardware version    | 0/1 (0:old, 1:new) always 1 |
|                              |                             |
| 0x04, Temperature Threshold  | 4\~50 (2\~25 degrees),      |
|                              | default: 4                  |
|                              |                             |
| 0x05, Auto Report Time       | 0\~240 minutes              |
|                              | default: 30                 |
|                              |                             |
| 0x06, Location               | 0\~20                       |
| (please refer to _Table 3_)  |                             |
|                              |                             |
| 0x07, Adjust Temperature     | +127\~-128                  |
|                              | (0.1 degree for each value) |
|                              |                             |
| 0x08, Adjust Humidity        | +127\~-128                  |
|                              | (1% for each value)         |
|                              |                             |
| 0x09, Hardware Fault         | 0x00\~0xFF                  |
| (please refer to _Table 4_   |                             |
| hardware fault listed below) |                             |
|                              |                             |
| 0x0A, Temporary Snooze       | 0\~7                        |
| (please refer to _Table 5_)  |                             |
|                              |                             |
| 0x0B, Language               | 01\~05                      |
|                              | 01: English                 |
|                              | 02: Norwegian (Default)     |
|                              | 03: Swedish                 |
|                              | 04: Finnish                 |
|                              | 05: Danish                  |
|                              |                             |

 _**Table 4**_ 0x09 (Hardware Fault)

| Bit7                                                                               | Bit6 | Bit5      |       |            | Bit4   | Bit3                                            | Bit2       | Bit1     | Bit0     |   |
| ---------------------------------------------------------------------------------- | ---- | --------- | ----- | ---------- | ------ | ----------------------------------------------- | ---------- | -------- | -------- | - |
|                                                                                    |      |           |       |            |        |                                                 |            |          |          |   |
| X                                                                                  | X    | AC        |       | Battery SW | Tamper | CO                                              | HD         | SD       |          |   |
|                                                                                    |      | 0:Restore |       |            | 0:On   | 1:Open                                          | 1:Broken   | 1:Broken | 1:Broken |   |
|                                                                                    |      | 1:Fail    |       |            | 1:Off  | 0:Close                                         | 0:Normal   | 0:Normal | 0:Normal |   |
|                                                                                    |      |           |       |            |        |                                                 |            |          |          |   |
|  SD Broken: If Bit0=1, it will send a Notification Command “00 00 00 FF 01 FE 00” |      |           |       |            |        |                                                 |            |          |          |   |
|  HD Broken: If Bit1=1, it will send a Notification Command “00 00 00 FF 04 FE 00” |      |           |       |            |        |                                                 |            |          |          |   |
|  CO Broken: If Bit2=1, it will send a Notification Command “00 00 00 FF 02 FE 00” |      |           |       |            |        |                                                 |            |          |          |   |
|  _**Table 5**_ 0x10 (Temporary Snooze)                                            |      |           |       |            |        |                                                 |            |          |          |   |
|                                                                                    |      |           | Value |            |        | Duration                                        |            |          |          |   |
|                                                                                    |      |           |       |            |        |                                                 |            |          |          |   |
|                                                                                    |      |           | 0     |            |        | Disable (the timer will be stopped immediately) |            |          |          |   |
|                                                                                    |      |           |       |            |        |                                                 |            |          |          |   |
|                                                                                    |      |           | 1     |            |        |                                                 | 5 minutes  |          |          |   |
|                                                                                    |      |           |       |            |        |                                                 |            |          |          |   |
|                                                                                    |      |           | 2     |            |        |                                                 | 30 minutes |          |          |   |
|                                                                                    |      |           |       |            |        |                                                 |            |          |          |   |
|                                                                                    |      |           | 3     |            |        |                                                 | 60 minutes |          |          |   |
|                                                                                    |      |           |       |            |        |                                                 |            |          |          |   |
|                                                                                    |      |           | 4     |            |        |                                                 | 8 hours    |          |          |   |
|                                                                                    |      |           |       |            |        |                                                 |            |          |          |   |
|                                                                                    |      |           | 5     |            |        |                                                 | 12 hours   |          |          |   |
|                                                                                    |      |           |       |            |        |                                                 |            |          |          |   |
|                                                                                    |      |           | 6     |            |        |                                                 | 24 hours   |          |          |   |
|                                                                                    |      |           |       |            |        |                                                 |            |          |          |   |
|                                                                                    |      |           | 7     |            |        |                                                 | 36 hours   |          |          |   |
|                                                                                    |      |           |       |            |        |                                                 |            |          |          |   |

* **Factory Reset**

If the device is learned and the Test Button is pressed and held for 20 seconds along with 3 beeps for the Factory Reset, it will send

\[COMMAND\_CLASS\_DEVICE\_RESET\_LOCALLY] \[DEVICE\_RESET\_LOCALLY\_NOTIFICATION]

 The device will be automatically excluded for the new version of PC Controller.

12
