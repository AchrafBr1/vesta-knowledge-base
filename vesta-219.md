# VESTA-219

HR-8-F1

## Hybrid Receiver

<figure><img src=".gitbook/assets/image (577).png" alt=""><figcaption></figcaption></figure>





## IDENTIFYING THE PARTS

<figure><img src=".gitbook/assets/image (578).png" alt=""><figcaption><p>Front View</p></figcaption></figure>

<figure><img src=".gitbook/assets/image (579).png" alt=""><figcaption><p>Side View</p></figcaption></figure>

* Pin 1 & 2 provide constant DC 12V input
  * Pin 1 is (+) polarity
  * Pin 2 is (–) polarity, Ground
* Pin 3 provides DC 12V tamper output
  * Connect a wired device; it will activate when HR receives a tamper signal from learned sensors.
  * **SW3** must be set to **ON** to include tamper as Fault output.
* Pin 4 & 5 provide an Alarm relay output
  * Connect a wired device; it will activate when HR receives an alarm signal from learned sensors.
  * SW4 selects Alarm relay behavior: Normally Closed (N.C.) or Normally Open (N.O.). See SW4 section.
* Pin 6 & 7 provide a Fault relay output
  * Connect a wired device; it will activate when HR receives a fault signal from learned sensors.
  * Fault relay is always N.C. (Normally Closed). Fault signals include Low Battery and Supervision Failure (>4 hrs).
  * SW2 must be ON to enable Supervision.

Notes:

* Tamper types include Tamper Open. (SW3 = ON to include tamper as Fault output.)

### FUNCTION SWITCH BLOCK

Open the protective cover to access a block of 6 DIP switches (marked 1–6 left to right). DIP Switch Top position = ON. Bottom = OFF.

| Switch | Function                            | ON              | OFF              |
| ------ | ----------------------------------- | --------------- | ---------------- |
| SW1    | Learning Device                     | Learning Mode   | Normal Operation |
| SW2    | Supervision                         | Enable          | Disable          |
| SW3    | Tamper Fault Output                 | Tamper included | Tamper excluded  |
| SW4    | Alarm Relay Operation               | Normal Close    | Normal Open      |
| SW5    | Relay Output Type                   | Latch           | Pulse            |
| SW6    | Test mode / Clear LED Fault Display | In Test Mode    | Normal Mode      |

Image (switch block):

<figure><img src=".gitbook/assets/image (580).png" alt=""><figcaption></figcaption></figure>

#### SW1 — Learning Mode

* When SW1 = ON, LED flashes every second (learning mode).
* If an RF signal is received from a device already learned, HR emits one long beep. See "Learn-in device" section.

#### SW2 — Supervision

* Enable/disable supervision.
* If enabled (ON), lack of supervision signal from a supervised sensor (IR/SD/DC/WS) for >4 hours triggers Fault relay (Pin 6 & 7).

#### SW3 — Include Tamper as Fault

* SW3 = ON:
  * PIN 3 (DC 12V tamper output): exports 12V when tamper is received; returns 0V when restored.
  * PIN 6 & 7 (fault relay): activate on tamper according to SW5 (Latch/Pulse).
* SW3 = OFF:
  * PIN 3 always 0V on tamper.
  * PIN 6 & 7 will NOT activate on tamper.

#### SW4 — Alarm Relay NO / NC

* SW4 = ON: Alarm relay in Normal Close (loop opens when alarm occurs).
* SW4 = OFF: Alarm relay in Normal Open (loop closes when alarm occurs).
* Fault relay is always N.C. and cannot be changed.

#### SW5 — Relay Output Type

* LATCH — alarm/fault relay remains activated until condition is restored.
* PULSE — relay gives a 3-second pulse on activation.
  * Note: If alarm signal comes from an IR sensor, the relay activates as Pulse only.

Alarm & Fault examples (summary)

* Alarm outputs (Pin 4 & 5): Door Contact open, Smoke Detector trigger, Panic/WTR/RC buttons, Water detected — activate; restored when conditions clear.
* Fault outputs (Pin 6 & 7): Low battery, Supervision Failure (>4 hrs), Tamper (if SW3=ON) — activate; restored when conditions clear.

#### SW6 — Test Mode / Clear LED Fault Display

* SW6 = ON: enter Test Mode. LED flashes every 2 seconds. HR beeps 2s on each sensor signal.
* SW6 can also clear LED flash caused by fault: toggle ON then OFF to stop LED flashing. (This clears LED indicator only, not the underlying fault.)

***

## LEARN-IN DEVICES

The HR can learn up to 10 devices: PIR (IR), Smoke Detector (SD), Door Contact (DC), Water Sensor (WS), Panic Button (PB), Wrist Transmitter (WTR), Remote Control (RC).

Use the stepper below to learn devices:

{% stepper %}
{% step %}
### Step 1 — Power up

Supply 12V DC to PIN 1 & 2.

* LED will turn steady on, then HR will emit a 1-second beep.
* LED stays on in normal mode.
{% endstep %}

{% step %}
### Step 2 — Enter Learn-in Mode

Use a sharp object to slide SW1 to ON (top).

* LED flashes rapidly once per second.
{% endstep %}

{% step %}
### Step 3 — Send learn/test from the device

Press the device's test/learn button.

* HR emits a short beep after the sensor is learned-in.
* A long beep indicates the device was previously learned-in.
{% endstep %}

{% step %}
### Step 4 — Repeat

Repeat Step 3 to learn additional devices (one device at a time).
{% endstep %}

{% step %}
### Step 5 — Exit Learn-in Mode

Slide SW1 to OFF (bottom) using a sharp object.

* LED stays on (normal operation).
* If 10 devices are learned, HR will warn until SW1 is switched OFF.
* Only one device can be learned at a time to prevent faulty signaling.
{% endstep %}
{% endstepper %}

***

## TEST MODE

Use Test Mode to verify device placement and reception.

{% stepper %}
{% step %}
### Enter Test Mode

Slide SW6 to ON. LED flashes every 2 seconds.
{% endstep %}

{% step %}
### Test a device

Hold the device in the desired location and press its test/learn button.

* HR emits a 2-second beep on receiving the sensor signal.
{% endstep %}

{% step %}
### Repeat

Repeat for other locations/devices as needed.
{% endstep %}

{% step %}
### Exit Test Mode

Slide SW6 to OFF to return to normal operation.
{% endstep %}
{% endstepper %}

***

## NORMAL OPERATION

* LED steady ON indicates normal operation.
* When an alarm signal is received, Alarm relay (Pin 4 & 5) activates according to SW5 (Pulse or Latch).
* When a fault signal is received, Fault relay (Pin 6 & 7) activates according to SW5.
* Supervised sensors (PIR/SD/DC/WS) send supervision signals every 20–60 minutes (random). If missing >4 hrs and SW2 = ON, HR activates Fault relay.
* Tamper on PIR or DC (if SW3 = ON) causes PIN 3 to export 12V and Fault relay activation (Pin 6 & 7) per SW5.
* LED fault flash patterns:
  * Low Battery: 1 quick flash
  * Tamper: 2 quick flashes
  * Supervision: 3 quick flashes

Notes:

* To display multiple statuses, LED cycles codes at 1-second intervals.
* To clear LED fault display: Slide SW6 to ON, then back to OFF (this clears LED only, not the underlying fault).

When HR receives a test code from IR/SD/DC/WS, it beeps and flashes LED once.

***

## CLEAR DEVICE (Clear All Learned Devices)

This erases all learned sensors. After clearing, all devices must be re-learned.

{% stepper %}
{% step %}
### Step 1 — Remove power

Disconnect HR power supply.
{% endstep %}

{% step %}
### Step 2 — Set all switches to ON

Slide all DIP switches to ON (top).
{% endstep %}

{% step %}
### Step 3 — Reconnect power

Reconnect HR power.
{% endstep %}

{% step %}
### Step 4 — Confirm LED

LED will turn steady on.
{% endstep %}

{% step %}
### Step 5 — Restore switches to OFF

Slide all switches back to OFF (bottom). HR returns to Normal Operation Mode with 1-second beep and LED stays on — clearance successful.
{% endstep %}
{% endstepper %}

***

Hints and notes:

{% hint style="info" %}
* SW2 must be ON to enable Supervision.
* SW3 must be ON to include tamper as a Fault output.
* SW6 toggled ON→OFF clears LED flash but does not clear the underlying fault condition.
{% endhint %}

If you want any section expanded into an FAQ (expandable blocks), or need the wiring diagram or relay pinouts reformatted as cards or a table for quick reference, tell me which parts you want changed.
