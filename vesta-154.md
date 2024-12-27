# VESTA-154

## **EIRC-1-F1 Outdoor Curtain Motion Sensor**

EIRC-1-F1 is an Outdoor Curtain Motion Sensor that is equipped with both PIR and Microwave motion detection technology. The combination of dual detection methods greatly improves the Motion Sensor’s detection accuracy and reduces false alarm rate, by using the PIR as initial detection, and microwave as confirmation before actually transmitting the activation signal.

The motion sensor also features anti-masking function. It is able to detect any attempts to blind the sensor by placing objects in its field of view.

By using the L-shaped mounting plate, the user can choose either flat mount or side mount when installing the Motion Sensor on the wall. This design enables the motion sensor to detect suspicious movements at the front door, or detect intruders climbing over and breaking through fences or walls.

### _**Parts Identification**_

#### &#x20;               **Front**                                     **Internal**

![](<.gitbook/assets/0 (59).png>)

1.  **Digital Proximity Detector**

    The detector is used detect any masking (blocking) attempt by an intruder.
2. **Sensor Lens**
3.  **Transmitter LED (Red)**

    The LED lights up briefly when:

    1. The Learn/Test button is pressed.
    2. The Tamper Switch is triggered or restored.
    3. Movement is detected under Test Mode
    4. Movement is detected under Low Batter or Tamper open condition during normal operation

    When Motion Sensor battery is exhausted, the LED flashes every 4 seconds.
4.  &#x20;**Microwave Detection LED (Blue)**

    The LED lights up briefly when Microwave detection is triggered under Test Mode or Microwave Test mode.
5.  **IR Detection LED (Green)**

    The LED lights up briefly when IR detection is triggered under Test Mode.
6. **Tamper Switch**
7. **Sensitivity Increaser Jumper Switch (JP3)**
   * <img src=".gitbook/assets/image (8).png" alt="" data-size="line">If the jumper is **OFF** (if the jumper link is removed or “parked” on one pin), the Motion sensor’s detection sensitivity is in normal level. **(Factory default)**
   * <img src=".gitbook/assets/image (10).png" alt="" data-size="line">If the jumper is **ON**, the Motion sensor’s detection sensitivity is high.
8. **Microwave Test Enable / Disable Jumper Switch (JP2)**
   * <img src=".gitbook/assets/image (11).png" alt="" data-size="line">When the jumper is set as **ON**, the Motion sensor is under Microwave Test Mode (please see **Microwave Test Mode**)
   * <img src=".gitbook/assets/image (9).png" alt="" data-size="line">When the jumper is set as **OFF**, the Microwave Test Mode is disabled. **(Factory default)**
9.  **Microwave Range Switch**

    The Range scale is shown on the right with the arrow pointing at the current sensitivity level:

    1. Turning in the **Clockwise Direction** increases detection range.
    2. Turning in the **Counter-Clockwise Direction** decreases detection range. **Factory Default**: is set to medium.

    <figure><img src=".gitbook/assets/image (12).png" alt=""><figcaption></figcaption></figure>
10. **Learn/Test Button**
11. **Battery Compartment**
12. **L-Type Mouting Plate**
13. **Mouting Holes**
14. **Protective Shield**

    The protective shield protects the Digital Proximity Detector from rain.

### _**Features**_

#### _**Movement Detection**_

* The Motion Sensor has built-in PIR sensor and Microwave Transmitter. Motion Detection is performed by PIR Sensor during normal operation. When PIR Sensor detects movement, the Microwave Transmitter will be activated to verify the movement detection. If both PIR and Microwave confirms movement detection, the Motion Sensor will transmit detection signal.
* Detection signal will only be transmitted when both PIR and Microwave detect movement.
* Adjust Microwave Range Switch setting to tune the Microwave Transmitter and overall detection range.
* When Microwave Range Switch is set to Maximum, the Motion Sensor has an approximate range of 11 meters when mounted at 1.4\~1.6m height.
* When Microwave Range Switch is set to Medium, the Motion Sensor has an approximate range of 8.5 meters when mounted at 1.4\~1.6m height.
* When Microwave Range Switch is set to Minimum, the Motion Sensor has an approximate range of 4.5 meters when mounted at 1.4\~1.6m height.

#### _**Sleep Timer**_

The Motion Sensor features an automatic “sleep time” of approximately **1 minute** for power conservation. After transmitting a detected movement, the EIR will not retransmit for one minute. Any further movement detected within this one-minute sleep period will extend the sleep time by another minute. This way, continuous movement in front of EIR will not unduly exhaust the battery.

_**Test Mode**_

The Motion Sensor can be put into Test mode by pressing the Learn /Test button. Test Mode lasts 10 minutes and will be reset to 10 minutes by any Learn/Test button press. In Test Mode, Sleep Timer is disabled and the LEDs will light up when movement is detected. Use the Test mode to determine the detection coverage of Motion Sensor when installing the sensor.

#### _**Microwave Test Mode**_

The Microwave Test Mode is for microwave range test only. Use the **JP2 Jumper to enable** Microwave Test Mode.&#x20;

When the Motion Sensor is under Microwave Test Mode, PIR detection is disabled, the Microwave Transmitter will be activated to repeatedly send microwave signal for movement detection. When the Motion Sensor detects movement under Microwave Test Mode, the Microwave Blue LED will light up briefly to indicate.

Use the Microwave Test Mode to determine the microwave range and adjust range with Microwave Range Switch if required.&#x20;

{% hint style="info" %}
Make sure to disable Microwave Test Mode after testing is complete by setting **JP2 Jumper to OFF** and return the Motion Sensor to normal opeation.
{% endhint %}

#### _**Battery**_

* The Motion Sensor uses two AA L91 Lithium batteries as its power source.
* The Motion Sensor features low battery detection, when low battery voltage is detected, a low battery signal will be sent to the Control Panel along with regular signal transmissions.
* If battery is not changed after low battery detection and the battery is fully exhausted, the Motion Sensor will stop all operation. The Red LED will flash every 4 seconds to indicate.
* When changing batteries, after removing the old batteries, press the Tamper Switch or Learn/Test a couple times to fully discharge before inserting new batteries.

#### _**Supervision**_

* After installation, the Motion Sensor will transmit a supervisory signal to the Control Panel every 30 to 50 minutes
* If the Control Panel fails to receive the supervisory signals from the Motion Sensor for a preset period of time, the Control Panel will indicate on its display that the particular sensor is out of order.

#### _**Tamper Switch**_

The tamper switch on the Motion Sensor is in normal position (Tamper closed) when the spring is compressed against the inside of device back cover. Tamper violation happens when the front cover is removed from the base and the tamper switch is released.

#### _**Proximity Detection**_

* The Motion Sensor has a digital proximity detector that can detect any masking (blocking) attempt by an intruder.
* When a masking event is detected, and the masking condition lasts for 2 minutes, EIRC-1-F1 will send tamper open signal to the Control Panel to notify user of the condition.
* After masking/blocking is removed for 2 minutes, EIRC-1-F1 will send tamper restore signal to the Control Panel.

{% hint style="info" %}
Any IR trigger movement will clear currently detected masking event/condition. A new masking event must be detected and last for 2 minutes for the tamper open report to be tramsmitted.
{% endhint %}

### _**Learning and Installation**_

#### _**Getting Started**_

1. Remove the front cover from the base by loosening the bottom fixing screw.
2. Orient and insert the batteries according to polarity.
3. The Red Transmitter LED will begin to flash for 30 seconds to indicate the Motion Sensor is warming up. During the warming up period, the Motion Sensor will not be activated. It is recommended that you stay away from the detection area during this time. After the warming-up period, the Red LED will turn off and the Motion Sensor will enter normal operation.
4. Put the Control Panel into learning mode; refer to Control Panel manual for details.
5. Press the Learn/Test Button to transmit signal to panel.
6. If the panel receives signal from Motion Sensor, it will display sensor info accordingly. Refer to your Control Panel to complete the learn-in process.
7. After the Motion sensor is learnt-in, put the Control Panel into “Walk Test” mode, hold the sensor in the desired location, and press the Test Switch to confirm this location is within signal range of the Control Panel.
8. When you are satisfied with the chosen location, you can proceed with Installaiton.

{% hint style="info" %}
* **Walk Test** should be conducted to confirm proper operation and coverage of the Motion Sensor.
* When learning Motion Sensor or conducting Walk Test, please avoid obstructing the anti-masking detector by your hand, otherwise tamper open signal will transmitted to the Control Panel if masking condition lasts for 2 minutes.
{% endhint %}

### _**Mounting Method**_

The EIRC-1-F1 is designed to be mounted on the wall. Depending on how you use the L-shaped mounting plate, the motion sensor can either be flat-mounted or side-mounted when installed on the wall.

#### **Flat Mounting**

1. Detach the EIRC-1-F1 base and cover assembly.
2. Use the mounting holes on the longer side of the L-shaped mounting plate as a template to drill holes on the wall for plugs. Fix the longer side of mounting plate on the wall with provided screws. **(Picture1)**
3. Fix the back cover of EIRC-1-F1 to the mounting plate with two provided screws. **(Picture 2)**
4. &#x20;Fit the front cover onto the back cover and tighten the bottom fixing screw. **(Picture 2)**
5. Insert the protective shield. (Please remove the protective film from both sides of the protective shield before inserting.)**(Picture 3)**

![](<.gitbook/assets/5 (32).jpeg>)



#### **Side Mounting**

1. Detach the EIRC-1-F1 base and cover assembly.
2. Use the mounting holes on the narrow side of the L-shaped mounting plate as a template to drill holes on the wall for plugs. Fix the narrow side of mounting plate on the wall with provided screws. **(Picture1)**
3. Fix the back cover of EIRC-1-F1 to the mounting plate with two provided screws. **(Picture 2)**
4. Fit the cover onto the back cover and tighten the bottom fixing screw. **(Picture 2)**
5. Insert the protective shield. **(Picture 3)** (Please remove the protective film from both sides of the protective shield before inserting.)

![](<.gitbook/assets/6 (44).jpeg>)



{% hint style="info" %}
There are three nuts on the mounting plate, providing two mounting levels (**high/low**) for selection. After the mounting plate is fixed on the wall, you can choose to mount the EIRC-1-F1 at the lower level or the higher level with two provided screws
{% endhint %}

![](<.gitbook/assets/7 (43).jpeg>)

{% hint style="info" %}
After EIRC-1-F1 is mounted, if the Control Panel displays the Tamper fault status for the device, please make sure the anti-masking detector is not obstructed by any object and wait for two minutes to see if the Tamper Open status is cleared. If Tamper Open status persists after two minutes, please remove the motion sensor from the mounting location, and check if the Tamper Switch is properly compressed against the inside of device back cover.
{% endhint %}

### _**Installation Recommendations**_

The Motion Sensor should be mounted at 1.4m\~1.6m for optimal performance. It has a maximum range of 11 meters when microwave sensor is set to maximum range and mounted at 1.6 meters height.

_\<IMPORTANT NOTE>_

{% hint style="info" %}
Please note that the performance is affected by external factors, such as height of detected object, desired detection range, installation area, etc. The suggested mounting height could be adjusted according to actual installation environment factors.
{% endhint %}

* **It is recommended to install the Motion Sensor in the following locations**
  * Mount in a position such that an intruder would normally move across the sensor’s field of view.
  * Mount where its field of view will not be obstructed e.g. by curtains, ornaments etc.
* **Limitations**
  * Do not position a Motion Sensor to look directly at a door protected by a Door Contact, this could cause the Door Contact and Motion Sensor radio signals to be transmitted at the same instant when entering, causing signal collision..
  * Do not install the Motion Sensor completely exposed to direct sunlight.
  * Avoid installing the Motion Sensor in areas where devices may cause rapid change of temperature in the detection area, i.e. air conditioner, heaters, etc.
  * Avoid large obstacles in the detection area.
  * Do not aim the sensor directly at sources of heat e.g. fires or boilers, and not above radiators.
  * Avoid moving objects in the detection area i.e. curtain, wall hanging etc.

![](<.gitbook/assets/8 (34).jpeg>)



![](<.gitbook/assets/9 (21).jpeg>)

