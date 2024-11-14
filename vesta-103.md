# VESTA-103

**Shutter Control (SCM-8)**

**Introduction**

SCM-8 is a Roller Shutter Control that provides convenient operation, remotely roll up, down, or stop of motorized roller shutters.

The Roller Shutter Control has two motor outputs for automatic and remote control and two local switches for optional manual control. The user can control the SCM-8 via the Control Panel at a remote distance or manually by activating local switches.

SCM-8 is also equipped with a strain relief clamp and a wiring buckle for electrical and mechanical integrity, overall performance, and safety.

## **Parts Identification**



![](<.gitbook/assets/0 (57).jpeg>)

1. **Test Button**

* Press once: Transmit supervision signal.
* Report current position to the Control Panel.
* Press and hold for 3 seconds: Send a learn code.
* Press and hold the button while powering on the Shutter Control, keep holding the button for about 4 seconds, then release the button when the LED flashes 3 times to factory reset.
* Press and hold for 10 seconds: Enter Calibration mode.

2. **LED indicator**

The LED indicator is used to indicate Shutter Control status:

* Flashes once: When powered on.
* Flashes twice: When learning is successful.
* Flashes 3 times: Shutter Control has been factory reset.
* Turns steady on: Under learning mode.
* Flashes continuously: When in Calibration mode.

3. **Mounting Holes**
4. **Local Switch S1 (Open Direction)**
   * Connect an external switch to this terminal. Activate this switch to control the shutter to roll toward “Open” direction by activating the Motor Output O1.
   * Activating this switch when the shutter is rolling towards the “Close” direction will stop the shutter.
5. **Local Switch S2 (Close Direction)**
   * Connect an external switch to this terminal. Activate this switch to control the shutter to roll toward “Close” direction by activating the Motor Output O2

* Activating this switch when the shutter is rolling towards the “Open” direction will stop the shutter.

6. **Motor Output O1 (Open Direction)**

Connect to the Open terminal of the Shutter Motor.

**7. Motor Output O2 (Close Direction)**

Connect to the Close terminal of the Shutter Motor.

8. **Power Input L (Live Lead)**
9. **Power Input N (Neutral Lead)**
10. **Strain Relief Clamp**

The clamp is used for securing the wires, and providing strain relief to protect the wires from the metal cutout.

**11. Wiring Buckle**

The Wiring Buckle is used for managing wires.

## **Specification**

* Power Supply: 100 - 240VAC, 50/60Hz
* Supported Load Current: 1/2 HP (Horse power); 3.6Amps for motors with compensated power factor (inductive loads)

## **Caution**

* All works on the device, including installation and maintenance, must be performed by a qualified and licensed electrician.
* Before installation or any maintenance work, make sure the power supply has been disconnected.
* Do not connect the device to loads exceeding supported load current.
* Please connect the device to AC powered motor only.

## **Wiring**

* <mark style="background-color:yellow;">SCM-8</mark> should be connected according to the diagram below:

![](<.gitbook/assets/2 (40).jpeg>)

* Connect N terminal of SCM to the N terminal of Power Supply.
* Connect L terminal of SCM to the L terminal of Power Supply.
* Connect O1 terminal of SCM to the Open terminal of the Shutter Motor.
* Connect O2 terminal of SCM to the Close terminal of the Shutter Motor.
* **(Optional local switch)** Connect S2 and S1 terminals of SCM to the L terminal of Power Supply.

Insert each wire into the terminal that it should be connected to, tighten each screw to close the clippers and hold the wires in place.

After the wires are connected, use the wiring buckle to manage the wires, and place the wiring buckle on the base with its gap (opening) positioned on the left.

![](<.gitbook/assets/3 (39).jpeg>)

## **Learning**

Step 1: Connect the power supply to the Shutter Control according to the installation instructions in previous section and power up the Shutter Control.

Step 2: Put the Control Panel into learning mode.

Step 3: Press and hold the Test button on the Shutter Control for 3 seconds to send a learn code.

Step 4: The LED will flash once and then turn steady on after the button is released, indicating that the Shutter Control is in learning mode.

Step 5: If the Control Panel receives the signal from the Shutter Control, it will display the information accordingly. Refer to the Control Panel manual to complete the learn-in process.

Step 6: When the Shutter Control receives the learning code from the Control Panel, the LED of the Shutter Control will flash twice and then turn off to indicate that learning process is complete.

_\<NOTE>_

* After entering learning mode, if the Shutter Control does not receive acknowledgement from the Control Panel for 1 miniute, it will automatically leave learning mode.
* If the Shutter Control already exists in a Control Panel system, you will need to first remove the Shutter Control from the Control Panel before you can learn it into a different Control Panel.

## **Walk Test**

To test whether the Shutter Control is able to communicate with the Control Panel:

* Put the Control Panel into Walk Test mode.
* Press the Test Button on the Shutter Control.
* The Control Panel should display if the Shutter Control is within the operation range (please refer to the operation manual of the Control Panel).

## **Mounting**

* After you have finished the walk test, and you are satisfied that the device is able to communicate with the control panel in the chosen location, proceed to mounting.
* Disconnect the main power supply.
* Loosen the bottom fixing screw and remove the top cover of the Shutter Control.
* Use the Mounting holes on the base to mark mounting location on the wall.
* Drill holes into marked location and insert wall plugs if required, screw the base onto the mounting location.
* Replace the top cover and tighten the bottom fixing screw.

## **Supervision**

* After the Shutter Control is successfully learned in to the Control Panel, the device will automatically transmit supervisory signal along with current position report to the Control Panel at random intervals of 30 to 50 minutes.
* If the Control Panel has not received the signal from the Shutter Control for the preset period of time, the Control Panel will indicate on its display that the particular Shutter Control is experiencing an out-of-signal problem.

## **Operation**

### _**Calibration**_

* The Shutter Control default activation time is **4** minutes. When the Up/Down button is pressed or the Control Panel sends Up/Down request, it will activate the Shutter Motor for 4 minutes.
* For the Shutter Control to work properly, its activation time must be calibrated manually. Calibrate the activation time according to procedures below:
  1. Before calibration, the external local switches must be connected to the Shutter Control.
  2. Press and hold the Test button for 10 seconds and then release to enter Calibration mode (The LED will flash twice). The Shutter Control will roll toward the “Open” direction for 4 minutes after entering Calibration mode.
  3. Wait for 4 minutes for Shutter motor to stop rolling, then press “Down” button to roll down the shutter. (If less than 4 minutes the shutter has reached the open position already, you can press the “Down” button to stop the shutter motor. Then press the “Down” button again to roll down the shutter.)
  4. Press the “Up” button the moment the shutter is fully closed. The Shutter control will record the time it took for the shutter to roll from open to close as the new “**close time**”.
  5. The Shutter Control will roll toward open direction after step 4 (when the “Up” button is pressed the moment the shutter is fully closed).
  6. Press the “Down” button the moment the shutter is fully opened. The Shutter control will record to time it took for the shutter to roll from close to open as the new “**open time**”.
  7. After calibration is completed, the Shutter Control will send current position report to the Control Panel and operate with new close/open time.

Example

If it takes 30 seconds for the shutter to move from Open to Close, and 40 seconds to move from Close to Open, the new **close time** will be **30** seconds and new **open time** will be **40** seconds.

After calibration, whenever the Shutter Control receives close request, it will roll toward close direction for 30 seconds. When it receives open request, it will roll toward open for 40 seconds.

* The activation time will be reset to **4** minutes whenever the Shutter Control has been factory reset.

## _**Shutter Control**_

### **Remote Control**

* After the Shutter Control is successfully learned into the Control Panel, the user can remotely control the shutter to open, close or stop via the Control Panel Webpage.
* When the Shutter Control receives open/close request from the Control Panel, it will roll toward open/close direction according to calibrated activation time to fully open/close the shutter.
* The Shutter status can also be adjusted by percentage from 0%, 10%, 20%... to 100% through the Control Panel Webpage.
* The current open percentage is also transmitted to the Control Panel.

![](<.gitbook/assets/4 (59).png>)

### **Local Switch**

* If an optional Local Switch is connected, users can also press the switch button to open/close the shutter.
* Press and release the switch for less than 1 second will control the shutter to fully open or close.
* Pressing the switch when the shutter is moving to opposite direction will stop the shutter. Press the switch again to open/close the shutter.

For example, pressing the down switch when the shutter is opening will stop the shutter, press down switch again to start closing the shutter.

## **Factory Reset**

* Factory resetting the Shutter Control will clear its memory and restore it to factory default settings.
* Press and hold the button while powering on the Shutter Control, keep holding the button for about 4 seconds, then release the button when the LED flashes 3 times to factory reset.
