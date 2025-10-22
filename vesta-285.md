# VESTA-285

MH4936

## Boiler thermostat with integrated Z-Wave

<figure><img src=".gitbook/assets/image (2) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1).png" alt=""><figcaption></figcaption></figure>

## Introduction

MCO Home MH4936. Boiler thermostat with integrated Z-WAVE. Measurement of interior temperature and control of boiler heating. Remote control via Z-Wave Plus, integrated with VESTA panels. LCD display screen. Temperature setting. Tactile buttons for local control. Modern design with tempered glass. Quick connection terminals for cables. Automatic backlighting with motion sensor (PIR). Z-Wave Plus frequency: 868.42 MHz Boiler thermostat with integrated z-wave.

### Main Features

* Boiler thermostat with integrated Z-WAVE
* Measurement of interior temperature and control of boiler heating
* Remote control via Z-Wave Plus, integrated with VESTA panels
* LCD display screen
* Temperature setting
* Tactile buttons for local control
* Modern design with tempered glass
* Quick connection terminals for cables
* Automatic backlighting with motion sensor (PIR)
* Z-Wave Plus frequency: 868.42 MHz
*   Power supply: 24V AC / 24V DC, 4 AA batteries

    5 \~ 6 meter PIR range with 100 ° detection angle
* Self-consumption: <2W
* Resistive load: <1A
* NTC thermistor



## Wiring Diagram

**REQUIRED:** 24 VAC POWER (“C” WIRE)

<figure><img src=".gitbook/assets/image (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1).png" alt=""><figcaption></figcaption></figure>

<table><thead><tr><th width="118">Terminal</th><th width="371">Terminal Description</th></tr></thead><tbody><tr><td>C</td><td>AC 24 V power supply</td></tr><tr><td>RH</td><td></td></tr><tr><td>RC</td><td></td></tr><tr><td>WI</td><td>Is, stage heating</td></tr><tr><td>W2</td><td>200 stage heating or auxiliary heating</td></tr><tr><td>G</td><td>Fan</td></tr><tr><td>YI</td><td>Compressor stage I</td></tr><tr><td>Y2</td><td>Compressor stagc2</td></tr><tr><td>0/B</td><td>Changeover</td></tr><tr><td>K</td><td>Wire with 4-5T module</td></tr><tr><td>EF</td><td>Reserved terminal</td></tr></tbody></table>

Note: A wire saver acts as a splitter for applications that do not include a 24-volt C wire. If your heating/cooling system does not include a C wire,install the wire saver in or near the main unit (furnace, air handler) of your heating/cooling system.

<figure><img src=".gitbook/assets/image (2) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1).png" alt=""><figcaption></figcaption></figure>

**Controlling Type**

<figure><img src=".gitbook/assets/image (3) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1).png" alt=""><figcaption></figcaption></figure>

## Display

<figure><img src=".gitbook/assets/image (4) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1).png" alt=""><figcaption></figcaption></figure>

### Functions & Settings

* **Setpoint Setting**\
  Press “/\”or ” V” to set the desired indoor temperature. Setting range: 5\~37 t (41\~98 “F) by default.
* **Mode Setting**\
  This device supports OFF, HEAT, COOL, AUTO mode and EM mode (not enabled by default). Press the “MODE” button to switch the working mode.
* **Fan Mode Setting**\
  Short press the “FAN” key to switch the working mode of the fan.
* **Fan On**\
  In this mode, the fan is always running when it is turned on, and stops when it is turned off.
* **Fan Auto**\
  In this mode, the fan runs both in cooling and heating state ; the fan stops when cooling or heating is stopped, when the device is in shutdown state, the fan stops.
* **Secret Menn**\
  Under “OFF” interface, long press “MODE” button for 3 sec to enter into parameter setting interface. Short press “MODE11 button to switch the parameter number, press A “or” V “to modify the corresponding setting value, and then press “FAN” to confirm and then exit.



<table data-full-width="true"><thead><tr><th width="61">Menu Number</th><th width="125">Item</th><th width="112">Setting Range</th><th width="111">Default</th><th width="800">Description</th></tr></thead><tbody><tr><td>01</td><td>Restore factory setting</td><td>0-99</td><td>53</td><td>Default 53, change to 55 to restore factory setting</td></tr><tr><td>02</td><td>Device state after power failure</td><td>0- I</td><td></td><td>0 : device turn to OFF stateI: device return to last stat before power failure</td></tr><tr><td>04</td><td>Beep volume</td><td>1-5</td><td></td><td>I: Mute            2: Low    3:Medium    4: High    5: Normal</td></tr><tr><td>06</td><td>Temp. setting upper limit</td><td>1-99</td><td>37C/98F</td><td>gap I</td></tr><tr><td>07</td><td>Temp. setting bottom limit</td><td>0-98</td><td>5 C/41F</td><td></td></tr><tr><td>08</td><td>Indoor temperature calibration</td><td>-9.9-+9.9</td><td></td><td>-9.9-+9.9</td></tr><tr><td>09</td><td>Indoor humidity calibration</td><td>-20-+20</td><td></td><td>-20- +20</td></tr><tr><td>11</td><td>Temp. deadband</td><td>0-9.0</td><td>1.0 C/2.0 F</td><td></td></tr><tr><td>12</td><td>Temp. format</td><td>0-1</td><td></td><td>0: Celsius              1: Fahrenheit</td></tr><tr><td><p> </p><p> </p><p>13</p></td><td><p> </p><p> </p><p>Controlling type</p></td><td><p> </p><p> </p><p>00-07</p></td><td><p> </p><p> </p><p>07</p></td><td><p>Conventional cooling/heating system <br> 0= cool only              1= heat only            2= cool or heat</p><p><br>Heat pump cooling/heating system</p><p>3= cool only              4= heat only           5= two stages heat <br>6= single cooling/single heating+ AUX</p><p>7= two stages cooling/ two stages heating+ AUX</p></td></tr><tr><td><p> </p><p>14</p></td><td><p> </p><p>Changeover valve logic</p></td><td><p> </p><p>0-1</p></td><td></td><td>00=When the heat pump cooling starts, 0/B turned on, but turned off when heating<br>01=When the heat pump heating starts, 0/B turned on, but turned off when cooling</td></tr><tr><td>15</td><td>Compressor protection time</td><td>0-10unit: minute</td><td></td><td>Indicates the setting of compressor delay time from shutdown to startup</td></tr><tr><td>16</td><td>EM emergency heating mode</td><td>ON/OF</td><td>OF</td><td>ON=turn on emergency heating mode OF=turn off emergency heating mode <br>Only available for heat pump system with heating function</td></tr></tbody></table>

### Z-Wave Setting

**Include into Z-Wave network**\
Under the normal working interface, long press the” A “and” V ” buttons synchronously for 3sec, and the device will enter the Z-WAVE MENU interface, long press the” A “and” V” buttons synchronously for 3sec again or without any operation for 10sec, it will back to the homepage. Before the device is included in the network,”- – -” will display on the screen. Then shortly press the” A” button, the device will enter learning mode to get a node ID. If inclusion is a success, a node ID will display on the screen in a few seconds. Note: A node ID can always inform us whether the device is in the network or not.

**Exclude from Z-Wave network**\
Under the normal working interface, long press the” A “and” V ” buttons synchronously for 3sec, and the device will enter the Z-WAVE MENU interface, long press the” A “and” V” buttons synchronously for 3sec again or without any operation for 10sec, it will back to the homepage. Current ID displays on the screen, short press the” A” button, and the device will enter learning mode, current ID will flash, once “- – -” is displayed on the screen, the device has excluded from the Z-Wave network.

**Z-WAVE supported Command Class:**

Support S2:

* COMMAND\_ CLASS\_ VERSION,
* COMMAND\_CLASS\_POWERLEVEL,
* COMMAND\_CLASS\_MANUFACTURER\_SPECIFIC,
* COMMAND\_CLASS\_BATTERY,
* COMMAND\_CLASS\_DEVICE\_RESET\_LOCALLY,
* COMMAND\_ CLASS\_SENSOR MULTILEVEL\_ V5,
* COMMAND\_ CLASS\_ THERMOSTAT\_ SETPOINT,
* COMMAND\_ CLASS\_ THERMOSTAT\_ OPERATING\_ STATE,
* COMMAND\_CLASS\_THERMOSTAT\_FAN\_STATE,
* COMMAND\_ CLASS\_ ASSOCIATION\_ V2,
* COMMAND\_ CLASS\_ ASSOCIATION\_ GRP INFO,

**Not support S2:**

* COMMAND\_ CLASS\_ THERMOSTAT\_ MODE,
* COMMAND\_CLASS\_THERMOSTAT\_FAN\_MODE,
* COMMAND\_CLASS\_CONFIGURATION,
* COMMAND\_CLASS\_MULTI\_CHANNEL\_ASSOCIATION\_V2,
* COMMAND\_ CLASS FIRMWARE\_ UPDATE\_ MD\_ V5
* COMMAND\_ CLASS\_ ZWAVEPLUS \_ INFO,
* COMMAND\_ CLASS\_ SECURITY\_ 2,
* COMMAND\_ CLASS\_ TRANSPORT\_ SERVICE\_ V2,
* COMMAND\_ CLASS\_ SUPERVISION



