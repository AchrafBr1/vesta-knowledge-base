# VESTA-071

<figure><img src=".gitbook/assets/image (1313).png" alt=""><figcaption></figcaption></figure>

## MX Control Panel – Enabling Cloud Services

By default, MX control panels are delivered with cloud services disabled. To enable cloud connectivity, follow the steps below.

### Step 1 – Update the Panel Firmware

Upgrade the control panel to the following firmware version:

**MX\_demes\_adc\_4gQT\_1.1.95.bin**

The firmware can be updated through the panel's local web interface:

1. Access the local web interface.
2. Navigate to **Update**.
3. Upload the firmware binary file (**MX\_demes\_adc\_4gQT\_1.1.95.bin or higher**).

{% file src=".gitbook/assets/MX_demes_adc_4gQT_1.1.95 (2).bin" %}

### Step 2 – Perform a Factory Reset

After the firmware update, a factory reset must be performed to enable cloud services.

Once the factory reset is completed, the panel will automatically negotiate with the cloud/XMPP server and connect online. From that point onwards, the panel can be managed using the **MediAlert App** or the [**MediAlert Portal**.](https://portal.vestasecurity.eu/medalert/)

<figure><img src=".gitbook/assets/image (1314).png" alt=""><figcaption></figcaption></figure>

#### Factory Reset Procedure

**Step 1:** Unplug the power cord from the DC jack.

**Step 2:** Use a pen or screwdriver to slide the battery switch to the **OFF** position.

**Step 3:** While pressing both the **HELP** and **RESET** buttons, plug the power cord back into the DC jack. Continue holding both buttons until a long beep is heard, indicating that the factory reset has been successfully executed.

**Step 4:** Release both buttons.

**Step 5:** Slide the battery switch back to the **ON** position.

### Expected Result

After rebooting, the panel will automatically connect to the cloud platform and appear online. The device can then be enrolled and managed through the MediAlert mobile application or web portal.

<figure><img src=".gitbook/assets/image (1315).png" alt=""><figcaption></figcaption></figure>

1 Red Help Button

2 Red Backlight

3 Green Reset Button





{% file src=".gitbook/assets/MX Installation and Operation Guide_ 20180730 (1.0.1).docx" %}

