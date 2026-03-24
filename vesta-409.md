---
hidden: true
---

# VESTA 409

PIR Motion Sensor (IR-32SL-ADC2)

## Introduction

The PIR detects infrared signature to pick up movements within an assigned area and signals the Control Panel to activate the alarm if an intruder crosses its’ path of detection.

The PIR is designed to give a typical detection range of 12 meters when mounted at a height of 2.5 meters above the ground. The PIR sensor also supports pet immunity feature and will not detect pets of up to 25 kg to minimize false alarm situations.

The PIR consists of a two-part design made up of a cover and a base. The cover contains all the electronics and optics, and the base provides a means of fixing.

## Parts Identification

![](<.gitbook/assets/Unknown image (247)>)

Front View

![](<.gitbook/assets/Unknown image (248)>)

Internal View

![](<.gitbook/assets/Unknown image (249)>)

Back View

![](<.gitbook/assets/Unknown image (250)>)

1. Test Button / LED Indicator

* The test button is used for testing the radio performance and for learning purpose.
* The LED indicator is used to indicate the status of system. 2. IR Sensor

1. ![](<.gitbook/assets/Unknown image (251)>)Battery Compartment
2. Bottom Fixing Screw
3. Tamper Switch
4. Pet Immunity Enable/Disable Jumper Switch (JP3)

### Jumper On Jumper Off

The jumper link is inserted, The jumper link is removed or connecting the two pins. “parked” on one pin.

![](<.gitbook/assets/Unknown image (252)>) ![](<.gitbook/assets/Unknown image (253)>) ![](<.gitbook/assets/Unknown image (254)>) ![](<.gitbook/assets/Unknown image (255)>)

* When set as ON, Pet Immunity is disabled.
* When set as OFF, Pet Immunity is enabled (Factory default).

1. Sensitivity Increaser Jumper Switch (JP4)

* When set as ON, the PIR’s detection sensitivity is high.
* When set as OFF, the PIR’s detection sensitivity is in normal level (Factory default).

2. Battery Insulator Hole

## Features

### LED Indicator

In Normal operation mode, the LED Indicator will light up in the following situations:

 When movement is detected under low battery condition  When the cover is opened and the tamper switch is triggered.

 When movement is detected if the Tamper condition persists.

 When movement is detected under Test mode

 When the Test Button is pressed under tamper condition or if the PIR is low in battery.

The LED will not flash if the PIR tamper and battery are normal and the PIR is not under test mode.

### Battery

The IR-32SL-ADC2 uses one CR123 3V lithium battery as its power source.

The PIR features low battery detection. If low battery voltage is detected, a low-battery signal will be sent to the Control Panel along with regular signal transmissions for the Control Panel to display the status accordingly.

For each installation, the battery is installed with a battery insulator inserted by the factory before shipment.

 When changing the battery, after removing the old battery, press the Tamper Switch twice to fully discharge before inserting a new battery.

### Tamper Protection

The PIR is protected by a tamper switch which is depressed when the PIR is properly installed. When the PIR is removed from mounted surface or mounting bracket, or its cover opened, the tamper switch will be activated and the PIR will send a tamper open signal to the system control panel to remind the user of the condition. If movement is detected when the tamper switch is open, the LED will light up.

### Supervision Function

When the PIR is in Normal operation mode, it will conduct a self-test periodically by transmitting a supervisory signal once every 15 to 18 minutes.

If the Control Panel fails to receive the supervisory signals transmitted from a certain PIR for a preset time, a fault message “Out-Of-Order” will be generated.

### Test Mode

The PIR can be put into Test mode by pressing the Test Button. In test mode, it will disable the sleep timer and will enable the LED indicator to light up every time a movement is detected. Every time the Test Button is pressed, the PIR will transmit a test signal to the Control Panel for radio range test and enter test mode for 3 minutes. Test mode will time out after 3 minutes.

### Sleep Timer

The PIR has a “sleep time” of approximately 1 minute to conserve power. After transmitting a detected movement, the PIR will not retransmit for 1 minute; any further movement detected during this sleep period will extend the sleep time by another minute. In this way continuous movement in front of a PIR will not unduly exhaust the battery.

### Pet Immunity Function

The PIR sensor supports pet immunity feature and will not detect pets of up to 25 kg to minimize false alarm situations.

The Pet Immunity function can be enabled/disabled by setting the position of the Jumper Switch (JP3). When the Jumper Switch (JP3) is set to ON, Pet Immunity is disabled. When the Jumper Switch (JP3) is set to OFF, Pet Immunity is enabled (Factory default).

### Sensitivity Increaser Function

You can use the sensitivity increaser function to increase the PIR’s detection sensitivity. To increase detection sensitivity, set the Jumper Switch (JP4) to ON. To maintain normal detection sensitivity, set the Jumper Switch (JP4) to OFF (Factory default).

### Getting Started

 Pull out the battery insulator to activate battery.

 The LED indicator will flash for 30 seconds. (The PIR is warming up). During the warm-up period, the PIR will not be activated. After the warm-up period, the LED will turn off and the PIR will be ready for operation.

 Put the Control Panel into learning mode (refer to the Control Panel’s manual for details).

 Press the test button.

 Refer to the Control Panel’s manual to complete the learn-in process.

 After the PIR is learnt in, put the Control Panel into “Walk Test” mode; hold the PIR at the desired location, and press the Test button to confirm whether this location is within the signal range of the Control Panel (refer to the Control Panel’s manual to complete Walk Test).

 When you are satisfied that the PIR works at the chosen location, you can proceed to mounting.

## Installation

### Installation Guideline

 The PIR is designed to be mounted either on a flat surface or in a corner.

 The detection range is up to 12 meters if the PIR is mounted at a height of 2.3-2.5 meters above the ground. 

 When Pet-Immunity function is enabled, the PIR will not detect pets up to 25kg when mounted at a height of 2.3-2.5 meters above the ground. If required, you can adjust the height of the PIR according to the size of your pet for optimal pet immune performance. Higher installation location will provide larger pet-immune space, but increase the blind spot under the PIR. 

 When the PIR is mounted with the rotating bracket, it will not have the regular detection area (as in the diagram), or the typical pet immune range.

 After the installation site is selected, press the Test Button to enter Test Mode. Walk around the protected area noting when the LED lights up and check whether the detection coverage is adequate.

 When the detection coverage is found to be satisfying, follow the steps described in Mounting Method section below to mount the PIR.

![](<.gitbook/assets/Unknown image (256)>)![](<.gitbook/assets/Unknown image (257)>) The PIR is designed to be mounted either on a flat surface or in a corner.



Mounting Method

![](<.gitbook/assets/Unknown image (258)>)

 The base has two knockouts where the plastic is thinner and can be broken for mounting purpose.

 For corner mounting, a triangular bracket is provided to add Back Tamper Protection. The bracket also includes four knockouts for mounting on the corner

 For surface mounting, an optional rotating bracket is provided for users to adjust the range of detection. With the rotating bracket, IR-32SL-ADC2 can be rotated 80 degrees horizontally and 70 degrees vertically to provide optimal coverage.

####  Corner Mounting with the triangular bracket

The PIR camera can be mounted in the corner by means of the triangular bracket provided.

1. Break through the four knockouts on the triangular bracket.
2. Use the holes as a template and drill holes into the corner surface to be mounted.
3. Insert the wall plugs if the PIR is to be fixed onto plaster or bricks.
4. Screw the triangular bracket onto the wall plugs with the two pointing sticks on top and facing you. 5) Fit the PIR onto the hooks of the triangular bracket.

Corner Mounting

####  Surface Mounting

 The PIR can also be mounted directly on a flat surface with the fixing screws and wall plugs provided.

 The base has two knockouts where the plastic is thinner and can be broken for mounting purpose. The steps for surface mounting through the two knockouts are described and shown in the picture below.

1. Unscrew the bottom fixing screw and detach the cover and the base.
2. Break through the two knockouts from the inside of the base.
3. Use the holes as a template and drill holes into the surface to be mounted.
4. Insert the wall plugs if the PIR is to be fixed onto plaster or bricks.
5. Screw the base onto the wall plugs.
6. Screw the cover back to the base.

Surface Mounting

![](<.gitbook/assets/Unknown image (259)>)

####  Surface mounting with the rotating bracket (optional item, sold separately)

 For surface mounting, an optional rotating bracket is provided for users to adjust the range of detection. With the rotating bracket, IR-32SL-ADC2 can be rotated 80 degrees horizontally and 70 degrees vertically to provide optimal coverage.  The rotating bracket can be mounted on the wall with the screws provided.

1. Screw the rotating bracket onto the wall.
2. Fit the PIR onto the 3 hooks of the rotating bracket.
3. Rotate the bracket for the proper range of detection and tighten the fixing screw.

![](<.gitbook/assets/Unknown image (260)>)

###  Installation Recommendations

 It is recommended to install the PIR in the following locations:

|  | At a height of 2.3-2.5 meters above the ground for best performance.                                         |
| - | ------------------------------------------------------------------------------------------------------------ |
|  | At a position where the animals cannot come to the detection area by climbing on furniture or other objects. |
|  | Don’t aim the device at stairways on which the animals can climb.                                            |
|  | At a position such that an intruder would normally move across the PIR’s field of view from side to side.    |
|  | In a corner to give the widest view.                                                                         |
|  | At a position where its field of view will not be obstructed by, e.g., curtains, ornaments etc.              |

 Limitations

|  | Do not install outdoors.![](<.gitbook/assets/Unknown image (261)>)                                                                                                                                 |  | Avoid large obstacles in the detection area.![](<.gitbook/assets/Unknown image (262)>)                                                           |
| - | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | - | ------------------------------------------------------------------------------------------------------------------------------------------------ |
|  | Do not expose the PIR completely to direct sunlight.![](<.gitbook/assets/Unknown image (263)>)                                                                                                     |  | Avoid vapor or high humidity that can cause condensation.![](<.gitbook/assets/Unknown image (264)>)                                              |
|  | Avoid moving objects in the detection area e.g., curtains, wall hangings, etc.![](<.gitbook/assets/Unknown image (265)>)                                                                           |  | Avoid reflected light from bright surfaces, e.g., mirrors, windows, etc.![](<.gitbook/assets/Unknown image (266)>)                               |
|  | Avoid installing the PIR in areas where machines may cause rapid change in temperature in the detection area, e.g., near air conditioners, heaters, etc.![](<.gitbook/assets/Unknown image (267)>) |  | Avoid reflecting surface in the detection area. Reflected infrared signatures may lead to false alarm.![](<.gitbook/assets/Unknown image (268)>) |
