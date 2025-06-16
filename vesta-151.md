# VESTA-151

**IRMP-23-F1**

IRM-23 Series Motion Sensor is equipped with both PIR and Microwave motion detection technology. The combination of dual detection methods greatly improves the Motion Sensor’s detection accuracy and reduces false alarm rate, by using the PIR as initial detection, and microwave as confirmation before actually transmitting the activation signal.

The Motion Sensor has multiple models with different battery, tamper switch and Pet Immunity combination. Identify the function of your model on hand with following table before proceeding to read rest of this manual.

The PIR is designed to give a typical detection range of 12 meters when mounted at 2 meters above ground.

The Pet-Immune models of IRM-23 series PIR sensor further support pet immunity feature and will not detect pets of up to 27 kg within 7 meter range to minimize false alarm situation.

<figure><img src=".gitbook/assets/image (306).png" alt=""><figcaption></figcaption></figure>

## Parts Identification

<figure><img src=".gitbook/assets/image (307).png" alt=""><figcaption></figcaption></figure>

### 1. Transmitter LED (Red)

The LED lights up briefly when:

* The Learn/Test button is pressed.
* The Tamper Switch is triggered or restored.
* Movement is detected under Test Mode
* Movement is detected under Low Batter or Tamper open condition during normal operation When Motion Sensor battery is exhausted, the LED flashes every 4 seconds.



2. **Microwave Detection LED (Blue)**

The LED lights up briefly when Microwave detection is triggered under Test Mode or Microwave Test mode

3. **IR Detection LED (Green)**

The LED lights up briefly when IR detection is triggered under Test Mode.

### 4. Learn/Test Button&#x20;

### 5. Sensor Lens

### &#x20;6. Battery Compartment

### &#x20;7. Supervision Enable / Disable Jumper Switch (JP2)

* When set to **ON**, supervision is disabled. **(Factory default for 433AM model)**
* When set to **OFF**, supervision is enabled. **(Factory default for 868WF model)**

**(868FM and F1 models does not have JP2 Jumper, supervision is always enbled)**

### 8. Microwave Test Enable / Disable Jumper Switch (JP3)

* When the jumper is set as **ON**, the Motion sensor is under Microwave Test Mode (please see **Microwave Test Mode**)
* When the jumper is set as **OFF**, the Microwave Test Mode is disabled. **(Factory default)**

### 9. Tamper Switch&#x20;

### 10. Microwave Range Switch

The Range scale is shown on the right with the arrow pointing at the current sensitivity level:

* Turning in the **Clockwise Direction** increases detection range (Maximum 20 meters)
* Turning in the **Counter-Clockwise Direction** decreases detection range (Minimum 3\~5 meters) - **Factory Default**: is set to medium, appproximately 10 meters.

<figure><img src=".gitbook/assets/3 (96).jpeg" alt=""><figcaption></figcaption></figure>

### 11. Tamper Hole

**IRM-23A**: Tamper switch is pressed against the inside of the back cover

**IRM-23B**: The tamper switch protrudes from the hole on the back cover

### **12. Break-Away Area**

## Features

### Movement Detection

* The Motion Sensor has built-in PIR sensor and Microwave Transmitter. Motion Detection is performed by PIR Sensor during normal operation. When PIR Sensor detects movement, the Microwave Transmitter will be activated to verify the movement detection. If both PIR and Microwave confirms movement detection, the Motion Sensor will transmit detection signal.
* Detection signal will only be transmitted when both PIR and Microwave detects movement.
* Adjust Microwave Range Switch setting to tune the Microwave Transmitter and overall detection range.
* When Microwave Range Switch is set to Maximum, the Motion Sensor has an approximate range of 12 meters when mounted at 1.9\~2m height.
* When Microwave Range Switch is set to Minimum, the Motion Sensor has an approximate range of 3\~5 meters when mounted at 1.9\~2m height.

### Sleep Timer

After transmitting a detected movement signal, the Motion Sensor will not retransmit for 1-minute sleep period. Any further movement detected during the Sleep Period will reset the sleep time to 1 minute. In this way continuous movement in front of the Motion Sensor will not unduly exhaust the battery.

### Test Mode

The Motion Sensor can be put into Test mode by pressing the Learn /Test button. Test Mode lasts 3 minutes and will be reset to 3 minutes by any Learn/Test button press. When under Test Mode, the Sleep Timer is disabled and the LEDs will light up when the Motion Sensor detects movement to notify user.

Use the Test mode to determine the detection coverage of Motion Sensor when installing the sensor.

### Microwave Test Mode

The Microwave Test Mode is for microwave range test only. Use the JP3 Jumper to enable Microwave Test Mode. When the Motion Sensor is under Microwave Test Mode, PIR detection is disabled, the Microwave Transmitter will be activated to repeatedly send microwave signal for movement detection. When the Motion Sensor detects movement under Microwave Test Mode, the Microwave Blue LED will light up briefly to indicate.

Use the Microwave Test Mode to determine the microwave range and adjust range with Microwave Range Switch if required. Make sure to disable Microwave Test Mode after testing is complete by setting JP3 Jumper to OFF and return the Motion Sensor to normal opeation.

### Battery

* The Motion Sensor uses different battery depending on the sensor model.

<figure><img src=".gitbook/assets/image (308).png" alt=""><figcaption></figcaption></figure>



* The Motion Sensor features low battery detection, when low battery voltage is detected, a low-battery signal will be sent to the Control Panel along with regular signal transmissions (e.g., transmission of the supervisory signal when Supervision is enabled).
* If supervision is disabled, the low-battery status is transmitted to the control panel every 12 hours.
* If battery is not changed after low battery detection and the battery is fully exhausted, the Motion Sensor will stop all operation. The Red LED will flash every 4 seconds to indicate.
* When changing batteries, after removing the old batteries, press the Tamper Switch or Learn/Test a couple times to fully discharge before inserting new batteries.

### Supervision

If enabled, the Motion Sensor will transmit a supervisory signal once every 30 to 50 minutes

If the Control Panel fails to receive the Supervisory signals transmitted from a certain Motion Sensor for a preset time, the Control Panel will determine the particular sensor is out of order.

### Tamper Switch

The tamper switch on the Motion Sensor operates differently according to Motion Sensor models.

* **IRM(P)-23A Series:** The Tamper switch is in normal position (Tamper closed) when the spring is compressed against the inside of device back cover. Tamper violation happens when the cover is removed from the base and releases the tamper switch.
* **IRM(P)-23B Series** The Tamper Switch protrudes from the hole on device back cover and is in normal operation position when the Motion Sensor is properly mounted and the tamper switch pressed against mounting location. Tamper violation happens when the device is removed from the mounting surface and releases the tamper switch.
* **Break-Away Areas**

The Motion Sensor back cover has 2 hollowed **break-out areas**. When the device is properly installed, if an intruder forcibly removes the Motion Sensor from mounted location, the break-away areas will break off from the back cover and remain attached to the mounting surface while the device main body is removed, activating the tamper switch.

## Learning and Installation

### Getting Started

1. Orient and insert the battery according to polarity.
2. The Red Transmitter LED will begin to flash for 30 seconds to indicate the Motion Sensor is warming up. During the warming up period, the Motion Sensor will not be activated. It is recommended that you stay away from the detection area during this time. After the warming-up period, the Red will turn off and the Motion Sensor will enter normal operation.

<figure><img src=".gitbook/assets/4 (79).jpeg" alt=""><figcaption></figcaption></figure>



3. Put the Control Panel into learning mode; refer to Control Panel manual for detail.
4. Press the Learn/Test Button to transmit signal to panel.
5. If the panel receives signal from Motion Sensor, it will display sensor info accordingly. Refer to your Control Panel to complete the learn-in process.
6. After the Motion sensor is learnt-in, put the Control Panel into “Walk Test” mode; hold the sensor in the desired location, and press the Test Switch to confirm whether this location is within the signal range of the Control Panel.
7. When you are satisfied with the chosen location, you can proceed with Installaiton.

### Mounting Method

* The Motion sensor is designed to be mounted on either a flat surface or in a corner with fixing screws and plugs provided.
* The base has knockouts, where the plastic is thinner, for mounting purpose. Two knockouts are located on the back for surface fixing and four knockouts on the sides for corner fixing.
* For IRM-23B corner mounting, a triangular bracket is provided to add Back Tamper Protection. The bracket also includes two knockouts to mount on the wall.
* For IRM-23B surface mounting, an optional rotating bracket is provided for users to adjust the range of detection. With the rotating bracket, the IRM-23 can be rotated 80 degrees horizontally and 70 degrees vertically to provide optimal coverage.

<figure><img src=".gitbook/assets/image (309).png" alt=""><figcaption></figcaption></figure>

* **Corner mounting for IRM-23A:**
  1. Detach the base and cover assembly with a screwdriver to loosen the bottom fixing screw.
  2. Break through the four corner knockouts.
  3. Use the four holes as a template and drill holes in the surface of the corner.
  4. Insert the wall plugs.
  5. Screw the base into the wall plugs.
  6. &#x20;VI. Fit the base onto the cover.
  7. VII. Tighten the bottom fixing screw.
* **Corner mounting for IRM-23B:**
  1. Break through the knockouts on the **triangular bracket**.
  2. Use the two holes as a template and drill holes in the surface of the corner. III. Insert the wall plugs
  3. Screw the bracket into the wall plugs
  4. Locate the **Bracket Insertion Holes** and fit the holes onto the **Bracket Insertion Hooks**. Fitting the sensor onto the bracket should compress the Tamper switch onto the **Tamper Compression Protrusion** on the bracket.

<figure><img src=".gitbook/assets/6 (65).jpeg" alt=""><figcaption><p><strong>Bottom Fixing Screw</strong></p></figcaption></figure>



* **Surface mounting:**
  1. Detach the base and cover assembly with a screwdriver to loosen the bottom fixing screw.
  2. Break through the knockouts on the inside of base.
  3. Use the holes as a template and drill holes in the surface.
  4. Insert the wall plugs if fixing it into plaster or brick.
  5. &#x20;V. Screw the base into the wall plugs. VI. Fit the base onto the cover.
  6. VII. Tighten the bottom fixing screw.
* **Surface mounting with rotating bracket (optional item, sold separately) for IRM-23B:** The rotating bracket can be mounted on the wall with the provided screws. I. Screw the rotating bracket into the wall.
  1. Fit the 3 hooks of the rotating bracket into the 3 holes of the base accordingly.
  2. Rotate the bracket for the proper range of detection and tighten the fixing screw.

<figure><img src=".gitbook/assets/7 (91).png" alt=""><figcaption></figcaption></figure>

### Installation

* Decide on the location of the Motion Sensor and if it is to be corner or surface mounted.
* After the installation site is selected, follow the steps described above to mount the Motion Sensor.
* Press the Test Switch to enter Test Mode. Walk around the protected area noting when the LED lights up and check that the detection coverage is adequate.
* When detection coverage is found to be satisfying, installation is now completed.

### Installation Recommendations

The Motion Sensor should be mounted at 1.9m\~2.0m for optimal performance. It has a maximum range of 12 meters when microwave sensor is set to maximum range and mounted at 2 meters height. The pet immune models do not detect pets up to 27 kg within 7 meter range to minimize false alarm situation.

![](<.gitbook/assets/8 (62).jpeg>)

{% hint style="danger" %}
_IMPORTANT NOTE_

* For the most desirable performance, remember to adjust the height of the Motion Sensor according to the height of the tallest animal in the house. Taller animals require the sensor to be mounted higher for the Pet Immunity purpose.
* When deciding on the height of the sensor mounting site, remember to take any possible blind spot into consideration. The blind spot underneath the sensor enlarges proportionally to the height of the mounting site.
* Please note that the performance is affected by external factors, such as height of detected object, desired detection range, installation area, etc. The suggested mounting height could be adjusted according to actual installation environment factors.
* When IRM-23 is mounted with rotating bracket, it will not have the regular detection area (as in the above diagram), or the typical pet immue range.
{% endhint %}

* **It is recommended to install the Motion Sensor in the following locations**
  * Mount where the animals cannot come to the detection area by climbing on furniture or other objects.
  * Avoid aiming the sensor at stairways where the animals can climb on.
  * Mount in a position such that an intruder would normally move across the sensor’s field of view.
  * Mount in a corner to give the widest view.
  * Mount where its field of view will not be obstructed e.g. by curtains, ornaments etc.
* **Limitations**

<figure><img src=".gitbook/assets/image (310).png" alt=""><figcaption></figcaption></figure>

<figure><img src=".gitbook/assets/image (311).png" alt=""><figcaption></figcaption></figure>
