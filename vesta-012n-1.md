# Copy of VESTA 012N

**KPT-39N-BLE**

## **BLUETOOTH REMOTE KEYPAD**

KPT-39N-BLE is a Remote Keypad with Bluetooth feature and NFC reader. It is designed to have quick access control of the System Control Panel via User PIN Code, NFC label, or by approaching the keypad with the paired smartphone to disarm the system. The Keypad can send wireless signals to and receive wireless signals from the Control Panel.

The Remote Keypad can be mounted on a flat surface or wall with screws. It also has a tamper protection switch, which will be activated upon any unauthorized attempt to open the lid or to detachthe  keypad from the mounting surface.

## _**Parts Identification**_

![](<.gitbook/assets/3 (21).jpeg>)

1. Arm Key
2. Home Key
3. Disarm Key
4. Panic Alarm (if enabled)
   * Press both 1 and 3 to trigger the Panic Alarm
5. Fire Alarm (if enabled)
   * Press both 4 and 6 to trigger the Fire Alarm
6. Medical Alarm (if enabled)
   * Press both 7 and 9 to trigger the Medical alarm
7. Send Learning Code
   * Press ＊ then 7 Key (under Programming Mode)
   * Press both # and \* keys (under Normal Operation Mode)
8. \# Key
   * Press to check current system mode
9. \* Key
10. Fault LED (Orange LED)
11. Power LED (Green LED)
12. Detection Area for NFC Label
    * Put the NFC Label close to the detection area to access the alarm system
13. Tamper Switch
14. Mounting Holes
15. NFC Label

{% hint style="warning" %}
Note:

A short beep will sound along with a key pressing to indicate that the button pressed is valid.

4 continuous beeps will sound, indicating mistake, and the user should repeat the process again.
{% endhint %}

## _**LED Indicator**_

**Power LED (Green):**

* On for 5 seconds: after successful completion of a valid keystroke sequence.
* Flash for 5 seconds: low battery in Normal Operation Mode.
* If the Power LED turns off before a valid keystroke sequence is completed, the previous entered keys are ignored.

**Fault LED (Orange):**

* Disarm Key and Orange LED on along with 5 beeps: Alarm Memory (depends on Control Panel).
* Flash:

&#x20;                  -Flash only: No response is sent by the control panel within 10 seconds.

&#x20;                 \- Flash along with 2 beeps: Request for Home mode during Arm mode.

&#x20;                  -Flash along with 3 beeps: Request for Home or Arm Mode when fault condition exists.

&#x20;                  -Flash along with 4 beeps: PIN code was incorrect.

## _**General Operation**_

* Enter Programming Mode — Enter Keypad PIN code and then press ＊ key.
* Panic Alarm — Press **1** key + **3** key at the same time. (if the function is enabled)
* Fire Alarm — Press **4** key + **6** key at the same time. (if the function is enabled)
* Medical Alarm — Press **7** key + **9** key at the same time. (if the function is enabled)
* Check Control Panel Status — Normal Mode Press **#** key.
* Enable/Disable Entry & Exit Sound —Press **1** key + **2** key at the same time for 2 seconds. (The Keypad will emit one long beep to indicate the function is enabled and emit 2 short beeps to indicate the function is disabled.)

## _**Power**_

* Remote keypad uses one CR123 3V Lithium battery as its power source.
* Remote keypad can also detect the battery status. If the battery voltage is low, the Power LED will flash for 5 seconds during operation. The Low battery signal will be sent along with regular signal transmissions to the Control Panel for displaying the status accordingly.
* Before shipment, the battery is pre-installed by the factory.
* When changing the battery, press any key a couple of times to discharge before inserting a new battery.

## _**Power Saving Feature**_

* When idle, the remote keypad is in **Stand-by** mode and uses no power. It will activate and **wake-up** for 5 seconds when any key is pressed.
* After 5 seconds of key inactivity, the power goes off, and it returns t**o Stand-by** mode.

## _**Tamper Protection**_

* The keypad is protected against any attempt to open the lid or to detach the keypad from its mounting surface.
* Tamper protection is disabled when the keypad is in Programming Mode.

## _**Supervision Signal**_

* After installation, the Remote Keypad will automatically transmit Supervision Signals to the Control Panel at an interval of 30-50 minutes.
* If the Control Panel has not received the signal from the Remote Keypad for a preset period of time, the Control Panel will consider the Remote Keypad out of order and react according to the panel setting.

## _**Learning Keypad into Control Panel**_

Step 1. Put the Control Panel into **Learning Mode**. Please refer to the Control Panel manual.

Step 2. **Keypad Normal Mode**

&#x20;           Under Keypad Normal Mode, press and hold **＊** key and **#** key for 2 seconds to transmit learn code to Control Panel.

**Keypad Programming Mode**

Alternatively, you can enable Remote keypad to enter Programming Mode first. Enter Keypad PIN Code (Default: 0000)

&#x20;and then press **＊** key. The three![](<.gitbook/assets/13 (21).png>)![](<.gitbook/assets/14 (9).jpeg>) LEDs will turn on, along with a long beep. Press ＊ key and then **7** key to transmit learn code to Control Panel. Remote keypad will sound a long beep.

Step 3. Refer to the Control Panel manual to complete the learning process. If learning is successful, the Keypad will emit 3 beeps upon receiving the acknowledgement signal from the Control Panel. If the Keypad does not sound 3 beeps, please repeat Step 2 to transmit the learn code again.

Step 4. After the Remote keypad is learnt-in, put the Control Panel into **Walk Test** mode, hold the Remote keypad in the desired location, and send the learning code to the Control Panel to confirm this location is within the signal range of the Control Panel.

## _**Edit Keypad Operation Area**_

* Follow the instructions below to change the Keypad Area in the Control Panel
  1. Use the panel Edit Device function to change the Keypad area setting.
  2. Put the Control Panel into **Learning Mode**.
  3. Press and hold ＊ key and **#** key of keypad for 2 seconds to transmit learn code to Control Panel.

## _**Add Tag/Clear Tag Procedures**_

The Keypad is capable of transmitting NFC (Near Field Communication) tags to the Control Panel, and you can assign a User PIN Code and user name to each NFC tag on the Panel webpage. The NFC tags can then be used to control alarm system mode through the Keypad. The number of NFC tags and User PIN Codes are managed on the Control Panel webpage.

_**A) Add Tag:**_

When adding a new tag, the keypad must be in normal operation mode.

Step 1. Go to the PIN Code page on the Control Panel webpage, input a 4-digit or 6-digit user pin code and user name for the tag, and assign the user pin code to an Area.

<figure><img src=".gitbook/assets/1.png" alt=""><figcaption></figcaption></figure>

Step 2. After VESTA-012N is successfully learnt into the panel, press ![](<.gitbook/assets/18 (5).jpeg>) key on the keypad. Then, apply a new tag to the Keypad Tag sensor zone. The white backlight will turn on with 4 beeps to indicate this tag is new (not added to the system yet).

Step 3. Click the Load button on the PIN Code page as below. The corresponding tag number will be loaded. Click Submit to save the user code setting.

<figure><img src=".gitbook/assets/2.png" alt=""><figcaption></figcaption></figure>

Step 4. The tag has been added. You can use the tag to arm/home arm/disarm the system. When the Keypad is powered on by inserting batteries, the Orange LED will flash, and the white backlight will turn on. When the LED is off, wait 10 seconds for the keypad tag sensor to start functioning.

_**B) Clear Tag:**_

Step 1. Go to the PIN Code page on the Control Panel webpage.

Step 2. Manually delete the tag number and click Submit.

<figure><img src=".gitbook/assets/3.png" alt=""><figcaption></figcaption></figure>

Step 3. The tag is cleared.

## _**Programming Mode**_

**Enter Programming Mode:**

* Put the remote keypad in Programming Mode by entering the KP PIN code (default: **0000**), then press the **＊** key. The three LEDs will turn on, along with a long beep.

**Programming Mode Functions:**

* Press **＊** key and then **1** key —Enable BLE Pairing Mode.
  * Except pressing ＊ key and then 1 key under Programming Mode to enter the BLE Pairing Mode, the quick access to the BLE Pairing mode is pressing ＊ key and 0 key at the same time for 2 seconds on the Keypad in the Tamper Open state.
* Press **＊** key and then **2** key —Enable Dual-key (1+3) Panic Alarm function
* Press **＊** key and then **3** key — Enable Dual-key (4+6) Fire Alarm function
* Press **＊** key and then **4** key — Enable Dual-key (7+9) Medical Alarm function
* Press **＊** key and then **5** key — Disable all Dual Key function (Default)
* Press **＊** key and then **6** key — Edit Keypad Pin Code
* Press **＊** key then **7** key — Transmit learning signal. The remote keypad will sound a long beep.
* Press **＊** key and then **8** key — Enable Arm/ Home without User PIN Code function.

&#x20;                      _(Please refer to “**Arm/Home without Control Panel PIN Code**” for details)._

* Press **＊** key and then **9** key — Enable Arm/ Home with Control Panel User PIN Code function (Default).

&#x20;                     (_Please refer to “**Arm/Home with Control Panel PIN Code**” for details_).

**Exit Programming Mode:**

* Press the Disarm key **twice** to leave Programming mode. Alternatively, the remote keypad will automatically exit Programming Mode after 5 minutes of inactivity and return to Stand-by mode. All the LEDs will turn off, and the Keypad will emit one long beep.

## _**System Mode Control**_

After finish learning the Keypad into the alarm system Control Panel, the user may change the system using the Keypad.

There are two ways to arm the system.

1. Away Arm/Home Arm the system by entering the Control Panel User PIN Code.
2. Away Arm/Home Arm the system without entering the Control Panel User PIN Code. Disarming the system always requires entering the Control Panel User PIN Code.



_**Arm/Home with Control Panel PIN Code:**_

Under Programming Mode, Pressing ＊ key and then **9** key to enable Arm/ Home with User PIN Code function.

**Enter Arm Mode**: Enter any one of the Control Panel user codes and press the (arming away button) key, or press the (arming away button) key and apply an NFC label. If the panel has no fault and arming is successful, the  LED will turn ON along with a long beep.

**Enter Home Mode:** Enter any one of the Control Panel user codes and press the (arm stay button) key, or press the (arm stay button) key and apply an NFC label. If the panel has no fault and arming is successful, the  LED will turn ON along with 3 beeps.

**Return to Disarm Mode**: Enter any one of the Control Panel user codes and press the disarm button) key, or press the disarm button) key and apply an NFC label. If disarm is successful, the  LED will turn ON along with 2 beeps. If there is an **Alarm Memory,** the (disarm button) LED and fault LED will turn ON along with 5 beeps.



_**Arm/Home without Control Panel PIN Code:**_

In the Programming Mode, Pressing ＊ key and then **8** key to enable Arm/Home without User PIN Code function

**Enter Arm Mode:** Press the (arming away button)  key. If the panel has no fault and arming is successful, the (arming away button)  LED will turn ON&#x20;along with one long beep.

**Enter Home Mode**: Press the (arm stay button) key. If the panel has no fault and arming is successful, the (arm stay button) LED will turn ON&#x20;along with 3 beeps.

**Return to Disarm Mode**: Enter any one of the Control Panel user codes and the (disarm button) Key, or press the (disarm button) key and apply a label. If disarm is successful, the (disarm button)  LED will turn ON along with 2 beeps. If there is an **Alarm Memory,** the (disarm button) LED and fault LED will turn ON along with 5 beeps. (Disarm always requires a Control Panel User Code or NFC label.)



## _**Bluetooth Function to Disarm the System via Smartphone**_

To use the keypad’s Bluetooth feature to disarm the system via Smartphone, the Control Panel must be registered on the Home Portal Server.

**SmartHomeSec&#x20;**_**APP**_ is used for Bluetooth pairing the smartphone with the keypad. Up to **25** smartphones can be paired with the keypad to disarm the system via the SmartHomeSec APP.

Please go to the APP store or Google Play and search SmartHomeSec to download the application.

### **Bluetooth Setup**

#### <mark style="color:blue;">**Pairing the Keypad with one or multiple smartphones**</mark>

**Step 1.** In keypad **tamper open state**, put the keypad into the **BLE Pairing mode** by pressing and holding both **＊** key and **0** key together for **2 seconds**. When entering the BLE Pairing mode, the Keypad emits a long beep, and the Green and Orange LED will turn on during BLE Pairing mode.

**Step 2.** On your smartphone, open the **SmartHomeSec&#x20;**_**App**_, enter the registered user ID and password, and tap Connect to log into your account.

{% hint style="warning" %}
Note:

Make sure Bluetooth is turned on for your smartphone setting.
{% endhint %}

**Step 3.** Go to the All Devices page and select VESTA-012N. Tap “**Start Bluetooth Pairing**.”

**Step 4.** The app will automatically start scanning the Keypad that is under BLE Pairing mode. If it does not start scanning automatically, tap the button on the screen to search for the Keypad.

When the detected Keypad is shown on the list, tap it to enter the Pairing PIN Code page. Enter the BLE Pairing PIN Code **(Default: 000000)** and tap the **Pair** button to proceed.

{% hint style="warning" %}
Note:

To edit the Pairing PIN Code, enter 6-digit PIN Code and ＊ on the Keypad under the BLE Pairing mode.
{% endhint %}

If the PIN Code setting is confirmed, the Keypad emits 1 long beep. If the PIN Code setting is not confirmed, the Keypad emits 4 beeps.

**Step 5.** When the dialog box Pairing Successful is shown on the APP, Pairing is successful.

Click OK, and you will be directed to the KPT device setting page, where you will need to set your PIN code.

**Step 6.** Select the PIN Code and input a 4-digit or 6-digit Control Panel User PIN.

If the user wants to leave this page but the User PIN field is empty, the system will pop up an error message.

{% hint style="warning" %}
Please Note:

When the Keypad is in the BLE Pairing mode, users can pair the Keypad with one or multiple smartphones. Whether the first pairing smartphone is connected or not, the second and more smartphones can be paired with the Keypad by following steps **2\~6** in the instructions above.

The Keypad can pair with a maximum of 25 smartphones.
{% endhint %}

**Step 7.** Leave the BLE Pairing Mode by pressing **#** key once. Otherwise, the Remote keypad will automatically exit BLE Pairing Mode after 5 minutes and return to Stand-by mode.

#### <mark style="color:blue;">**Unpairing a Keypad with One or Multiple Smartphones**</mark>

**Step 1.** Under keypad **BLE Pairing mode**, you can unpair the Keypad with one or multiple smartphones.

In keypad **tamper open state**, put the keypad into the **BLE Pairing mode** by pressing and holding both **＊** key and **0** key together for **2 seconds**. The Keypad emits a long beep and Green and Orange LED turn on.

* Press **0, or 1, or 2, … 24** key and then **#** key — to unpair the 1st , 2nd, 3rd, ….or the 25th smartphone.
* Press **25** key and then **#** key — to unpair all smartphones.

**Step 2.** Besides unpairing the keypad with your smartphone, you will also need to remove the Bluetooth Function of the keypad in your Smartphone APP.

7

**Step 3.** Then, delete the paired Keypad from your smartphone. Navigate the Smartphone’s **Settings** > **Bluetooth** > **My Devices.** Tap the paired Keypad and select **Forget This Device** to remove it from the device list.

* **Disarming the System via Smartphone**

To disarm the system via a paired smartphone:

*
  * The smartphone’s Bluetooth function needs to be turned ON, and the Vesta Home 5 APP must be kept active in the background so that the device can communicate with the App.
  * A 4-digit or 6-digit Control Panel User Code must have been saved in the Vesta Home 5 APP.

When the system is armed, approach the keypad with the paired smartphone. Once the Keypad detects the paired smartphone within the BLE range, the system will automatically disarm.

_**Note:**_

*
  *
    * The effective BLE range may differ depending on different mobile devices.
    * After the system arms, a 30-second buffer is configured for the paired mobile to be out of the Keypad BLE range. The keypad will start detecting only after the system is armed for 30 seconds. If the paired mobile is within the BLE range when the system arms, the system will not Disarm until the 30-second buffer passes.
* _**Entry/Exit Sound**_
  * After the Entry/Exit Sound is enabled by pressing **1** key + **2** key at the same time for 2 seconds (indicated by one long beep), the keypad will sound beeps when the Entry/exit timer is activated.
  * After the Entry/Exit Sound is disabled by pressing **1** key + **2** key at the same time for 2 seconds (indicated by two short beeps), the keypad will remain silent when the Entry/exit timer is activated.
* _**Fault Conditions**_

_When Remote Keypad is under **NORMAL OPERATION MODE,**_

*
  1. When fault condition exists within Control Panel, if the Keypad is used to arm the panel, the Fault LED will flash along with 3 beeps to indicate fault condition.
  2. When the Keypad disarms the panel, the  LED will turn ON along with two beeps indicating normal operation.
  3. If you input incorrect KP Pin code for 4 times within 10 minutes under Programming Mode, KP will disable the key function for 1 minute and all the LEDs will flash 3 times along with 6 beeps. After 1 minute, it will emit a long beep to indicate that the key function is back to normal.
  4. If you input incorrect User PIN Code for 4 times within 10 minutes when changing system mode, KP will disable key function for 5 minutes. After 5 minutes, the keypad will emit a long beep to indicate that the key function is back to normal.
* _**Factory Reset**_

Resetting the Keypad to factory default will restore Keypad’s own PIN Code to 0000 and clear all panel learning memory.

_**Reset to factory default:**_

Step 1 Remove the batteries and release the tamper.

Step 2 If “**Arm/Home with Control Panel PIN Code**” method is selected, press & hold **3** key while inserting the battery back.

.If “**Arm/Home without Control Panel PIN Code**” method is selected, press & hold **4** key while inserting the battery back.

Step 3 Continue pressing **3** key until KP emit 3 beeps to indicate successful reset.

.Continue pressing 4 key until KP emit 4 beeps to indicate successful reset.

Step 4 Release **3** or 4 key, the reset process is complete. After reset, PIN code reverts to factory default values, **0000**.

.Remote keypad will need a new learn-in process to start functioning.

*
  * Whenever the Keypad is removed from the Control Panel, it should be put to factory reset as well to clear its Control Panel memory.
* _**Mounting Remote Keypad**_

To mount the remote keypad:

1. Remove the front cover.
2. Using the 2 mounting holes of the back cover as a template, mark off the positions in the most appropriate place.
   1. Insert the wall plugs if fixing into plaster or brick surface.

IV. Screw the remote keypad onto the wall plugs.

V. Replace the front cover.

8
