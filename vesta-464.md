# VESTA-464

DBRA 2 F1

## Decibels Recognition Alarm (DBRA-2)

<figure><img src=".gitbook/assets/image (459).png" alt=""><figcaption></figcaption></figure>



The Decibels Recognition Alarm (DBRA-2) recognizes preset sound levels in decibels and activates an alarm. It&#x20;is ideal for use in homes that are often vacant to protect against burglary or unauthorized entry.

## Parts Identification

<figure><img src=".gitbook/assets/image (451).png" alt=""><figcaption></figcaption></figure>

***

### 1. Test Button (with Red Backlight)

* Press once to activate an alarm.
* Press and hold for 3 seconds to send a learn code.
* Press and hold for 8 seconds to send a cancel code to the Panel.
* Red backlight will flash when a signal is transmitted to the Control Panel.
* The red backlight flashes 3 times when sending a test/learn code.

### 2. LED Indicator (Green/Red)

* Green LED ON: When external power supply is connected.
* Green LED OFF: When external power supply is removed.
* Red LED flashes for three times: Low battery status detected when powered on.
* Red LED flashes once every 5 seconds: Low battery status detected during operation.

### 3. Microphone (for Decibels Recognition)

### 4. Battery Compartment

### 5. DIP Switch Set

### 6. Keyhole

### 7. DC Jack (with Locking feature)

Plug in a DC 5V power adpator and rotate it 90 degrees clockwise to the lock position. To remove the adapter, rotate it 90 degrees counterclockwise to the original open position and then remove it.

***

## Power Supply

* DBRA-2 can be powered by connecting to a 5V DC power supply or two Type C batteries.
* When DBRA-2 is connected to a 5V DC power supply, the green LED will turn on. When DC power supply is removed, DBRA-2 will switch to using batteries (if batteries are already installed and not exhausted) and continue operation; the green LED will turn off.
* When powered by Type C batteries, DBRA-2 will transmit any detected low battery status along with regular status signal transmissions to the Control Panel for display accordingly.
* When changing the batteries, please remove the back cover by unscrewing the fixing screw, and then insert a flat-head screwdriver to lift the back cover. Remove the old batteries, and then press the Help Button twice to fully discharge the residual power before inserting new ones.

***

## Getting Started – Learning into the Panel

{% stepper %}
{% step %}
### Step&#x20;

Connect DBRA-2 to power supply, or insert the batteries to power it on.
{% endstep %}

{% step %}
### Step

Put the Control Panel into learning mode (Refer to your Control Panel’s operation manual).
{% endstep %}

{% step %}
### Step

Press and hold the Help Button on the device for 3 seconds and release it until the red backlight lights up to transmit a learn code to the Panel.

* If the button is not released and is kept being held for 8 second, the device will send a Cancel Code instead and its red backlight will rapidly flash 6 times.
{% endstep %}

{% step %}
### Step

When the device’s red backlight is on (for up to 60 seconds), press “**Add**” on the Panel’s webpage to enroll the device. When it receives an acknowledgement from the Panel, it will turn off the red backlight and beep twice to indicate successful learning.

* If the Panel does not receive the learn code, pressing the Help Button once during the 60 seconds will send the learn code again, and the 60 seconds will be reset.
* If the device is not added within the 60 seconds, please repeat step 3 to retry.
{% endstep %}
{% endstepper %}

***

## Supervision Signal

* DBRA-2 will automatically transmit supervision signals every 15 to 18 minutes.
* If the Control Panel has not received the supervision signal for a preset period of time, it will indicate that the device is out of signal range or out of order.

***

## Sensitivity & Sound duration

* The decibels recognition function has eight sensitivity sound pressure levels: **65 dB (1), 70 dB (2), 75 dB (3), 80 dB (4), 85 dB (5), 90 dB (6), 95 dB (7), 97.5 dB (8)**. (1) is the most sensitive, while (8) the least.
* An alarm is activated when the sound reaches the preset sound pressure level (dB SPL) and persists for the configured duration **(2 options: Long: 2 seconds, Short: 100 milliseconds)**.
* The sensitivity level can be set using DIP Switches 1, 2, and 3, while DIP Switch 4 is used to set the sound duration. See **Dip Switch Settings** below for more information.
* Alternatively, users can configure the sensitivity level and sound duration via the Panel’s webpage, Home Portal Server, or the SmartHomeSec app. See **Remote Configuration** below for details.
* The most recent configuration takes effect, whether set via DIP switches, the app, the Server, or the Panel’s webpage.

***

## Dip Switch Settings

Remove the back cover by unscrewing the fixing screw, and then insert a flat-head screwdriver to lift the back cover.

* Based on your needs, set the Sensitivity Switch as shown in the Dip Switch Position Table.

<figure><img src=".gitbook/assets/image (452).png" alt=""><figcaption></figcaption></figure>

* Please use a sharp tool to adjust the DIP Switch positions to set the sensitivity level and sound detection time duration.

<figure><img src=".gitbook/assets/image (453).png" alt=""><figcaption></figcaption></figure>

***

## Remote Configuration

Remote Configuration includes setting adjustments via the Panel’s webpage, the Home Portal\
Server, and the SmartHomeSec app.

**Panel’s webpage**

* On the Panel’s webpage, click “DBRA Setting” in DBRA entry.
*  Available functions:  \
   Configuration: displays current sensitivity and sound duration settings.  \
   Command – Query configuration: queries the current settings.  \
   Command – Set configuration: applies new settings.

<figure><img src=".gitbook/assets/image (454).png" alt=""><figcaption></figcaption></figure>

* The configuration command uses four numeric digits in the format “XXYY”, where XX sets the  \
  sensitivity level, and YY sets the sound duration.
* Below is the input value for each setting:

<figure><img src=".gitbook/assets/image (455).png" alt=""><figcaption></figcaption></figure>

* Example: Entering 0300 sets the device to trigger an alarm when a sound level of 80 dB is detected  \
  and sustained for 100 milliseconds.

**Home Portal Server**

* Select the desired sensitivity level and time duration; click “Submit” to confirm and apply the new  \
  settings.

<figure><img src=".gitbook/assets/image (456).png" alt=""><figcaption></figcaption></figure>

## Walk Test

After DBRA-2 is successfully learned in, place the Control Panel in the walk test mode, then press the button on DBRA-2 to confirm that this location is within signal range of the Control Panel. Refer to Control Panel manual to complete Walk Test.

***

## Operation

* When the preset decibel level is reached and the sound persists for the configured duration, DBRA-2 will raise an alarm and flash its Red backlight.
* Pressing the Test Button once will trigger an alarm manually.

***

## Installation Guidelines

* To ensure decibels recognition accuracy, please avoid installing DBRA-2 in a large or noisy room.
* The ideal environment for decibels recognition is silence or partial silence.
* The decibels recognition function has eight sensitivity levels. You may test with them and select the level that best suits your mounting location.

***

## Installation

After you conduct the Walk Test to confirm DBRA-2 is within signal range of the Control Panel, and the sensitivity and sound duration settings are confirmed to be appropriate, you can proceed with installation. There are two ways to install DBRA-2: Wall Mounting and Surface Deployment.

### Wall Mounting

Ensure that DBRA-2 is mounted at approximately chest height (around 130cm–150cm above the ground) where the button can be easily accessed and operated.

{% stepper %}
{% step %}
### Step

Drill a hole into the wall and insert the provided wall plug. Apply the screw into the wall plug, leaving the non-threaded part exposed for hanging the device.
{% endstep %}

{% step %}
### Step

Hook the device over the exposed non-threaded part of the screw. Then gently and firmly push it downwards to secure it in place.
{% endstep %}
{% endstepper %}

<figure><img src=".gitbook/assets/image (457).png" alt=""><figcaption></figcaption></figure>

### Surface Deployment

DBRA-2 comes with an anti-slip pad on its back. The device can also be placed on a flat surface without being installed at a fixed location.

<figure><img src=".gitbook/assets/image (458).png" alt=""><figcaption></figcaption></figure>
