# VESTA 033N

![](<.gitbook/assets/0 (43).png>)

**Tag Reader (TG-15N F1)**

13-Mar-2017

![](<.gitbook/assets/1 (46).png>)

* _**Identifying the parts:**_
  *
    *
      1. **Green LED Red LED Orange LED Arm Button**
      2. **Tag Reader Sensor (for tag)**
      3. **Battery Compartment**
      4. **Learn Button**
      5. **Tamper**
* _**LED Indicator:**_
  * **Green LED:**
    * Light on for 3 seconds: When Control Panel is under Disarm Mode.
    * Flashes for 5 seconds: When the Arm Button is pressed (_Put the tag near the Tag Reader Sensor to Arm the system during this 5 seconds_).
  * **Red LED:**
    * Light on for 3 seconds: When the Control Panel is under Arm Mode.
    * Flashes for 3 seconds: When system is disarmed after alarming.
  * **Orange LED:**
    * Light on for 3 seconds: When Arm Button is pressed under Tag Reader/Control Panel fault

conditions: low battery, tamper fault etc.

*
  *
    * Flashes for 3 seconds: Learning failed or no response from the Control Panel.
* _**Power:**_
  * The Tag Reader is powered by two AA 1.5V L91 Lithium batteries as power source.
  * The Tag Reader can also detect the battery status. If the battery voltage is low during operation, the low battery signal will be sent to the Control Panel along with regular signal transmissions for the Control Panel to display the status accordingly.
  * If battery voltage is exhausted, both Green and Red LED will flash every 4 seconds and the Tag Reader will stop all operation.
* _**Power Saving Feature:**_
  * When idle, Tag Reader is in “**power saving**” mode and uses no power. It will activate and “**wake-up**” for 10 seconds when put the tag on the Tag Reader sensor.
  * After 10 seconds of inactivity, the power goes off and it returns to power saving mode.
* _**Tamper Protection:**_
  * Tag Reader is protected against any attempt to open the lid or to detach Tag Reader from its mounting surface (see **Mounting Tag Reader** for details).
  * When Tag Reader’s tamper is triggered, a tamper signal will be sent to the Control Panel for the Control Panel to display the status. Once the signal is sent, Tag Reader returns to power saving mode.

![](<.gitbook/assets/2 (29).jpeg>) ![](<.gitbook/assets/3 (49).png>)

1

* _**Getting Started:**_

**Step 1.** Remove the cover by losing the fixing screw.

**Step 2.** Power on the Tag Reader.

**Step 3.** **Adding Tag Reader into the Control Panel:**

1. Put Control Panel into Learning Mode (Refer to the operation manual of your Control Panel for details), then Remove the Tag Reader’s cover.
2. Press the Learn Button, the Tag Reader will transmit a learning signal to the Control Panel with a beep sound, if the Control Panel successfully receives the learning signal, Tag Reader will emit 3 beeps and its info will display in the Control Panel.
3. Press the Add button, the Control Panel will send acknowledgement back to Tag Reader and it will emit 1 beep to indicate successful learning.
4. If Tag Reader fails to transmit signal or receive acknowledgement from the Control Panel, the Orange LED will flash for 3 seconds times. Please press the Learn Button again to learn into the Control Panel.

**Step 4.** Navigate the Control Panel into “**Walk Test**” mode. Hold the Tag Reader in the desired location, press the learn button on the Tag Reader with 1 beep sound, to confirm this location is within signal range of the Control Panel, if success the Tag Reader will emit 3 beeps.

**Step 5.** When you are satisfied that the Tag Reader works in the chosen location, you can proceed to mount the Tag Reader by following the below steps.

* _**Mounting Tag Reader:**_

The Tag Reader consists of a two-part design made up of a cover and base. The cover contains all the electronics and the base provides a mean of fixing. The tamper switch protects the enclosure from being opened or being removed from the mounting surface.

The base has three knockouts for mounting purpose. To mount the Tag Reader:

**Mounting Holes:**

![](<.gitbook/assets/4 (26).jpeg>)

I. Remove the fixing screw at the bottom II. Remove the cover assembly

1. Break through the appropriate knockouts on the mounting holes.

IV. Use the Mounting holes of the base as a template, drill holes in the surface.

1. Insert the wall plugs if fixing into plaster or brick VI. Screw the base into the wall plugs

VII. Fix the cover with the screw and clips to the base

![](<.gitbook/assets/5 (45).png>)

_**\<NOTE>**_

*
  * If the mounted Tag Reader is forcedly removed, the Breakaway Area will be left on the wall separated from the Tag Reader, the tamper will then be triggered (only available by using the **Mounting Holes** method).
* _**Tag Learning/Removing**_

After first power on the Tag Reader, please wait for 10 seconds for Tag Reader to enable tag sensor function.

Please start _**Learning**_ the tag into the Control Panel, follow the steps as below:

**Step 1.** Press and hold the Learn Button for 5 seconds, release it when Green LED light on (30 seconds) with 1 beep sound.

**Step 2.** Place the tag near the Tag Reader Sensor to record a tag ID into the Tag Reader:

1. If a New tag ID is successfully learned in to the Tag Reader, the Green LED will flash twice with 2 beeps.

2

1. If an Existing tag ID has already been learnt in, the Green LED will flash once with 1 beep.
2. If tag ID is full (a maximum of 60 tags can be learned in), the Green LED will flash 4 times with 4 beeps to indicate.

![](<.gitbook/assets/6 (33).png>)

_**\<NOTE>**_

* If Tag Reader has not yet learned into the Control Panel, placing the tag near the Tag Reader Sensor will emit 2 beeps indicating no transmission has been sent.

**Step 3.** To exit Tag Learning Mode:

1. Press the Learn Button once, the Tag Reader will emit 2 beeps, and the Green LED will light off.
2. The Tag Reader will automatically exit Tag Learning Mode after 30 seconds, the Tag Reader will emit 2 beeps and Green LED will light off. Any tag detected during this period will recount 30 seconds.

To start _**Removing**_ the tag from the Tag Reader, follow the steps as below:

(_Please make sure you exit Learning Mode already_)

**Step 1.** Press and hold the Learn Button for 8 seconds, release it when Red LED light on (30 seconds) with 1 beep sound.

**Step 2.** Place the tag near the Tag Reader Sensor to remove the tag ID from the Tag Reader:

1. If the tag is removed, the Red LED will flash twice with 2 beeps emitted from the Tag Reader.
2. If an unrecorded tag ID is placed near the Tag Reader’s Sensor, the Red LED will also flash twice and with two beeps emitted from the Tag Reader.

**Step 3.** To exit Tag Removing Mode:

*
  1. Press the Learn Button once, the Tag Reader will emit 2 beeps, and the Red LED will light off.
  2. The Tag Reader will automatically exit Tag Removing Mode after 30 seconds, the Tag Reader will emit 2 beeps and Red LED will light off. Any tag detected during this period will recount 30 seconds.
* _**Operation:**_

After you complete learning the tag into the Tag Reader, you can now switch the system to Arm, Disarm Mode:

1. **Disarm Mode Control:** Apply tag near Tag Reader Sensor, the Control Panel will automatically switch to Disarm Mode, the Tag Reader will emit 2 beeps.
2. **Arm Mode Control:** Press the Arm Button once, the Green LED will quickly flash for 5 seconds, apply the tag near Tag Reader Sensor during this 5 seconds, the Tag Reader will emit 1 long beep for 3 seconds to indicate arming success.
3. **LED flash:** If system is Armed, Red LED will light on for 3 seconds. When Disarmed, Green LED will light on for 3 seconds.
4. **Tamper:** When Tamper is triggered, the Tag Reader will transmit tamper alarm signal to the Control Panel immediately and returns to power saving mode.

* _**Changing Battery:**_

**Step 1:** Remove the Tag Reader cover by losing the fixing screw.

**Step 2:** Remove the old batteries.

**Step 3:** Press Learn button to fully discharge.

**Step 4:** Insert new batteries. The Tag Reader will emit one beep to indicate.

**Step 5.** Press Learn button again to send low battery restore to Control Panel.

**Step 6:** Fix the cover with the screw and mount back to its location.

* _**Factory Default (Reset Learning Record):**_

**Step 1:** Remove the cover by losing the fixing screw.

**Step 2:** Remove battery, press and hold the Learn Button and insert the batteries to power back on.

**Step 3:** The Tag Reader will be removed from the Control Panel until it emits 3 beeps.

3
