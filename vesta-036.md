# VESTA-036

**EIR-32**

## **Outdoor Pet-Immune PIR Motion Sensor**&#x20;

<figure><img src=".gitbook/assets/image (32) (1) (1).png" alt=""><figcaption></figcaption></figure>

The EIR-32, a battery operated outdoor PIR detector, allows economical and effortless outdoor installation while providing exceptional detection capabilities.

The built-in sensor with detection sensitivity eliminates the chance of false alarms caused by small animals or other outdoor disturbances.

The anti-masking feature allows for detection of any attempts to blind the detector by placing objects in its field of view.

In addition, the adjustable Detection Range gives the effective match for every installation environment, that provides a peace of mind living-style and yet protecting your premises and be-loved ones all year round.

## _**Identifying the Parts**_

&#x20;   **Front View                                              Inside View**                                                                  **Back View**

![](<.gitbook/assets/0 (45).png>)

1. **Digital Proximity Detector**

The detector is used detect any masking (blocking) attempt by an intruder.

2. **LED indicator**

The LED indicator is used to indicate the system status.

3. **IR Sensor**

The sensor is intended to detect moving objects.

4. **Test Button**

The Test button is used for testing the radio performance and for learning purpose.

5. **DIP Switch Block**

There are 8 DIP Switches for setting the function & detection sensitivity levels.

6. **Tamper Switch**

EIR-32 is protected by the tamper switch against any unauthorized removal from the mounting plate or mounting location.

7. **Battery Compartment**
8. **Mounting Plate**
9. **Breakaway Area**

The Breakaway Area has 6 knockouts (2 for surface mounting and 4 for corner mounting) where plastic is thinner for screw mounting. When the Detector is forcibly removed from mounting location, the Break Away area will detach and allow tamper switch to be activated.

10. **Protective Shield**

The protective shield protects the Digital Proximity Detector from rain.

## _**LED Indicator**_

In Normal operation mode, the LED Indicator remains off except:

* When the Motion Sensor is in low battery condition, each time it transmits a detected movement, the LED will flash for 6 times.
* When the Tamper Switch is triggered, the LED will flash for 6 times to indicate it is transmitting “**Tamper**” signal.
* When the Tamper condition persists, each time it transmits a detected movement, the LED will flash for 6 times.
* In Test mode, the LED will flash for 6 times whenever a movement is detected.

## _**Test Mode**_

The Motion Sensor can be put into Test mode for 10 minutes by pressing the Test button once. In Test mode, sleep timer is disabled and LED indicator is enabled to light up for two seconds whenever a movement is detected. The Motion Sensor will automatically exit Test Mode after 10 minutes, and return to normal mode.

To put the Motion Sensor into constant Test mode, please adjust DIP switch 1 (Please refer to _DIP Switch Position Table_).

## _**Battery**_

* The Motion Sensor uses two AAL91 lithium batteries as its power source.
* The Motion Sensor features low battery voltage detection. When low battery is detected, a low battery signal will be sent to the Control Panel along with regular signal transmissions for the Control Panel to display the status accordingly.
* **To Change Battery:**

**Step 1:** Navigate the Control Panel into Programming mode.

**Step 2:** Remove the Motion Sensor from mounting position and unscrew to open top cover.

**Step 3:** Remove the old batteries and press the tamper button a few seconds to fully discharge.

**Step 4:** Insert two new AAL91 lithium batteries.

**Step 5:** Screw back the top cover.

**Step 6:** Mount back the Motion Sensor to mounting location.

**Step 7:** Navigate the Control Panel to exit Programming mode and return to operation mode. The procedure is complete.

## _**Supervisory Signal**_

* After installation, the Motion Sensor will automatically transmit Supervisory signals periodically to the Control Panel at random intervals of 30 to 50 minutes.
* If the Control Panel has not received the signal from the Motion Sensor for the preset period of time, the Control Panel will indicate on its display that the particular Motion Sensor is experiencing an out-of-signal problem.

## _**Sleep Timer**_

The Motion Sensor features an automatic “sleep time” of approximately one minute for power conservation. After transmitting a detected movement, the Motion Sensor will not retransmit for one minute. Any further movement detected within this one-minute sleep period will extend the sleep time by another minute. This way, continuous movement in front of Motion Sensor will not unduly exhaust the battery.

## _**Double Knock Function**_

The Motion Sensor has a double knock function. If the double knock function is enabled, the Motion Sensor will report an alarm to the control panel only if two movements are detected within 10 seconds. If the double knock function is disabled, the Motion Sensor will report an alarm to the control panel when a movement is detected.

## _**Proximity Detection**_

* The Motion Sensor has a digital proximity detector that can detect any masking (blocking) attempt by an intruder.
* When a masking event is detected, and the masking condition lasts for 2 minutes, EIR-32 will send tamper open signal to the Control Panel to notify user of the condition.
* After masking/blocking is removed for 2 minutes, EIR-32 will send tamper restore signal to the Control Panel.

_\<NOTE>_

* Any IR trigger movement will clear currently detected masking event/condition. A masking event must be detected and last for 2 minutes for the tamper open report to be tramsmitted.

## _**DIP Switch Position Table**_

The function of each DIP Switch is listed in the table below. The DIP Switch is either ON or OFF. Top position indicates ON and the bottom position indicates OFF.

| <mark style="color:green;">DIP</mark> | <mark style="color:green;">Position</mark> | <mark style="color:green;">Function</mark>              |
| ------------------------------------- | ------------------------------------------ | ------------------------------------------------------- |
| Switch1                               | ON                                         | Test Mode                                               |
| Switch1                               | OFF                                        | Normal Mode (default)                                   |
| Switch2                               | ON                                         | Reserved                                                |
| Switch2                               | OFF                                        | Reserved                                                |
| Switch3                               | ON                                         | PIR facing a wall within 10 m                           |
| Switch3                               | OFF                                        | PIR facing an open space (no wall within 10 m)(default) |
| Switch4                               | ON                                         | PIR facing a lawn (default)                             |
| Switch4                               | OFF                                        | PIR facing a concrete/stone ground                      |

| <mark style="color:green;">DIP</mark> | <mark style="color:green;">Sensitivity Level</mark> |                                |
| ------------------------------------- | --------------------------------------------------- | ------------------------------ |
| Switch5                               | Switch6                                             |                                |
| ON                                    | ON                                                  | Low; 75 cm/60 kg pet (default) |
| ON                                    | OFF                                                 | Medium; 50 cm / 35 kg pet      |
| OFF                                   | ON                                                  | High; 30 cm / 20 kg pet        |
| OFF                                   | OFF                                                 | Reserved                       |
| <mark style="color:green;">DIP</mark> | <mark style="color:green;">Position</mark>          | Function                       |
| Switch7                               | ON                                                  | Double Knock Enable (default)  |
| Switch7                               | OFF                                                 | Double Knock Disable           |
| Switch8                               | ON                                                  | Pet Immune Enable (default)    |
| Switch8                               | OFF                                                 | Pet Immune Disable             |

<div align="left"><figure><img src=".gitbook/assets/image (2) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1).png" alt=""><figcaption></figcaption></figure></div>

{% hint style="warning" %}
Note:

After changing Dip Switch settings, please re-power on EIR-32 for it to operate with new Dip Switch Settings.
{% endhint %}

## _**Tamper Protection**_

* EIR-32 is protected by a tamper switch which is compressed when it is hooked onto the mounting bracket.
* Whenever the Motion Sensor is removed from the mounting plate, the tamper switch will be activated.
* When the Motion Sensor is forcibly removed from mounting location, the Break Away area on the mounting plate will detach, also allowing the tamper switch to be activated.
* The Motion Sensor will send a tamper open signal to remind the user of the condition whenever the tamper switch is activated.

## _**Getting Started – Learning the Motion Sensor into the Control Panel**_

* Loosen the fixing screws and remove the cover assembly.
* Based on your needs, set Sensitivity Switch as shown in _DIP Switch Position Table_.
* Insert two AAL91 lithium batteries into the battery holder taking care to connect the polarity correctly.
* The LED indicator will flash for 60 seconds. The Motion Sensor is warming up. During the warming period, the Motion Sensor is not activated. It is recommended that you stay away from the detection area during this time. After the warming period is over, the LED dims and the Motion Sensor is ready to operate.
* Put the Control Panel into learning mode, refer to Control Panel manual for details.
* Press the Test button once. The LED indicator will flash for three times.
* If the Control Panel receives the signal, it will display the information accordingly. Refer to the Control Panel manual to complete the learn-in process. (For certain Control Panel models, the Motion Sensor can be learnt in as a regular PIR with programmable attributes and thus the Control Panel will report when an alarm is triggered).
* After the Motion Sensor is learnt-in, put the Control Panel into Walk Test mode. Hold the Motion Sensor in the desired location, and press the Test button to confirm this location is within the signal range of the Control Panel.
* When you are satisfied that the Motion Sensor works in the chosen location, you can proceed to installation.

{% hint style="warning" %}
Note:

**Walk Test** should be conducted to confirm proper operation and coverage of the Motion Sensor.

When learning Motion Sensor or conducting Walk Test, please avoid obstructing the anti-masking detector by your hand, otherwise tamper open signal will transmitted to the Control Panel if the masking condition lasts for 2 minutes.
{% endhint %}

## _**Mounting & Installation Method**_

* **Mounting with mounting plate:**
  * The Motion Sensor is designed to be mounted on either a flat surface or in a corner situation with fixing screws and plugs provided.
  * The provided mounting plate has knockouts, where the plastic is thinner and can be broken for mounting purpose. Two knockouts are for surface fixing and four knockouts are for corner fixing as shown in the picture.
  * To Mount EIR-32 with Mounting Bracket:
    1. Use the mounting plate as a template to drill holes on the wall for plugs.
    2. Push in the plugs and fix the mounting plate on the wall with the screws.
    3. Mount EIR-32 with the hooks of the mounting plate latched on the back cover of the EIR-32, and then push downwards until you hear a click sound to lock the hook.
    4. Insert the protective shield (the protective film from both sides must first be removed).

![](<.gitbook/assets/4 (28).jpeg>) ![](<.gitbook/assets/5 (47).png>)

* **Mounting with mounting plate and rotating holder (Optional):**
  * A rotating holder is provided as a user friendly mounting option **(optional item, sold separately)**. It is comprised of a base to fix to surface, and a swivel ball to fix to mounting plate and EIR-32.

![](<.gitbook/assets/6 (32).jpeg>)

* With the rotating holder, the EIR-32 can be rotated horizontally to provide optimal coverage.

A special screwdriver with reversible double-sided bit, and three star socket screws are provided for fixing the rotating holder to the wall.

![](<.gitbook/assets/7 (29).png>)

Please use the provided screwdriver to tighten/loosen star socket screws.

![](<.gitbook/assets/8 (32).png>)

* To mount EIR-32 with mounting plate and rotating holder:
  1. Fix the rotating holder to the wall with provided screws.
  2. Fix the mounting plate on the swivel ball with the fixing screw secured through the foolproof design hole.
  3. Mount EIR-32 with the hooks of the mounting plate latched on the back cover of the EIR-32, and then push downwards until you hear a click sound to lock the hook.
  4. Insert the protective shield (the protective film from both sides must first be removed).

![](<.gitbook/assets/9 (34).png>)

1. Rotate the swivel ball horizontally to adjust EIR-32’s detecting angle. (When the angle adjusting screw is half loosen, the swivel ball can still be rotated.)
2. When EIR-32 is rotated to a positon with desired detection coverage, you can lock the position by firmly tightening the angle adjusting screw.

![](<.gitbook/assets/10 (12).jpeg>)

{% hint style="warning" %}
Note:

After EIR-32 is mounted, if the Control Panel displays the Tamper fault status for the device, please make sure the anti-masking detector is not obstructed by any object and wait for two minutes to see if the Tamper Open status is cleared. If Tamper Open status persisits after two minutes, please remove EIR-32 from the mounting location, and check if the Tamper Switch is properly compressed against the mounting plate.
{% endhint %}

## _**Installation Recommendations**_

**It is recommended to install the Motion Sensor in the following locations:**

![](<.gitbook/assets/11 (22).png>)

* At a height of 2 meters (measured from the bottom of the motion sensor) above the ground for best performance.
* In a corner for the widest view.
* Where an intruder would normally move across the Motion Sensor’s field of view.
* On a surface or in a corner where animals are inaccessible.
* The Motion Sensor has a detection range of 10M when mounted at the height of 2 meters above the ground.

**Limitations:**

* Do not expose the Motion Sensor completely to direct sunlight.
* Avoid large obstacles in the detection area.
* Do not face heat sources such as fires and boilers, or install above radiators.
* Never attempt to disassemble or modify the unit.
* Please install the Motion Sensor straight up. Do not tilt it.

![](<.gitbook/assets/12 (13).jpeg>)

* Do not install the motion sensor where objects moved by wind such as trees and laundry, which may block the motion sensor’s field of view.

![](<.gitbook/assets/13 (12).jpeg>)

* Clear all light-reflecting surfaces from the detection area, as well as water puddles.

![](<.gitbook/assets/14 (14).jpeg>)

* Avoid aiming at the path of outdoor unit’s intake or exhaust airflow.

![](<.gitbook/assets/15 (9).jpeg>)

{% hint style="warning" %}
IMPORTANT NOTE

Adjust the Dip Switches according to the installation location of the Motion Sensor for ideal performance. If Dip Switch settings does not match with installation environment, the Motion Sensor’s performance will be hindered and may cause either false alarm or inability to detect movement.

The Motion Sensor detects differences between the moving object and the background. If the object is stationary (i.e. not moving), the Motion Sensor is unable to detect it.

The Motion Sensor has a directional characteristic and is most effective at detecting intruder moving across field of detection. It is less sensitive for detecting motion directly towards the Motion Sensor.

For best performance, remember to adjust the mounting height of Motion Sensor with respect to the height of the tallest pet in the house. Taller dogs require the Motion Sensor to be mounted higher for pet friendliness.

The Motion Sensor has a blind spot of about 1 meter under it when mounted at a height of 2 meters. The blind spot area will enlarge if you mount the Motion Sensor higher than 2M, and reduce if lower than 2M.

Unless required, we suggest keeping the Motion Sensor mounting location at 2M for optimum performance. If you change the mounting height, please conduct detection test to make sure the Motion Sensor can detect intruder normally at the desired height.
{% endhint %}

