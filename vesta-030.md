# VESTA 030

**Repeater (RP-29)**

The Repeater is designed to increase the effectiveness and versatility of the alarm system. It is a device that makes your system more powerful by increasing the maximum possible distance between the Main Unit (Control Panel) and the Devices.

* **Identifying the Parts**

![C:\Documents and Settings\C0874.CLIMAX-TECH\桌面\done\to be completed\manual pictures\RP-23 20140415.jpg](<.gitbook/assets/0 (14).jpeg>)

1. **Power LED (Green)**

**On** – Powered by a Power Adapter or Rechargeable Battery

**Flash** – Rechargeable Battery low on power

1. **Mode LED (Yellow)**

**On** – The Repeater is in Learning Mode (Panel) or Clear Mode

**Flash** (1 flash every second) – The Repeater is in Walk Test Mode

**Slow Flash** (1 flash every 2 seconds) – The Repeater is in Learning Mode (Device)

1. **Transmission: Receive LED (Blue)**

The Blue LED lights up when the Repeater receives a signal transmission

1. **Transmission: Transmit LED (Red)**

The Red LED lights up when the Repeater transmits a signal.

1. **Functional Switch Block**
2. **Test Button**
3. **Battery Switch**
4. **Removable Cover**
5. **Tamper Switch**
6. **Mounting Hole**
7. **DC power jack**
8. **Mounting Bracket**

* **Power Supply**

A Power Adapter is required to connect to a wall power outlet. Be sure only to use an adapter with the appropriate AC voltage rating to prevent component damage. A DC 12V 1A output Power Adapter is generally used to power the Repeater.

**Power Adapter Application:**

To connect the Power Adapter:

1. Locate the Power Adapter and plug into the DC power jack.
2. Plug the Power Adapter to a wall power outlet.
3. The Repeater will sound a Long beep and the Green LED will light up.

**AC Failure/AC Restore:**

The Repeater will send an AC Failure signal to the Control Panel when the Power Adapter is unplugged for 30-60 seconds. When the Power Adapter is plugged in again for 30-60 seconds, the Repeater will send an AC Restore signal to the Control Panel.

**Rechargeable Battery:**

In addition to the adapter, there is a rechargeable battery inside the Repeater, which serves as a back-up power in case of a power failure.

When the Power Adapter is plugged into the DC power jack, slide the Battery Switch to the ON position so the Power Adapter supplies power to the Repeater and at the same time recharges the battery. It takes approximately 72 hours to fully charge the battery.

When the Power Adapter is unplugged, the Repeater will be powered by the rechargeable battery.

The Repeater can detect the battery voltage. When the battery voltage is low, the Green LED will flash to indicate low battery status.

* **Functional Switch Block**

![C:\Documents and Settings\C0874.CLIMAX-TECH\桌面\done\to be completed\manual pictures\RP-23 switch block.jpg](<.gitbook/assets/1 (13).jpeg>)The Functional Switch Block determines which Mode the Repeater is in. A switch in the up position indicates the (**ON**) Mode. Likewise, a switch in the down position indicates the (**OFF**) Mode.

|              | Function                 | ON                     | OFF                   |
| ------------ | ------------------------ | ---------------------- | --------------------- |
| DIP Switch 1 | Learn Device             | Learning mode (Device) | Normal Mode           |
| DIP Switch 2 | Range or Walk Test       | Walk Test Mode         | Normal Mode           |
| DIP Switch 3 | Factory Reset            | Clear Mode             | Normal Mode           |
| DIP Switch 4 | Learn into Control Panel | Learning mode (Panel)  | Normal Mode           |
| DIP Switch 6 | One-way/Two-way Setting  | Two-way                | One-way               |
| DIP Switch 8 | Tamper Function          | Disable                | Normal Mode (Enabled) |

DIP Switches 5 and 7 are reserved.

\<Note>

* Please change DIP Switch 1-4 setting when the Repeater is powered, because change for DIP Switch 1-4 is only valid when the Repeater is powered. For example, DIP Switch 3 is slid to the On position when the Repeater is turned off. When the Repeater is turned on, it will NOT enter Clear Mode. However, if the DIP Switch 3 is slid to the Off position first, followed by sliding to the On position when the Repeater is on, the Repeater will enter Clear Mode.
* Please set the DIP Switch 6 position for One-way/Two-way device when the Repeater is off. After setting is complete, please power on the repeater and learn/re-learn it into the Panel for the setting to take effect.
* For DIP Switch 8 setting, please power off the repeater before changing DIP Switch setting. The new Dip Switch 8 settings will take effect when the repeater is re-powered on.
* **Supervisory Signal**
* After being learnt in to the Control Panel, the Repeater will automatically transmit Supervisory Signals every 30 to 50 minutes when working as a one-way device. If working as a two-way device, the Repeater will automatically transmit Supervisory Signals every 90 to 120 minutes.
* If the Control Panel has not received the signal from the Repeater for a preset period of time, the Control Panel will indicate it on its display to show that the Repeater is experiencing an out-of-signal problem.
* **One-way/Two-way setting**
* The Repeater can operate as either a one-way device or two-way device. When programmed as a two-way device, the Repeater can receive acknowledgement from the Control Panel to ensure successful transmission.
* The repeater will work as a **two-way** device when DIP Switch 6 is slid to the **ON** position. It will work as a **one-way** device when DIP Switch 6 is slid to the **OFF** position.
* Please set the DIP Switch 6 position for One-way/Two-way device when the Repeater is off. After setting is complete, please power on the repeater and learn/re-learn it into the Panel for the setting to take effect.
* **Learn into Control Panel**

1. To learn the Repeater into the Control Panel, slide DIP Switch 4 to the On position under Normal Mode. The Repeater will emit 1 long beep and the Yellow LED will turn on.
2. Put the Control Panel into Learning Mode (please refer to the Control Panel manual).
3. Press the Test button. The Repeater will transmit a Test Code to the Control Panel as the Red LED lights up and the Repeater emits 1 beep.
4. If the Repeater receives an acknowledge signal from the Control Panel within 60 seconds, Learning is successful. The Blue LED will light up for 1 second as the Repeater emits 1 long beep.

If the Repeater fails to receive an acknowledge signal from the Control Panel within 60 seconds, learning has failed and is indicated by the Yellow LED flashing 3 times. Please repeat step 3-4 again.

1. Slide DIP Switch 4 to the Off position. The Repeater will emit 1 long beep and the Yellow LED will turn off as the Repeater returns to Normal Mode.

* **Learning Repeater into Repeater**

If Repeater A is learning into Repeater B:

1. Putting Repeater B into learning mode: Under Normal Mode, slide DIP Switch 1 of Repeater B to the On position. Repeater B will emit 1 long beep and the Yellow LED will flash slowly (1 flash every 2 seconds).
2. Press the Test Button on Repeater A to send a learn code. Repeater A will emit 1 beep and the Red LED will turn on.

If Repeater B receives the learn code from Repeater A, it will emit 1 long beep and the Blue LED will light up for 1 second to indicate successful learning.

If Repeater B receives the learn code from Repeater A and Repeater A was already learnt, Repeater B will emit 2 beeps and the Blue LED will light up for 1 second.

\<Note>

* Please do not cross-learn the Repeaters, e.g. Learning Repeater A into Repeater B and learning Repeater B into Repeater A.
* All repeaters will have to be learnt into the Control Panel.

1. When the learning is complete, slide DIP Switch 1 of Repeater B to the Off position. Repeater B will emit 1 long beep and the Yellow LED will turn off as Repeater B returns to Normal Mode.

* **Learning Device into Repeater**

1. Under Normal Mode, slide DIP Switch 1 to the On position. The Repeater will emit 1 long beep and the Yellow LED will flash slowly (1 flash every 2 seconds).
2. Please refer to the device manuals on how to send learn code from the devices.

**For PIR Camera, please press the test button once to send a learn code to the Repeater.**

If the Repeater receives a learn code from a new device, it will emit 1 long beep and the Blue LED will light up for 1 second to indicate successful learning.

If the Repeater receives a learn code from a device already learnt into the Repeater, it will emit 2 beeps and the Blue LED will light up for 1 second.

**A maximum of 60 devices (including repeaters) can be learnt into the Repeater, and up to 8 PIR cameras are supported. If the user attempts to learn in a 61st device, the Repeater will emit 4 beeps.**

\<Note>

* If multiple repeaters are used, please only learn devices into the Repeater(s) closest to the operation areas of the devices.
* All the devices learnt into the Repeater must also be learnt into the Control Panel.

1. When the learning is complete, slide DIP Switch 1 to the Off position. The Repeater will emit 1 long beep, the Yellow LED will turn off as the Repeater returns to Normal Mode.

* **Walk Test Mode**

Learnt-in Control Panel or learnt-in devices can check for its signal range with the Repeater if the Repeater enters Walk Test Mode.

1. Under Normal Mode, slide DIP Switch 2 to the On position. The Repeater will emit 1 long beep and the Yellow LED will flash (1 flash every second).
2. When the Repeater receives signals from the Control Panel or the learnt-in devices, it will emit a long beep and the Blue LED will light up for 1 second. The signal is then retransmitted as the Red LED lights up for 1 second.
3. To exit Walk Test Mode, slide DIP Switch 2 to the Off position. The Repeater will emit 1 long beep and the Yellow LED will turn off.

* **Clear Mode (Factory Reset)**

Clear the previously programmed memory and reset the Repeater to Factory Default

1. Under Normal Mode, slide DIP Switch 3 to the On position. The Repeater will emit 1 long beep and the Yellow LED will light up.
2. Press and hold the Test button for 5 seconds. The Repeater will emit 1 long beep to indicate all learnt-in devices and Control Panel are cleared from the Repeater.
3. To exit Clear Mode, slide DIP Switch 3 to the Off position. The Repeater will emit 1 long beep and the Yellow LED will turn off.

\<Note>

* Whenever the Repeater is removed from the Control Panel, it should be put to factory reset as well to clear its Control Panel memory.
* **Operation**

If the Repeater receives a signal from the Control Panel (e.g. a command), the signal is retransmitted to the corresponding device(s) from the Repeater. The transmission LEDs will light up accordingly.

If the Repeater receives signal from a device (e.g. an alarm signal), the signal is retransmitted to the Control Panel from the Repeater. The transmission LEDs will light up accordingly.

* **How to mount the Repeater**

The Repeater can be placed on the table, mounted on the wall or wherever desired. Follow the steps below to mount the Repeater:

1. Using the holes of the Mounting Bracket as a template, drill holes into the mounting surface.
2. Insert the wall plugs if fixing into plaster or brick. Screw the Mounting Bracket to the wall.

![](<.gitbook/assets/2 (28).png>)

1. Hook the Repeater onto the Wall Mounting Bracket (with the Mounting Holes of the Repeater).

![](<.gitbook/assets/3 (26).png>)

1. Hold the Repeater and gently push it downwards as shown below.

![](<.gitbook/assets/4 (26).png>)

* **Tamper Protection**
* The Tamper Switch is in normal operating position (Tamper Closed) when the Repeater is hooked onto the Wall Mounting Bracket. Tamper violation happens when the Repeater is removed from the hook where Tamper Switch is released (Tamper Opened).
* The tamper protection function can be **disabled** when DIP Switch 8 is slid to the ON position. It is **enabled** when DIP Switch 8 is slid to the OFF position. Change to Dip Switch 8 setting will become valid when the repeater is re-powered on.
* **Recommendations**

It is strongly suggested to keep a distance between each repeater and/or Main Control Panel to avoid cross signaling.

If a particular device is within an acceptable range for Control Panel to receive its transmission signal, it is strongly recommended to learn the device into the Control Panel directly instead of into the Repeater.

When cascading repeaters to form a transmission relay, it is strongly recommended to link not more than 2 layers of repeaters.

\<Note>

* For devices that are directly controlled by the Panel to turn on/turn off, e.g. power switches, power meter switches, valve controllers, Roller Shutter Controls, or Input and Output Switches, please link only one layer of repeater(s).
* For keypad, it is also recommended to link only one layer of repeater(s).

**Multiple Repeaters**

If multiple repeaters are used, please follow the guidelines below for the optimum performance:

1. When linking repeaters to form a transmission replay, it is recommended to link not more than two layers of repeaters.

From the example below (Device to B to A to Control Panel), Repeater A, Repeater B, and the Device all need to be learned into the Control Panel.

The Device needs to be learned into its closest repeater (Repeated B). Repeater B needs to be learned into Repeater A. (Do not learn Repeater A into Repeater B.)

Example:

![C:\Documents and Settings\C0874.CLIMAX-TECH\桌面\done\to be completed\manual pictures\RP coverage device.jpg](<.gitbook/assets/5 (10).jpeg>)

1. If a device is located between the RF coverage of multiple repeaters and the Control Panel:

Example 1:

![C:\Documents and Settings\C0874.CLIMAX-TECH\桌面\done\to be completed\manual pictures\RP coverage eg1.jpg](<.gitbook/assets/6 (14).jpeg>)

From the displayed diagram, the device is located between the RF coverage areas of Repeater B and C. Users can choose to learn the device into Repeater B only, learn into Repeater C only, or learn into both Repeaters B and C.

It is **recommended** to learn the device into Repeater B only (and not to Repeater C) to reduce signal traffic.

\<Note>

* For the above system, Repeater C is also learnt into Repeater A or B or both so the signals from Repeater C can be relayed to the Control Panel through Repeater A or B, or either.

Example 2:

![C:\Documents and Settings\C0874.CLIMAX-TECH\桌面\done\to be completed\manual pictures\RP coverage eg2.jpg](<.gitbook/assets/7 (13).jpeg>)

From the displayed diagram, the device is located between the RF coverage areas of Repeater A, B and C. Users can choose to learn the device into Repeater A only, learn into Repeater B only, learn into Repeater C only, or learn into Repeaters A, B and C.

It is **recommended** to learn the device into Repeater A only or Repeater B only (and not to Repeater C) to reduce signal traffic.

\<Note>

* For the above system, Repeater C is also learnt into Repeater A or B or both so the signals from Repeater C can be relayed to the Control Panel through Repeater A or B, or either.

1. Typically, most devices stay in the same RF coverage area. For the exceptions such as a Remote Controller, please learn the device into all Repeaters (and Control Panel) of the system.
