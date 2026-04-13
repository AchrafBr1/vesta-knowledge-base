# VESTA-156

Configuration manual of the VESTA-156



<figure><img src=".gitbook/assets/0 (154).jpeg" alt=""><figcaption></figcaption></figure>

## FIRST OF ALL:

### • Connect the battery of the I/O module

![](<.gitbook/assets/2 (101).jpeg>)



{% hint style="danger" %}
NOTE:

### Connect the smoke generator in the terminals“smoke” only AFTER made the tests of working.
{% endhint %}



## Learning I/O module on the panel

1. Activate the learning function on the panel (for further info, refer to the panel manual)

![Add device](<.gitbook/assets/3 (151).png>)

![Select Others](<.gitbook/assets/4 (141).png>)

2. Press the button on the I/O module installed inside the VESTA-156

<figure><img src=".gitbook/assets/5 (69).jpeg" alt=""><figcaption></figcaption></figure>

3. Select the detected device and press OK

![](<.gitbook/assets/6 (117).png>)



4. Assign the appropriate area to the output device (DO), and choose the zone number and the name of the device: SMOKE ACTIVATION

![](<.gitbook/assets/7 (105).png>)

{% hint style="warning" %}
Note: The output module (DO) must be set as. "Separate devices"
{% endhint %}



5. Assign at the (DI) the same area to the output device (DO) and choose the zone number and the device name: SMOKE TAMPER.

![](<.gitbook/assets/8 (105).png>)

6. Set the input module as a 24H Burglar Alarm

## Configuration activation rule

In the menu "automation rule" create a new rule as indicated below:

![](<.gitbook/assets/9 (104).png>)

## Double coincidence configuration

In the device settings, set at least 2 devices with the "Cross zone" attribute to activate the smoke generator ONLY in the event of the activation of both devices in a programmable time and thus avoid improper activations.

Example of the Cross Zone programming:

![PIRCAM zone ](<.gitbook/assets/10 (160).png>)

![Magnetic Contac zone](<.gitbook/assets/11 (100).png>)



In the menu "Security“, set the timer for the cross zones to 1 minute or more (time within which the 2 zones must be activated to trigger the smoke generator)

![](<.gitbook/assets/12 (95).png>)
