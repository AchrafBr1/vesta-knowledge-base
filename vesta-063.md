# VESTA-063

Dual technology curtain outdoor sensor\



<figure><img src=".gitbook/assets/vesta-063 F.jpg" alt="" width="167"><figcaption></figcaption></figure>

### INTRUDUCTION

It creates a curtain barrier of small dimensions (about 7.5°) and&#x20;has an adjustable range up to 12 m. It is made with&#x20;weather-resistant materials and the container is completely&#x20;watertight. Furthermore, the electronics are subjected to a&#x20;tropicalization process to ensure correct operation in all&#x20;conditions of humidity and temperature.&#x20;It is a very stable sensor and immune to false alarms.

TECH SPECIFICATION

* &#x20;   Coverage: 12 meters, 7.5 °
* &#x20;   Microwave frequency: 24 GHz
* &#x20;   Sensitivity setting: 1 MW Trimmer / 1 IR Trimmer
* &#x20;   Working mode
* &#x20;   Alarm relay output
* &#x20;   Tamper
* &#x20;   Power supply: 3V \~ 10V DC
* &#x20;   Consumption: 8µA
* &#x20;   Protection degree IP54
* &#x20;   Dimensions: 37 (W) x 125 (H) x 40mm

### PART IDENTIFICATION

<figure><img src=".gitbook/assets/image (316).png" alt=""><figcaption></figcaption></figure>

1. 3-10V power supply
2. Alarm terminal block (AL-NC, AL-NO, AL-C)
3. Tamper terminal block (TP-NC, TP-NO, TP-C)
4. Red LED: in test mode detection alarm, in stand-by detection alarm if set (Dip3)
5. Dip Switch
6. Tamper
7. Microwave trimmer
8. Yellow LED  in test mode mW detection, in stand-by, low battery warning if set (Dip1)
9. Green LED: In test mode, Infrared detection
10. fixing screw
11. Infrared trimmer
12. Microwave sensor
13. PIR

INSTALLATION

<table><thead><tr><th width="78"></th><th></th></tr></thead><tbody><tr><td>DIP 1</td><td>ON: Low battery warning. Yellow LED flashes every 2 seconds if battery is low</td></tr><tr><td>DIP 2</td><td>Inhibition duration. ON long inhibition (6 minutes) otherwise 3 minutes</td></tr><tr><td>DIP 3</td><td>ON: Alarm signal in stand-by. The red LED lights up in case of detection even if the sensor is low consumption</td></tr><tr><td>DIP 4</td><td>ON: Test mode. If the dip is ON -> always in test (no inhibition, LEDs active), if OFF after 3 minutes it exits the test mode</td></tr></tbody></table>

<figure><img src=".gitbook/assets/image (317).png" alt=""><figcaption></figcaption></figure>

#### Range test in test mode

Open the cover, set Dip4 to ON, close the cover. From this moment the LEDs are&#x20;always active and the sensor is no longer inhibited. Adjust the infrared&#x20;and/or microwave range. Once the tests are complete, open the cover, set Dip4 to OFF and close&#x20;the cover. For a further 3 minutes the sensor is in test. After this time, the sensor enters&#x20;low consumption mode.

#### Low Battery

If the sensor is not powered by the transmitter battery, but by the internal battery (supplied separately), set Dip1 to ON. When the battery voltage drops below the preset threshold, the yellow LED flashes every (approximately) 20s.

#### Intrusion

By setting Dip3 to ON, the sensor activates the red LED for a few seconds each time it detects an intrusion. The signalling affects consumption by decreasing battery life. Remember that&#x20;after each detection, the sensor remains inactive for at least 3-6 minutes (see Dip2).
