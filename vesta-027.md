# VESTA 027

**Hardwire to Wireless Converter (HWC-1B)**

HWC-1B is a wired to wireless converter that converts existing wired sensors of security alarm systems to wireless technology. HWC-1B can be installed at a preferable location where it can send reports to the Control Panel easily without any more concern about traditional wired scenarios. To achieve this, the existing wired sensors are connected to the input zones of the HWC-1B, so there is no need to replace wired devices with individual transmitters.

The easy-to-use Converter consists of 9 input zones, each can be connected to existing security sensor by wiring, e.g. PIR sensor, door contact, smoke detector, water sensor, fire sensor, CO sensor, gas detector, heat detector, and glass break detector, etc. This saves on installation cost, and provides homes and businesses with increased convenience and efficient functionality for users.

* **Parts Identification**

1. **LED Indicator**
   * **Input power LED1 (Green/Red):**

![](<.gitbook/assets/0 (29).jpeg>)

LED green on: AC power is connected.

LED red on: AC power failure.

* **Status LED2 (Yellow):**

ON: Low battery or disconnection.

Flash: Battery charging failure.

* **Transmission LED3 (Green):**

The LED Green flashes when any signal is transmitted.

* **Input calibration LED4 (Green):**

ON: When pressing and holding the calibration button for 2 seconds.

ON: When Input calibration is successful.

* **Require calibration LED5 (Red):**

Flash: When Input needs calibrating.

ON: When pressing and holding the calibration button for

*
  1. seconds.

1. **Test/Learn Button (SW11).**
2. **Calibration Button (SW12)**
3. **Reset Button (SW1)**
4. **Terminal:** Z1\~Z9 Input Zones.

(See _**Application Diagram**_ for detail.)

1. **Tamper Switch Button (SW20).**
2. **Power Terminal** (See _**Application Diagram**_ for detail.)

![](<.gitbook/assets/1 (24).jpeg>)

**+12V/GND:** Connect to power supply.

**12VAUX/GND:** Provides 12V DC@100mA to power on connected devices.

1. **Rechargeable Battery Pack**
2. **Two-pin Connector**

The two-pin connector is used for connecting to the Rechargeable Battery Pack.

1. **Mounting Holes**

* **Power Supply**

1

**Power Adapter Application:**

* Power on the HWC-1B by connecting the two-wired 12V AC-DC Adaptor to the +12V/GND terminal.
* When power supply is interrupted and restore, HWC-1B will transmit AC failure and restore signal respectively.

**Rechargeable Battery:**

* A 1.2V\*8 750mAh AAA Ni-MH Rechargeable Battery Pack is installed inside HWC-1B to serve as a backup in case of a power failure. The battery pack is not connected by factory. Please connect the battery pack if you want to use it as backup power.
* HWC-1B will charge the rechargeable battery pack automatically when power is supplied and the rechargeable battery pack is connected. When power supply is interrupted, HWC-1B will switch to using the rechargeable battery and continue operation.
* When the rechargeable battery is low on power, HWC-1B will transmit low battery signal. When the battery has been charged, HWC-1B will transmit battery restore signal.

**Power Output:**

*
  * HWC-1B can supply 12V, 100mA power to connected devices via the power terminal.
* **Rechargeable Battery Pack**
  * HWC-1B will charge the battery automatically when power is connected. When power supply is interrupted, HWC-1B will switch to using the rechargeable battery and continue operation.
* **Application Diagram**

![](<.gitbook/assets/2 (22).jpeg>)

The Terminal (Z1\~Z9 input zones) allow existing wired sensors to be connected to the HWC-1B Converter:

* Each input zone is only available to one wired sensor.
* It is essential for all input zones that are used to have an EOL resistor (with a value from 1k to 10k ohms).
* Keep the existing installation zones which already have EOL resistor (with a value from 1k to 10k ohms).
* For a NC loop without an EOL resistor, please add one in series with the loop.
* For a NO loop without an EOL resistor, please add one in parallel (across) the loop. It should be located at the end of the loop far away from the Control Panel.

_\<NOTE>_

*
  * If you wish to change the wires on the input zone, please power OFF HWC-1B first, then change wire input location as prefered and power ON the HWC-1B again. Press the calibration button to finalize the changing process.
* **(SW12) Calibration Button**

After wiring existing sensors to the HWC-1B, initiate the calibration process which allows the HWC-1B to learn which zone will be active and what EOL resistors are used. Any unused / opened zone will not be recognized and reported to the Control Panel.

* Ensure all zones are well connected.
* Press and hold the Calibration button **(SW12)** for 2 seconds. Both LED4 (Green) and LED5 (Red) will turn ON.
* When calibration is completed, LED5 (Red) will turn OFF. LED4 (Green) will stay ON to indicate calibration is successful.
* When calibration fails, LED4 (Green) will turn OFF, LED5 (Red) will flash to indicate error.

_\<NOTE>_

* Zone 1 must be wired for HWC-1B to function normally and use calibration function.

2

* **(SW11) Learning / Walk Test**
  * Make sure the devices are connected and properly calibrated before proceeding to learning.
  * Refer to your Control Panel Manual to put panel into learning mode.
  * Press the Test/Learn button **SW11** to send learning code to the Control Panel.
  * Refer to your Control Panel operation manual to complete the learn-in process.
  * Test/Learn button is also used for Walk Test function. Put the panel into Walk Test mode and press the button to check signal range and strength.

![](<.gitbook/assets/3 (36).png>)

_\<NOTE>_

Zone number

*
  * When HWC-1B is learned into the alarm system, each active zone will be recognized as Door Contact device type. Users can edit the device name and select the alarm type for each connected sesnsor in the Device Edit page.
  * Each learned input zone will send an individual RF code to the Control Panel. The zone number is indicated by the the last digit of the device ID.
  * HWC-1B’s own status (Low Battery, Tamper..etc) is transmitted via Zone 1.
* **Supervision**
  * The Converter will automatically transmit Supervisory signals periodically to the Control Panel at random intervals of 30 to 50 minutes in Normal Operation Mode.
  * If the Control Panel has not received the signal from the Converter for a preset period time, the Control Panel will indicate that particular Converter is experiencing an out-of-signal problem.
* **(SW20) Tamper Switch**
  * It is designed to protect against unauthorized cover opening. When the tamper switch is triggered, HWC-1B will emit a tamper open signal to the Control Panel for reporting.
* **Installation Procedures**

The HWC-1B can be wall mounted with the mounting bracket provided, or with the pre-punched mounting holes. Please follow steps below to proceed.

1. **With Mounting Bracket:**
2. Take out the mounting bracket provided.
3. Use the 2 central mounting holes on the mounting bracket to mark positions on the wall.
4. Drill holes at mounting location and install wall plugs if required.
5. Install mounting screws at marked location as shown below.

![](<.gitbook/assets/4 (22).jpeg>)

3

1. Attach the HWC-1B onto the bracket as shown below.

![](<.gitbook/assets/5 (15).jpeg>)

1. Hold the HWC-1B and gently push it downwards as shown below.

![](<.gitbook/assets/6 (19).jpeg>)

**B: With Pre-punched Mounting Holes:**

*
  1. Press down on the pre-punch holes on the edges of HWC-1B and gently lift the front cover at the same time.
  2. Use the 4 mounting holes around the edge of the back cover to mark hole positions on the wall.
  3. Drill holes at mounting location and install wall plugs.
  4. Screw the back cover onto the marked location.
  5. Replace front cover back. The installation is now complete.
* **Factory Reset**

Factory Reset will clear HWC-1B of all calibrated zone information.

1. Disconnect both power supply and battery.
2. Press and hold the **Test/Learn Button (SW11)**, while holding the button, apply power to power on HWC-1B at the same time.
3. Keep holding the button for 3 seconds.
4. LED 1\~3 will turn ON. Release the button when the LEDs turn on. Factory Reset is complete.

4
