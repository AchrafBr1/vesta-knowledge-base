# VESTA-349N

VCP-LTE-E-S F1 868

## Voice Emergency Call Point

<figure><img src=".gitbook/assets/image (10).png" alt=""><figcaption></figcaption></figure>



This device can be added to a panel via F1 and allows GSM calls to be made from Rules. It includes the ability to make phone calls by pressing the ‘HELP’ button

## SMS COMMAND TABLE



![](https://192-168-195-151.jpab.direct.quickconnect.to:5001/ns/dv/6jnMN/9fdc70f4c98930f7b8924b40c90de48146d501e2/_ZDhRzavSTwy_erRsG6kYSQ/image.png?SynoToken=msYiY6OS.sAp.\&tid=gfGWk2j9Q0WRwB8n4CRtvnpzS0Yh7upYD87OomxM4tVL9X3WS85hzJG6_sElpMdMpwCefNBDRq6-H7_b)



## QUICK GUIDE

{% stepper %}
{% step %}
Send SMS to VCP with phone number you want to call

RPT:PROG,1111,3,<mark style="color:orange;">TELEPHONE</mark>,3,0,0,4
{% endstep %}

{% step %}
Add to VESTA panel (Only VESTA-349N)

Put panel in learn mode and press help button in VESTA-349N
{% endstep %}
{% endstepper %}





### Device button and led indicator

<figure><img src=".gitbook/assets/image (236).png" alt=""><figcaption></figcaption></figure>

<figure><img src=".gitbook/assets/image (235).png" alt=""><figcaption></figcaption></figure>



***



{% hint style="info" %}


## **Manual for Learning and Removing RF Devices on VESTA-341N**&#x20;

### **Entering Learning Mode**

1. Press and hold the **Alarm Button** on VCPP for **8 seconds**.
2. At the **8th second**, the device will emit **one beep**.
3. Release the button immediately after the beep to enter **learning mode**.



<img src=".gitbook/assets/image (234).png" alt="" data-size="original">

***

### **Device Learning and Testing**

1. **Press the Button** on the RF device to transmit signals. _(Refer to the RF device manual for specific details.)_
2. **VCP will emit 2 beeps** when it successfully receives the signal from the RF device (bracelet/pendant), confirming that it has been learned.
3. **Repeat Steps 1-2** to learn additional devices.
4. **Verification:**
   * To ensure correct reception at all key locations, verify that the **hands-free unit emits a confirmation tone** when pressing the **bracelet/pendant button**.
5. Once all devices are learned, **press the Alarm Button** on **VCP once** to exit learning mode.
   * The device will emit **2 beeps** to confirm exit.

***

### **Device Removal**

1. While in **learning mode**, press the **Alarm Button twice quickly**.
2. **VCP will emit 2 beeps**, indicating that **ALL RF devices** have been removed.
3. The device will automatically **exit learning mode** after removal.
{% endhint %}















