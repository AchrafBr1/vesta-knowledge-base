# VESTA-052

**POVS-1-ZW**

**PIR Occupancy/Vacancy Sensor**

**Introduction**

POVS-1-ZW is a Z-Wave Passive Infrared Motion Sensors. It is capable of sending wireless signals to the coordinator in the Z-Wave network upon movement detection. Z-Wave is a wireless communication protocol that uses a low-power RF radio. The Z-Wave Passive Infrared Motion Sensors allows access to the “S2 Unauthenticated” class and supports Z-Wave SmartStart inclusion as well as classic inclusion.

## **Parts Identification**



![](<.gitbook/assets/0 (49).jpeg>)

**1. IR Lens w/ LED Indicator**

The LED Indicator is located at the center of the IR lens.

The LED indicator lights up in the following conditions:

* Flashes once after pressing the Function Button:

The PIR enters Inclusion / Exclusion mode or detects a movement in Test mode.

2. **Battery Compartment**

The PIR is powered by one CR123A 3V Lithium battery.

3. **Function Button**

* Press the button once within 30 seconds of inserting the battery to enter Inclusion or Exclusion mode.
* Press the button once in normal operation to send a wake up notification command and enter Test Mode.
* Press and hold the button for 10 seconds then release to factory reset the PIR.

4. **Magnetic Base**

The PIR is deployed on the magnetic base when installing. The magnet within PIR and the base will ensure the PIR remains attached to the base regardless of PIR location and angle.

**Features**

## _**Occupancy/Vacancy Detection**_

When the PIR detects a movement, it will transmit a trigger signal. The PIR then begins counting down the occupancy/vacancy timer. The timer length is adjustable from **30 seconds** to **60 minutes** and must be adjusted from the Z-Wave network coordinator/control panel.

During the timer, if the PIR detects a movement, the timer will be reset.

When the timer expires without any motion detection, the PIR will transmit a motion detection restore signal and return to normal operation.

Please refer to _**Command Class Configuration**_ for more details about the settings.

## _**Sensitivity Adjustment**_

The PIR sensitivity can be adjusted to meet different requirements as either security or occupancy/vacancy sensor. Up to 5 levels of sensitivity may be selected via Z-Wave network coordinator/control panel. Follow steps below to adjust the sensitivity:

1. Press the function button on the PIR once, the PIR will wake up.
2. Within 10 seconds, set the new PIR sensitivity from the Control Panel (Please refer to your Control Panel manual for details). The panel will send signal to the PIR to complete setting.
3. If sensitivity setting is not completed within this interval, restart from Step 1.

Please refer to _**Command Class Configuration**_ for more details about the settings.

## _**Battery and Low Battery Detection**_

The PIR uses one CR123A 3V Lithium battery as its power source. The main body must be removed from base to access battery compartment. The battery compartment has a strip which should be pressed under the battery when battery is inserted. When removing batter, simply lift the strip.

The PIR features Low Battery Detection function. When the battery voltage is low, The PIR will transmit Low Battery signal to the coordinator in Z-Wave network.

If battery is not changed after Low Battery and is exhausted, the PIR will stop all operation.

When changing battery, after removing the old battery, press the Function Button twice to fully discharge before inserting new battery

## _**Wake Up**_

This function uses the Z-Wave Wake Up Command Class. The Wake Up Command Class allows the battery-powered PIR to notify the Control Panel/Gateway that it is awake and ready to receive any queued commands. The wake up interval time period is programmed automatically according to Control Panel’s setting when the PIR is included. The recommended setting of the interval time is between 60 minutes.

## _**Test Mode**_

* Test mode is for you to check the PIR’s detection range.
* To enter Test mode, press the Function Button once enter the Test mode for 3 minutes.
* During Test Mode, you can trigger PIR sensor to check its detection coverage. If PIR is triggered, the LED will flash once to indicate.

## _**Adding Device (Inclusion)**_

The device supports both classic inclusion process and SmartStart inclusion process. This product can be included and operated in any Z-Wave network with other Z-Wave certified devices from other manufacturers and/or other applications. All non-battery operated nodes within the network will act as repeaters regardless of vendor to increase reliability of the network.

## **Classic Inclusion**

* Put the Z-Wave gateway or control panel into **Inclusion mode** (please refer to the Z-Wave gateway or control panel manual).
* Insert the battery and press the button once within 30 seconds. Refer to the operation manual of the Z-Wave gateway or control panel to complete the adding process.
* If the device has already been added (included) into another Z-Wave Gateway/Control Panel, or if the device is unable to be added into the current Z-Wave Gateway/Control Panel, try removing it first (see _**Removing Device**_).



![](<.gitbook/assets/7 (32).png>)

#### **SmartStart Inclusion**

SmartStart enabled products can be added into a Z-Wave network by scanning the Z-Wave QR Code presented on the product with a controller providing SmartStart inclusion. No further action is required and the SmartStart product will be added automatically within 10 minutes of being switched on in the network vicinity. Z-Wave SmartStart utilizes the DSK of the device to enhance and simplify the inclusion process. **DSK** is Device Specific Key used for authentication. The DSK information is stored in the QR code format that is printed on a label and adhered to the exterior of the device, as example shown on the right hand side.

* Scan the QR Code on the base of POVS-1-ZW to obtain **DSK** and transfer to the Z-Wave gateway.
* Power on POVS-1-ZW, a SmartStart inclusion request will be automatically sent to the gateway.
* The gateway will automatically include the device upon recognition of the device by matching the inclusion request with the DSK obtained

_\<NOTE>_

* The DSK of the device is used only during inclusion.
* The DSK can be read without the POVS powering ON, so it is possible to prepare the gateway to include the device prior to installing and powering up the POVS-1-ZW.
* If the POVS-1-ZW has already been **included** (learnt) into another Z-Wave Gateway/Control Panel, please exclude it first (see _**Exclusion**_) before attempting to **include** it into the current Z-Wave Gateway/Control Panel. The POVS-1-ZW will not send a SmartStart inclusion request if it’s already in a Z-Wave Gateway/Control Panel.

## Removing Device (Exclusion)

The device must be removed from existing Z-Wave network before being added into another.

### **Exclusion Mode**

* Put the Z-Wave gateway or control panel into **Exclusion mode** (please refer to the Z-Wave gateway or control panel manual).
* Insert the battery and press the button once within 30 seconds. The device will be removed from the Z-Wave network.

## **Factory Reset**

_(Only use factory reset when network Control Panel/Gateway is missing or inoperable)._

* Factory resetting the device will restore it to factory default settings (i.e. not included into any Z-Wave network). Please only use this procedure if the Z-Wave gateway or control panel is lost or otherwise inoperable.
* Press and hold the Function Button of the device for 10 seconds to factory reset.

_\<NOTE>_

* Before you remove or factory reset the POVS-1-ZW, please ensure that the device DSK information has been removed or does not exist in the gateway. If you remove or factory reset the device, but its DSK still exists in the gateway, the gateway will automatically include the device again.

## _**Range Test**_

To test whether the device is able to communicate with the Z-Wave gateway or control panel:

* Put the gateway / panel into range test mode (Walk Test).
* Press the Function Button on the device.
* The gateway / panel should display if the device is within the operation range (please refer to the operation manual of the gateway / panel).

## _**Z-Wave Sleep Mode**_

* The PIR will enter Z-Wave Sleep mode (to conserve power) after waking up for a short period of time (\~10 seconds). While in Z-Wave sleep mode, Z-Wave gateways or control panels are unable to send commands to the PIR.
* To program the PIR using the Z-Wave Gateway/Control Panel, please send command(s) to the PIR within the wake-up period.

## **Installation**

### _**Mounting Height and PIR Detection Coverage**_

* The PIR has detection coverage of a 120∘cone to the front. When mounted at 1.2m to 2.1m height and facing forward, the PIR has maximum range of 10 meters.
* The PIR direction can be changed by simply rotating the PIR on the base. After changing direction, make sure to test the detection function to confirm the new detection coverage.

### _**Assembly**_

* The PIR is comprised of a front cover and a back cover. The back cover must be separated for battery installation and Z-Wave network setup.
* To separate the back cover, hold the PIR in both hands and turn according to picture below to open the PIR.

### _**Installation**_

* The PIR main body has internal magnet at bottom and back, which attaches the main body to PIR magnet base when placed on the base. The magnet locations are identified by the circle mark on the casing.
* The PIR’s movement detection function is directional. It is more sensitive to movement from side, and less sensitive to vertical movement from top to bottom. Use the location of the bottom magnet as a reference to determine the horizontal and vertical direction of the PIR.
* The PIR base has 2 mounting holes used for installation on surface with fixing screws and plugs provided. The base also has magnet within. One side of the base has an opening to mark the front side of the base. The main body should be placed on the base with the lens facing the front opening to ensure PIR’s detection coverage is not obstructed by the base.

<figure><img src=".gitbook/assets/image (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1).png" alt=""><figcaption></figcaption></figure>

1. Use the 2 mounting holes on PIR base as template, drill holes in the surface.
2. Insert the wall plugs if fixing it into plaster or brick.
3. Screw the base into the wall plugs.
4. Place the PIR on the base. The magnet within PIR and base will ensure the PIR stays attached to base.
5. Rotate the PIR to adjust detection coverage according to expected intruder movement path. Make sure the intruder would move across the PIR detection coverage from side to side.

### _**Installation Guideline**_

### **It is recommended to install the PIR in the following locations.**

* In a position such that an intruder would normally move across the PIR’s field of view from side to side, avoid installing where intruder moves across the detection coverage from PIR top to bottom.
* Between 1.9 and 2m above ground for best performance when facing forward.
* Where its field of view will not be obstructed e.g. by curtains, ornaments etc.

### **Limitations**

* Do not install the PIR at location exposed direct sunlight, or close to heating/cooling appliance and vent
* Do not point the PIR at heat source such as heater, radiator and window.
* Do not point the PIR at window.
* Avoid large obstacles in the detection area, and avoid moving objects such as curtain.
* Avoid locations where pet may climb on and compromise pet immunity, such as stairway.

## **Z-Wave Information**

**Device Type:** Generic Type Sensor Notification

**Role Type:** Slave Sleeping Reporting (RSS)

**Manufacturer ID:** 0x018E

**Product Type ID:** 0x0001

**Product ID:** 0x0104

### **Supported Command Class:**

| **Command Class**         | **Version** | **Required Security Class**    |
| ------------------------- | ----------- | ------------------------------ |
| Association               | 2           | Highest Granted Security Class |
| Association Group Info    | 3           | Highest Granted Security Class |
| Device Reset Locally      | 1           | Highest Granted Security Class |
| Firmware Update Meta Data | 5           | Highest Granted Security Class |
| Manufacture Specific      | 2           | Highest Granted Security Class |
| Multi Channel             | 4           | Highest Granted Security Class |
| Multi Channel Association | 3           | Highest Granted Security Class |
| Powerlevel                | 1           | Highest Granted Security Class |
| Notification              | 8           | Highest Granted Security Class |
| Battery                   | 1           | Highest Granted Security Class |
| Wake Up                   | 2           | Highest Granted Security Class |
| Configuration             | 1           | Highest Granted Security Class |
| Version                   | 3           | Highest Granted Security Class |
| Transport Service         | 2           | None                           |
| Z-Wave Plus Info          | 2           | None                           |
| Security 2                | 1           | None                           |
| Supervision               | 1           | None                           |

### Association Groups :

<table data-header-hidden><thead><tr><th width="89"></th><th width="111"></th><th width="135"></th><th></th></tr></thead><tbody><tr><td><strong>ID</strong></td><td><strong>Name</strong></td><td><strong>Node count</strong></td><td><strong>Description</strong></td></tr><tr><td>1</td><td>Lifeline</td><td>5</td><td>Supports the following command classes:<br>Device Reset Locally: triggered upon reset<br>Notification Report: triggered by PIR<br>Battery Report: when battery level changes </td></tr><tr><td>2</td><td>Basic Set</td><td>5</td><td>When PIR triggers, group 2 sends 0xFF.<br>When PIR restores, group 2 sends 0x00.</td></tr></tbody></table>

### Command Class Configuration:

<table data-header-hidden><thead><tr><th width="110"></th><th width="110"></th><th width="66"></th><th width="106"></th><th width="110"></th><th width="91"></th><th></th></tr></thead><tbody><tr><td><strong>Number</strong></td><td><strong>Name</strong></td><td><strong>Size</strong></td><td><strong>Minimum</strong></td><td><strong>Maximum</strong></td><td><strong>Default</strong></td><td><strong>Description</strong></td></tr><tr><td>1</td><td>IR Sensitivity</td><td>1</td><td>1</td><td>5</td><td>4</td><td>Sensitivity level adjustment:<br>When the maximum is larger than 5, 5 will be the set value; when the minimum is smaller than 1, 1 will be the set value.<br>1: the lowest; 5: the highest</td></tr><tr><td>2</td><td>IR Restore Time</td><td>1</td><td>1</td><td>120</td><td>1</td><td>The timer length is adjustable from 30 seconds to 60 minutes:<br>1: 30 seconds; 120: 60 minutes<br>When the maximum is larger than 120, 120 will be the set value; when the minimum is smaller than 1, 1 will be the set value.</td></tr></tbody></table>

