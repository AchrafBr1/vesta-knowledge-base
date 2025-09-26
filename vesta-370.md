# VESTA-370

&#x20;**VST-894-IL**

## **Outdoor PIR Motion Sensor Camera**&#x20;

VST-894 is an outdoor passive infrared (PIR) motion sensor camera. It is capable of sending wireless signals and captured images (picture quality of up to 1280 x 720 pixels) to the Control Panel upon movement detection.

Featuring night illumination capability, with UV resistant housing, and waterproof to IPX5 standard, VST-894 is ideal for backyards, lawns, gates, outdoor corridors and hallways.

The outdoor PIR Camera is designed to give a typical detection range of 12 meters by 90 degrees wide. The flexible PIR distance limit is adjustable to 5 levels (12M, 8.5M, 6M, 3.5M, 2.5M); the suggested mounting height is 0.8-1.2M. Featuring pet immunity, the PIR Camera can prevent false alarms triggered by pets or small to medium size animals (up to 25 kg).

Besides, VST-894 is designed with the digital proximity detector. The anti-masking feature allows for detection of any attempts to blind the detector by placing objects in its field of view.

VST-894 is also compatible with Climax’s Repeater RP-29/Router RMB-29, which can further extend the RF communication range into hard-to-reach areas.

**The VST-894 Series includes the following models**:

VST-894 – PIR motion sensor camera with flash LED

VST-894-IL – PIR motion sensor camera with Infrared LED

## Identifying the Parts

<figure><img src=".gitbook/assets/image (4) (1) (1) (1) (1) (1) (1) (1) (1).png" alt=""><figcaption></figcaption></figure>

1 PIR Camera Lens&#x20;

2 Flash LED / Infrared LED

The Flash LED (VST-894) or Infrared LED (VST-894-IL) delivers sufficient light for image capture under low lighting condition.

**3 IR LED Indicator (Red)**&#x20;

**4 IR Sensor**

The sensor is intended to detect moving objects.

5. **Front Tamper**

The front tamper is compressed when the camera face cover is properly installed.

6. **Camera Angle Adjustment Scale**
7. &#x20; **Dip Switch Block**
8. &#x20; **Detection Length Adjustment Switch**
9. &#x20; **IR Angle Adjustment Scale**
10. &#x20; **IR Cover Unit Tamper**

The IR cover unit tamper is compressed when the IR cover unit is properly closed.

11 PIR Sensitivity Selector&#x20;

12 Test & Learn Button

* Press and hold the button for 3 seconds to send a learn code, and then release the button when VST-894 LED Indicator (Red) lights up.
* Press the button once to send a learn code to the repeater/router.

13 Battery Compartment

&#x20;14 Rear Tamper

The rear tamper switch is compressed when the PIR Camera is properly installed onto the mounting bracket. **15 VST-894 LED Indicator (Red)**

**16 Hook Holes**

&#x20;**17 Hooks**

&#x20;**18 Top Stabilizing Screw Hole**

&#x20;**19 Bottom Stabilizing Screws**

### LED Indicator

**IR LED (Red)**

* The LED indicator can be enabled / disabled by setting the DIP VST-894 LED Indicator IR LED Indicator Switch1 position or remotely controlled from the panel. Please refer to the _**DIP Switch Settings**_ and _**Remote Settings**_ section for details.

<figure><img src=".gitbook/assets/2 (1) (1).jpeg" alt=""><figcaption></figcaption></figure>

<figure><img src=".gitbook/assets/3 (1) (1).jpeg" alt=""><figcaption></figcaption></figure>

* When disabled, the LED will not be activated except during warm-up and test mode.
* When enabled, the LED will light up according to the detector's status. - **Warm-up:** the Red LED flashes for 60 seconds.
  * **IR movement detection:** the Red LED lights up for 2 seconds.
  * **Masking detection:** the Red LED flashes 3 times and repeats until the masking condition is cleared. **VST-894 LED Indicator (Red)**
* The LED is ON when the PIR Camera is in learning mode.
* When the PIR Camera receives acknowledgement from the Control Panel, the LED of the PIR Camera will flash 6 times and then turn off to indicate successful learning.

### Battery

* The PIR Camera uses four AA L91 lithium batteries as its power source.
* The PIR Camera’s battery level will be reported to the Control Panel with transmission of regular supervisory signals
* The PIR Camera features low battery voltage detection. When low battery is detected, a low battery signal will be sent to the Control Panel.

**To change the batteries:**

<figure><img src=".gitbook/assets/4 (1) (1).jpeg" alt=""><figcaption></figcaption></figure>

**Step 1** Remove the PIR Camera from the mounting bracket.

**Step 2** Loosen the 4 fixing screws of the battery compartment and open the cover.

**Step 3** Remove the old batteries and press the test button twice to fully drain the residual energy.

**Step 4** Insert four new AA L91 lithium batteries.

**Step 5** Press the test button once. A battery normal signal will be sent to the Control Panel.

**Step 6** Screw back the battery compartment cover.

**Step 7** Hook the PIR Camera back to the mounting bracket.

### Tamper Protection

* The PIR Camera is protected against any attempts to open the camera face cover, the IR cover unit, and to detach the device from its mounting bracket, or to forcibly remove the whole unit from the mounting location.
* If the PIR Camera detects a tamper condition of camera face cover opening, IR cover unit opening, or device removal, a tamper signal will be sent to the Control Panel to remind the user of the condition.

### Supervision Signal

* After installation, the PIR Camera will automatically transmit Supervisory signals periodically to the Control Panel at random intervals of 15-18 minutes.
* If the Control Panel has not received the signal from the PIR Camera for the preset period of time, the Control Panel will indicate on its display that the particular PIR Camera is experiencing an out-of-signal problem.

### Image Capture

When the alarm system is armed, the PIR Camera will capture 1, 3 or 6 alarm images in resolutions of 640 x 360, 320 x 184, or 1280 x 720 pixels (programmable from Control Panel) upon movement detection. You can also manually request the PIR Camera to take a picture through the Control Panel. The captured images will be transferred to the Control Panel for visual alarm verification.

{% hint style="warning" %}
Note:

&#x20;If your PIR Camera is installed at a location where the camera’s field of view is a complex environment with intense light or lots of colors, the images captured will be great in file size, possibly leading to truncation when the images are transmitted to the Control Panel.
{% endhint %}

### Sleep Timer

* The PIR Camera features an automatic “sleep time” of 5 seconds or 120 seconds (default) for power conservation. The sleep timer can be programmed by DIP Switch 3 or remotely adjusted from the Control Panel. Please refer to the _**DIP Switch Settings**_ and _**Remote Settings**_ sections for details.
* Even if there are continuous movements detection, the alarm is generated only once in the sleep timer period to save the battery life.

### Anti-Masking

* The PIR Camera has a digital proximity detector that can detect any masking (blocking) attempt by an intruder. The Anti-Masking feature can be turned on (default) or off by setting the position of DIP Switch 4 or remotely controlled from the panel. Please refer to the _**DIP Switch Settings**_ and _**Remote Settings**_ sections for details.
* Under normal operation mode, when a masking event is detected, and the masking condition lasts for 3 minutes, VST-894 will send a masking alarm signal to the Control Panel to notify user of the masking condition.

### PIR Sensitivity

The PIR sensitivity can be set to High, Middle (default), or Low by using the PIR sensitivity selector or remotely programmed from the Control Panel. Please refer to _**Dip Switch Settings & PIR Sensitivity Setting**_ and _**Remote Settings**_ sections for details.

### Warm-Up Period

* The PIR Camera will warm up for 60 seconds or less when powered on.
* The IR Red LED will keep flashing; the PIR Camera will not be activated in the warm-up period.

### Local Setting

To adjust the PIR Camera Settings locally, you will need to remove the cover unit to access the local switches or selectors. Follow the steps below to proceed.

1\) Remove the camera face cover.

<figure><img src=".gitbook/assets/5 (1) (1) (1) (1).jpeg" alt=""><figcaption><p>Remove the camera face cover.</p></figcaption></figure>

2\) Lift the camera module from the arc side.

<figure><img src=".gitbook/assets/7 (2).jpeg" alt=""><figcaption><p>Lift the camera module from the arc side.</p></figcaption></figure>

3\) Unlock the bottom lock, and remove the cover unit.

<figure><img src=".gitbook/assets/6 (1) (1) (1).jpeg" alt=""><figcaption><p>Unlock the bottom lock, and remove the cover unit.</p></figcaption></figure>

#### PIR Area Direction & Camera Direction Adjustment

* The angles of both the camera module and the IR sensor can be adjusted in 7 levels from A to G.
* The angle of the camera and the angle of the PIR sensor must be consistent to ensure optimum coverage. For example, if you set the PIR sensor angle to level A, please also set the camera angle to level A.

_\<NOTE>_

{% hint style="warning" %}
Note:

Do not adjust the camera module when it is lifted. Adjust the camera module only when it is in normal operation position.
{% endhint %}

<figure><img src=".gitbook/assets/8 (1) (1) (1) (1).png" alt=""><figcaption></figcaption></figure>

![](<.gitbook/assets/9 (1) (1) (1) (1) (1) (1).png>)

#### PIR Detection length adjustment

The PIR distance limit can be adjusted in 5 levels (2.5 to 12m).

![](<.gitbook/assets/10 (1) (1) (1) (1) (1) (1).png>)

#### Dip Switch Settings & PIR Sensitivity Setting

* The functions of each DIP Switch and the PIR sensitivity selector are listed in the tables below. After Dip Switch and PIR sensitivity settings are changed, please remove batteries, and then re-insert batteries to power on the PIR Camera. The device will operate with new settings after re-powered on.
* Please note that LED, anti-masking, sleep timer and PIR sensitivity can also be remotely programmed from the Control Panel. Setting remotely from the Panel will overwrite DIP Switch settings. (Refer to _**Remote Settings**_ for details.)

{% hint style="warning" %}
Note:

Please _**DO NOT**_ change the default setting of Dip Switch 2 (N.C.).
{% endhint %}

<figure><img src=".gitbook/assets/11 (1) (1) (1).jpeg" alt=""><figcaption></figcaption></figure>

### PIR Area Masking

The PIR Camera is provided with a masking seal to ignore specific areas that either are not required to be secured or may cause false or nuisance alarms, such as a swaying tree in full foliage.  To mask out a specific area:

<figure><img src=".gitbook/assets/image (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1).png" alt=""><figcaption></figcaption></figure>

<figure><img src=".gitbook/assets/image (2) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1).png" alt=""><figcaption></figcaption></figure>

### Test Mode

Test Mode should be conducted to confirm proper operation and coverage of the PIR Camera.

In Test mode, sleep timer is disabled, and the LED indicator will turn on to indicate the detection status.

* Close the cover unit, “TEST MODE” starts automatically.

![](<.gitbook/assets/15 (1) (1).jpeg>)

* Check if the LED lights up for 2 seconds when the intended object is detected.

![](<.gitbook/assets/16 (1) (1).jpeg>)

* “TEST MODE” expires 3 minutes after closing the cover unit, with IR Red LED blinking for 5 seconds.

### Getting Started – Learning the PIR Camera into the Control Panel

* Insert four AA L91 lithium batteries into the battery holder to power on the PIR Camera, making sure to connect the polarity correctly.
* The PIR Camera will start to warm up and flash its IR Red LED for 60 seconds. Wait for warm-up process to complete.
* Put the Control Panel into learning mode; refer to Control Panel manual for details.
* Press and hold the Test button for 3 seconds to send a learn code, and then release the button when VST-894 Red LED lights up. The LED will be on for 20 seconds at most, indicating the PIR Camera is in learning mode.
* If the Control Panel receives the signal from the PIR Camera, it will display the information accordingly. Within 20 seconds when the LED of the PIR Camera is on, select the PIR Camera on the Control Panel Webpage and click “**add**” to include it into the Panel. Refer to the Control Panel manual for details.
* When the PIR Camera receives acknowledgement from the Control Panel, the VST-894 Red LED will flash 6 times and then turn off to indicate successful learning.
* After the PIR Camera is learnt-in, put the Control Panel into Walk Test mode. Hold the PIR Camera in the desired location, and press the Test button to confirm if this location is within the signal range of the Control Panel.

{% hint style="warning" %}
Note:

* After the Test button is pressed and held for 3 seconds, the LED of the PIR Camera will be on for 20 seconds. If the PIR Camera does not receive acknowledgement from the Control Panel within this 20-second period, the LED will turn off. The Test button needs to be pressed and held for 3 seconds again to resend a learning code.
* If the PIR Camera already exists in a Control Panel system, you will need to first remove the PIR Camera from the Control Panel before you can learn it into a different Control Panel.
* When learning the PIR Camera into a repeater/router, please press the Test button once (instead of pressing and holding it for 3 seconds) to send a learn code.
{% endhint %}

### Edit Device Operation Area

1. Use the “Edit Device” function on the Panel’s webpage to change the area setting.
2. For the device communicating directly with the Panel, the setting is completed after clicking OK.

For the device using a Repeater, press and hold the Test button for 3 seconds on the PIR Camera to send a signal to the panel, and then release the button when VST-894’s LED lights up.

### Remote Settings

* The PIR Camera supports remote settings of PIR sensitivity, anti-masking, sleep timer and LED from the Control Panel.
* When the PIR Camera is powered on, its PIR sensitivity, anti-masking, sleep timer and LED are determined by the DIP Switch settings. (Refer to **Dip Switch Settings** for details.) Users can change the settings either by adjusting DIP Switches or programming from the Panel remotely. Setting remotely from the Panel will overwrite DIP Switch settings.

**Control Panel Webpage**

1. On the Panel’s local webpage, go to the Edit Device page and input the IR configuration value in the Sensor Setting section. Click OK to confirm. Please refer to the table below for configuration details. For example, if you want to set PIR Sensitivity level to low, turn off the LED, set the sleep timer to 120 seconds and disable the anti-masking function, you can input 00.
2. Press the Test button once on the PIR Camera to send a signal to the Control Panel for the new settings to be applied immediately. If the button is not pressed, the new settings will be applied upon next signal transmission, i.e., transmission of the supervisory signals or PIR alarm signals.

| **IR Configuration** | **PIR Sensitivity** | **LED** | **Sleep Timer (T)** | **Anti-masking (A)** |
| -------------------- | ------------------- | ------- | ------------------- | -------------------- |
| 00                   | Low                 | Off     | 120 seconds         | Disable              |
| 01                   | Low                 | On      | 120 seconds         | Disable              |
| 02                   | Low                 | Off     | 5 seconds           | Disable              |
| 03                   | Low                 | On      | 5 seconds           | Disable              |
| 04                   | Low                 | Off     | 120 seconds         | Enable               |
| 05                   | Low                 | On      | 120 seconds         | Enable               |
| 06                   | Low                 | Off     | 5 seconds           | Enable               |
| 07                   | Low                 | On      | 5 seconds           | Enable               |
| 40                   | Medium              | Off     | 120 seconds         | Disable              |
| 41                   | Medium              | On      | 120 seconds         | Disable              |
| 42                   | Medium              | Off     | 5 seconds           | Disable              |
| 43                   | Medium              | On      | 5 seconds           | Disable              |
| 44                   | Medium              | Off     | 120 seconds         | Enable               |
| 45                   | Medium              | On      | 120 seconds         | Enable               |
| 46                   | Medium              | Off     | 5 seconds           | Enable               |
| 47                   | Medium              | On      | 5 seconds           | Enable               |
| 80                   | High                | Off     | 120 seconds         | Disable              |
| 81                   | High                | On      | 120 seconds         | Disable              |
| 82                   | High                | Off     | 5 seconds           | Disable              |
| 83                   | High                | On      | 5 seconds           | Disable              |
| 84                   | High                | Off     | 120 seconds         | Enable               |
| 85                   | High                | On      | 120 seconds         | Enable               |
| 86                   | High                | Off     | 5 seconds           | Enable               |
| 87                   | High                | On      | 5 seconds           | Enable               |

### Mounting & Installation Method

**Before proceeding to mount VST-894 (Optional Step):**

1. Assemble the PIR Camera and tighten the flat-tailed top fixing screw.

![](<.gitbook/assets/17 (1) (1).jpeg>)

2. Align the arc part of the Mylar tape to the arc part of the bottom of VST-894; apply the Mylar tape to the bottom to provide stronger hold and fixation.

![](<.gitbook/assets/18 (1) (1).jpeg>)

3. Bend the Mylar tape along the rounded edge of VST-894 to the back thereof.

![](<.gitbook/assets/19 (2).jpeg>) ![](<.gitbook/assets/20 (2).jpeg>)

**Mounting with the mounting bracket:**

* The PIR Camera is designed to be mounted either on a flat surface or in a corner with the fixing screws and wall plugs provided.
* The mounting bracket has knockouts, where the plastic is thinner and can be broken for mounting purpose. Three knockouts are for surface fixing and four knockouts are for corner fixing as shown in the picture.

<figure><img src=".gitbook/assets/image (3) (1) (1) (1) (1) (1) (1) (1) (1) (1).png" alt=""><figcaption></figcaption></figure>

1. For surface fixing, use the mounting bracket as a template to drill 3 holes into the wall to be mounted. For corner fixing, drill 4 holes into the wall.
2. Push in the wall plugs if the PIR Camera is to be mounted onto plaster or bricks.
3. Screw the mounting bracket on the wall.
4. Hook the PIR Camera onto the mounting bracket and push downwards until you hear a click sound.

{% hint style="warning" %}
Note:

Please make sure the PIR Camera is properly hooked to the mounting bracket, so that the rear tamper switch is fully depressed.
{% endhint %}

**Surface Mounting**

<figure><img src=".gitbook/assets/image (4) (1) (1) (1) (1) (1) (1) (1) (1) (1).png" alt=""><figcaption></figcaption></figure>

**Corner mounting**

<figure><img src=".gitbook/assets/image (5) (1) (1) (1) (1) (1) (1) (1) (1).png" alt=""><figcaption></figcaption></figure>

5. **(Optional Step)** On the top of the PIR Camera, fit the stabilizing screw to the socket provided and screw them into the mounting bracket. Fasten the two bottom stabilizing screws at the bottom of the mounting bracket into the bottom of VST-894 to firmly secure the device to the bracket.

<figure><img src=".gitbook/assets/image (6) (1) (1) (1) (1) (1) (1) (1).png" alt=""><figcaption></figcaption></figure>

### Installation Recommendations

**It is recommended to install the PIR Camera in the following locations:**

* At a height of 0.8 to 1.2 m (2′7″ to 4′) above ground level, where an intruder would normally move across the PIR Camera’s field of view.
* When installed in the corner (45 degrees), the PIR & Camera angles level C/D/E are recommended with level D offering the best quality.
* When installed flat (0 degrees), all 7 angles (A/B/C/D/E/F/G) work well.
* Below is the Area diagram of horizontal position D.
* The PIR Camera has a maximum detection range of 12 meters by 90 degrees wide.

<figure><img src=".gitbook/assets/image (7) (1) (1) (1) (1).png" alt=""><figcaption></figcaption></figure>

**Limitations:**

* Do not expose the PIR Camera completely to direct sunlight.
* Avoid large obstacles in the detection area.
* Do not point directly at sources of heat, such as fires and boilers, or install above radiators.
* Never attempt to disassemble or modify the unit.
* Please install the PIR Camera straight up. Do not tilt it.

<figure><img src=".gitbook/assets/image (8) (1) (1) (1) (1).png" alt=""><figcaption></figcaption></figure>

* Do not install the motion sensor camera at places where objects such as trees and laundry are moved by the wind, which may block the motion sensor camera’s field of view.

<figure><img src=".gitbook/assets/image (9) (1) (1) (1) (1).png" alt=""><figcaption></figcaption></figure>

* Clear all light-reflecting surfaces from the detection area, as well as water puddles.

<figure><img src=".gitbook/assets/image (10) (1) (1) (1) (1).png" alt=""><figcaption></figcaption></figure>

* Avoid aiming at the path of outdoor unit’s intake or exhaust airflow or exhaust airflow.

<figure><img src=".gitbook/assets/image (11) (1) (1) (1) (1).png" alt=""><figcaption></figcaption></figure>
