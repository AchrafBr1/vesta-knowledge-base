# VESTA 158

![](<.gitbook/assets/0 (47).png>)**Temperature Sensor (TAS-9/TAS-9E)**

TAS-9E is temperature wireless sensor device. It transmits temperature condition to the Control Panel every 30-50 minutes and alarm signal when temperature exceeds or drops below normal operation range set by Dip Switch.

The Temperature Sensor includes the following models: **TAS-9:** Temperature Sensor with built-in temperature sensor. **TAS-9E:** Temperature Sensor with External Temperature Probe.

![](<.gitbook/assets/1 (50).jpeg>)

* _**Parts Identification**_

Remove the cover by loosening the bottom fixing screw, the inside of the Temperature Sensor will be revealed as shown.

*
  1. **Terminal Block for External Temperature Probe (TAS-9E only)**

Optional Terminal Block to connect an External Temperature Probe.

*
  1. **Tamper Switch**

When the Temperature Sensor is properly installed, the Tamper switch will be compressed.

A **Tamper close** signal is transmitted when the Tamper is compressed.

A **Tamper open** signal is transmitted when the Tamper is released.

*
  1. **Internal LED**

Flashes Quickly for 2 seconds –

Tamper Switch closed/opened, Learn/Test Button pressed. Flashes every 4 seconds – Battery exhaustion

The LED flashes once every 4 seconds to indicate low battery and all operations are stopped. Refer to **Battery** to change and restore the Temperature Sensor’s function.

*
  1. **DIP Switch Functional Block**
  2. **Learn / Test Button**

Press the button once to send out a learning code along with status code to inform the control panel the status of the Temperature Sensor.

*
  1. **Battery Compartment**
  2. **External Temperature Probe Connector (TAS-9E only)**
  3. **External Temperature Probe (TAS-9E only)**
  4. **Internal Temperature Probe**
* _**Battery**_

![](<.gitbook/assets/2 (47).jpeg>) ![](<.gitbook/assets/3 (42).jpeg>)

The Temperature Sensor uses one **CR123 - 3V Lithium battery**. Please always replace battery with the correct size and voltage.

When the Temperature Sensor is low battery, a low battery signal will be sent to the Control Panel along with regular signal transmissions for the Control Panel to display the status accordingly.

When the battery is depleted, the LED flashes every 4 seconds and the Temperature Sensor will stop all function.

* **Battery Change**

1. Remove cover by loosening the bottom fixing screw. Then remove the Old Battery.

II. Press the Tamper Switch or the Learn/Test Button a few times.

III. Fit a new battery into the battery compartment. Please orient the battery according to the correct polarity.

IV. Replace the Cover.

1

* ![](<.gitbook/assets/4 (42).jpeg>)_**Supervision**_
  * A supervision signal is sent out every 30-50 minutes along with current temperature reading and battery status.
  * The supervision time is reset whenever a signal is transmitted. (such as **Tamper open** signal, **Tamper close** signal, etc.).
* _**Getting Started**_
  * Remove the fixing screw and cover assembly
  * Insert the battery into the battery holder taking care to connect the polarity correctly.
  * Put Control Panel into learning mode. Please refer to your Control Panel user manual.
  * Press the Learn/Test Button once to send a learn code to Control Panel.
  * Refer to the user manual of the Control Panel to complete the learn-in process.
  * To check for range, Put the Control Panel into Walk Test mode, put the device at desired mounting location and press Learn/Test button to transmit signal for rage test.
  * When you are satisfied that the Temperature Sensor works in the chosen location, you can proceed with installation.
* _**Installation**_

![](<.gitbook/assets/5 (26).jpeg>) ![](<.gitbook/assets/6 (36).jpeg>)

There are two ways to mount the Temperature Sensor: Self-adhesive or Screw mounting.

* **Self adhesive mounting**

1. Clean the surface with a suitable degreaser.
2. Remove the protective covering from one side of the double-sided adhesive pad and firmly apply to the back of the device.

III. Next remove the other cover and firmly press the item onto the desired location.

![](<.gitbook/assets/7 (31).png>)

_\<NOTE>_

*
  * Do not use the adhesive pad method of installation on a surface with peeling or cracked paint, or on a rough surface.
* **Screw mounting**

The Base has two knockouts, where the plastic is thinner, for mounting purpose. To mount the Temperature Sensor

1. Remove the cover and break through the knockouts on the base

II. Using the holes as a template, drill holes in the surface III. Insert the wall plugs if fixing into plaster or brick

IV. Screw the base into the wall plugs, then screw the cover back onto its base.

![](<.gitbook/assets/8 (28).jpeg>)

* _**Operation & Alarm Activation**_
  * The Temperature Sensor can be selected to use either the Internal or External temperature probe according to Dip Switch setting
  * The DIP Switch settings also determine four temperature ranges for normal operation and alarm activation threshold.
  * An alarm activating signal is transmitted if the temperature rises above Alarm Activation Threshold **for 10 minutes**.
  * An alarm restoration signal is transmitted if the temperature drops below the Alarm Restoration Threshold **for 4 minutes**.
  * Please refer to the table below for more detail:

| DIP       | DIP        | Normal      | Alarm        | Alarm   | Detecting Probe |   |
| --------- | ---------- | ----------- | ------------ | ------- | --------------- | - |
| Operation | Activation | Restoration | (Internal or |         |                 |   |
| Switch 1  | Switch 2   |             |              |         |                 |   |
| Range     | Threshold  | Threshold   | External)    |         |                 |   |
|           |            |             |              |         |                 |   |
| Off       | Off        | 7°C - 35°C  | < 7°C        | > 9°C   | Internal        |   |
| > 35°C    | < 33°C     |             |              |         |                 |   |
|           |            |             |              |         |                 |   |
|           |            |             |              |         |                 |   |
| Off       | On         | < -12°C     | > -12°C      | < -14°C | External        |   |
| > 7°C     | < 7°C      | > 9°C       |              |         |                 |   |
|           |            |             |              |         |                 |   |
|           |            |             |              |         |                 |   |
| On        | Off        | 7°C - 24°C  | < 7°C        | > 9°C   | Internal        |   |
| > 24°C    | < 22°C     |             |              |         |                 |   |
|           |            |             |              |         |                 |   |
|           |            |             |              |         |                 |   |
| On        | On         | < 6°C       | > 6°C        | < 4°C   | External        |   |
| > 7°C     | < 7°C      | > 9°C       |              |         |                 |   |
|           |            |             |              |         |                 |   |
|           |            |             |              |         |                 |   |

* To switch between modes, simply adjust the DIP switches according to desired setting.

2
