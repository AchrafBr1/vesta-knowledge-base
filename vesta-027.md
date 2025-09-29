# VESTA-027

**HWC-1B**

## **Hardwire to Wireless Converter**&#x20;

<figure><img src=".gitbook/assets/image (23) (1) (1) (1).png" alt=""><figcaption></figcaption></figure>

HWC-1B is a wired-to-wireless converter that converts existing wired sensors of security alarm systems to wireless technology. HWC-1B can be installed at a preferable location where it can send reports to the Control Panel easily without any more concern about traditional wired scenarios. To achieve this, the existing wired sensors are connected to the input zones of the HWC-1B, so there is no need to replace wired devices with individual transmitters.

The easy-to-use Converter consists of 9 input zones, and each can be connected to existing security sensors by wiring, e.g. PIR sensor, door contact, smoke detector, water sensor, fire sensor, CO sensor, gas detector, heat detector, and glass break detector, etc. This saves on installation costs and provides homes and businesses with increased convenience and efficient functionality for users.

## **Parts Identification**

<figure><img src=".gitbook/assets/1 (120).png" alt=""><figcaption></figcaption></figure>

1. **LED Indicator**
   * **Input power LED1 (Green/Red):**

&#x20;             LED green on: AC power is connected.

&#x20;             LED red on: AC power failure.

* **Status LED2 (Yellow):**

&#x20;      ON: Low battery or disconnection.

&#x20;      Flash: Battery charging failure.

* **Transmission LED3 (Green):**

&#x20;       The LED Green flashes when any signal is transmitted.

* **Input calibration LED4 (Green):**

&#x20;      ON: Press and hold the calibration button for 2 seconds.

&#x20;      ON: When Input calibration is successful.

* **Require calibration LED5 (Red):**

&#x20;      Flash: When Input needs calibrating.

&#x20;      ON: Press and hold the calibration button for 2 seconds.

<figure><img src=".gitbook/assets/2 (129).png" alt=""><figcaption></figcaption></figure>

2. **Test/Learn Button (SW11).**
3. **Calibration Button (SW12)**
4. **Reset Button (SW1)**
5. **Terminal:** Z1\~Z9 Input Zones.

&#x20;       (See _**Application Diagram**_ for details.)

6. **Tamper Switch Button (SW20).**
7. **Power Terminal** (See _**Application Diagram**_ for detail.)

<figure><img src=".gitbook/assets/4 (121).png" alt=""><figcaption></figcaption></figure>

8. **Rechargeable Battery Pack**
9. **Two-pin Connector**

&#x20;      The two-pin connector is used for connecting to the Rechargeable Battery Pack.

10. **Mounting Holes**

<figure><img src=".gitbook/assets/3 (117).png" alt=""><figcaption></figcaption></figure>

## **Power Supply**

**Power Adapter Application:**

* Power on the HWC-1B by connecting the two-wired 12V AC-DC Adaptor to the +12V/GND terminal.
* When the power supply is interrupted and restored, HWC-1B will transmit an AC failure and restore signal respectively.

### **Rechargeable Battery:**

* A 1.2V\*8 750mAh AAA Ni-MH Rechargeable Battery Pack is installed inside HWC-1B to serve as a backup in case of a power failure. The battery pack is not connected by the factory. Please connect the battery pack if you want to use it as backup power.
* HWC-1B will charge the rechargeable battery pack automatically when power is supplied and the rechargeable battery pack is connected. When the power supply is interrupted, HWC-1B will switch to using the rechargeable battery and continue operation.
* When the rechargeable battery is low on power, HWC-1B will transmit a low battery signal. When the battery has been charged, HWC-1B will transmit a battery restore signal.

### **Power Output:**

* HWC-1B can supply 12V, 100mA power to connected devices via the power terminal.

### **Rechargeable Battery Pack**

* HWC-1B will charge the battery automatically when power is connected. When the power supply is interrupted, HWC-1B will switch to using the rechargeable battery and continue operation.

### **Application Diagram**

![](<.gitbook/assets/2 (27).jpeg>)

The Terminal (Z1\~Z9 input zones) allow existing wired sensors to be connected to the HWC-1B Converter:

* resistor's input zone is only available to one wired sensor.
* It is essential for all input zones that are used to have an EOL resistor (with a value from 1k to 10k ohms).
* Keep the existing installation zones which already have EOL resistors (with a value from 1k to 10k ohms).
* For a NC loop without an EOL resistor, please add one in a series with the loop.
* For an NO loop without an EOL resistor, please add one in parallel (across) the loop. It should be located at the end of the loop, far away from the Control Panel.

{% hint style="warning" %}
Note:

If you wish to change the wires on the input zone, please power OFF HWC-1B first, then change the wire input location as preferred and power ON the HWC-1B again. Press the calibration button to finalize the changing process.
{% endhint %}

### **(SW12) Calibration Button**

After wiring existing sensors to the HWC-1B, initiate the calibration process which allows the HWC-1B to learn which zone will be active and what EOL resistors are used. Any unused / opened zone will not be recognized and reported to the Control Panel.

* Ensure all zones are well connected.
* Press and hold the Calibration button **(SW12)** for 2 seconds. Both LED4 (Green) and LED5 (Red) will turn ON.
* When calibration is completed, LED5 (Red) will turn OFF. LED4 (Green) will stay ON to indicate that calibration is successful.
* When calibration fails, LED4 (Green) will turn OFF, and LED5 (Red) will flash to indicate the error.

{% hint style="info" %}
Note:

Zone 1 must be wired for HWC-1B to function normally and use the calibration function.
{% endhint %}

### **(SW11) Learning / Walk Test**

* Make sure the devices are connected and properly calibrated before proceeding to learning.
* Refer to your Control Panel Manual to put the panel into learning mode.
* Press the Test/Learn button **SW11** to send the learning code to the Control Panel.
* Refer to your Control Panel operation manual to complete the learn-in process.
* Test/Learn button is also used for the Walk Test function. Put the panel into Walk Test mode and press the button to check the signal range and strength.

<figure><img src=".gitbook/assets/5 (121).png" alt=""><figcaption></figcaption></figure>

{% hint style="warning" %}
Note:

When HWC-1B is learned into the alarm system, each active zone will be recognized as a Door Contact device type. Users can edit the device name and select the alarm type for each connected sensor in the Device Edit page.

Each learned input zone will send an individual RF code to the Control Panel. The zone number is indicated by the the last digit of the device ID.

HWC-1B’s own status (Low Battery, Tamper..etc) is transmitted via Zone 1.
{% endhint %}

### **Supervision**

* The Converter will automatically transmit Supervisory signals periodically to the Control Panel at random intervals of 30 to 50 minutes in Normal Operation Mode.
* If the Control Panel has not received the signal from the Converter for a preset period time, the Control Panel will indicate that particular Converter is experiencing an out-of-signal problem.

### **(SW20) Tamper Switch**

* It is designed to protect against unauthorized cover opening. When the tamper switch is triggered, HWC-1B will emit a tamper open signal to the Control Panel for reporting.

### **Installation Procedures**&#x20;

**The** HWC-1B can be wall-mounted with the mounting bracket provided or with the pre-punched mounting holes. Please follow the steps below to proceed.

&#x20; **A.  With Mounting Bracket:**

1. Take out the mounting bracket provided.
2. Use the 2 central mounting holes on the mounting bracket to mark positions on the wall.
3. Drill holes at the mounting location and install wall plugs if required.
4. Install mounting screws at marked location as shown below.

![](<.gitbook/assets/4 (24).jpeg>)

5. Attach the HWC-1B onto the bracket as shown below.

![](<.gitbook/assets/5 (22).jpeg>)

6. Hold the HWC-1B and gently push it downwards, as shown below.

![](<.gitbook/assets/6 (28).jpeg>)

**B: With Pre-punched Mounting Holes:**

1. Press down on the pre-punch holes on the edges of HWC-1B and gently lift the front cover at the same time.
2. Use the 4 mounting holes around the edge of the back cover to mark hole positions on the wall.
3. Drill holes at the mounting location and install wall plugs.
4. Screw the back cover onto the marked location.
5. Replace the front cover. The installation is now complete.

### **Factory Reset**

Factory Reset will clear HWC-1B of all calibrated zone information.

1. Disconnect both the power supply and the battery.
2. Press and hold the **Test/Learn Button (SW11)**, While holding the button, apply power to power on HWC-1B at the same time.
3. Keep holding the button for 3 seconds.
4. LEDs 1\~3 will turn ON. Release the button when the LEDs turn on. Factory Reset is complete.
