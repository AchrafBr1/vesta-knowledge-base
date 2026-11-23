---
description: >-
  To ensure proper operation of OPTEX barrier connected to a wireless
  transmitter, the barrier GND must be connected to the transmitter GND
---

# Quick Guide - Correct connection of OPTEX barriers with a wireless transmitter

### Connection procedure

#### 1. Identify the 2-pin cable

The barrier transmitter has a **2-pin cable with a blue wire and a green wire**.

This cable is normally used for **tamper** or **battery low** reporting.

If you do **not** use that function, use this cable for the barrier **GND** connection.

***

#### 2. Connect the cable to the BCU-5 receiver

Connect the 2-pin cable to the **power connector on the BCU-5 receiver**.

* **Blue wire → GND**
* **Green wire → Not used**



<figure><img src="../.gitbook/assets/OPTEX 2.png" alt="" width="563"><figcaption></figcaption></figure>



***

#### 3. Connect the GND to the wireless transmitter

Connect the **blue wire** to the **GND terminal** of the wireless transmitter.

Connect it together with the **yellow ALARM NC wire**.

***

### Wiring diagram

<figure><img src="../.gitbook/assets/OPTEX FIX (1).png" alt=""><figcaption></figcaption></figure>

***

### Result

The barrier and the wireless transmitter now share the same **GND**.

This ensures correct and reliable operation.
