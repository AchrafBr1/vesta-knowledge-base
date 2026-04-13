---
hidden: true
---

# VESTA 410

PIR Motion Sensor Camera (VST-892-IL-ADC2)

## Introduction

VST-892-IL-ADC2 is a passive infrared (PIR) motion sensor camera. It is capable of sending wireless signals and captured images (picture quality of up to 640 x 480 pixels) to the Control Panel upon movement detection.

The PIR Camera is designed to give a typical detection range of 12 meters when mounted at a height of 2.3-2.5 meters above the ground. When Pet Immunity function is enabled, the motion sensor camera will not detect pets up to 25kg when mounted at a height of 2.3-2.5 meters above the ground. VST-892-IL-ADC2 is also compatible with Climax’s Repeater RP-29/Router RMB-29, which can further extend the RF communication range into hard-to-reach areas.

VST-892-IL-ADC2 is designed with a digital proximity detector. The anti-masking feature allows for detection of any attempts to blind the detector by placing objects in its field of view.

VST-892-IL-ADC2 also supports Remote configuration. Besides adjusting the Jumper Switches, users can also enable/disable pet immunity and adjust the sensitivity of the PIR camera from the Control Panel’s webpage or Home Portal Server.

The PIR Camera consists of a two-part design made up of a cover and a base. The cover contains all the electronics and optics and the base provides a means of fixing. The base has knockouts to allow the PIR camera to be mounted on a flat surface, or a triangular bracket is provided for mounting the PIR camera in a corner.

## ![](<.gitbook/assets/Unknown image (393)>)Parts Identification

1. Infrared LED

The Infrared LED delivers sufficient light for image capture under low lighting condition.

1. Blue LED/Function Button

Blue LED:

(Please refer to LED Indicator description below for details) Function Button Usage:

*
  * Press and hold the button for 3 seconds to send a learn code, release when Blue LED lights on.
  * Press the button once to enter test mode for 3 minutes.
  * Press the button once to send a learn code to the repeater/router.

1. Digital Proximity Detector

The digital proximity detector is used to detect any masking (blocking) attempts by an intruder.

4

. IR Sensor

5

. PIR Camera Lens

. Battery Compartment

6

7

. Tamper Switch

8

. Pet Immunity Enable/Disable Jumper Switch (JP

3.

When set as ON, Pet Immunity is disabled.

When set as OFF, Pet Immunity is enabled. (Factory default)

. Sensitivity Increaser Jumper Switch (JP4)

9

When set as ON, the PIR’s detection sensitivity is high.

When set as OFF, the PIR’s detection sensitivity is in normal level

(

Factory default

).

![](<.gitbook/assets/Unknown image (394)>) ![](<.gitbook/assets/Unknown image (395)>)

Jumper On

The jumper link is inserted,

connecting the two pins

![](<.gitbook/assets/Unknown image (396)>) ![](<.gitbook/assets/Unknown image (397)>)

Jumper Off

The jumper link is removed or

“

parked

” on one pin.

![](<.gitbook/assets/Unknown image (398)>)

## Features

###  LED Indicator

In Normal operation mode, the Blue LED will not light up except in the following situations:

 When the PIR Camera is low in battery, every time it transmits a detected movement, the Blue LED will flash for 2 seconds.

 When the cover is opened and the tamper switch is violated, the Blue LED will flash for 2 seconds to indicate the device is transmitting “Tamper” signals.

 When the Tamper condition persists, every time it transmits a detected movement, the Blue LED will flash for 2

seconds.

 When PIR Camera enters Test Mode, the Blue LED will flash for 1 second. During Test mode, the Blue LED will also flash for 2 seconds every time a movement is detected.

 When the PIR Camera is in 30-second warm-up period, the Blue LED will flash slowly.

 When the PIR Camera is transmitting captured images under fault conditions (low battery, tamper switch activated, etc.), the Blue LED will flash continuously.

The LED will not flash if the PIR Camera’s tamper and battery are normal and is not under test mode,

If the LED flashes to indicate signal transmission, it will flash twice rapidly upon receiving acknowledgement from the control panel.

###  Image Capture

When the alarm system is armed, the PIR Camera will capture 1, 3 or 6 alarm images in 640 x 480 or 320 x 240 resolutions (programmable from Control Panel) upon movement detection. You can also manually request the PIR Camera to take a picture through the Control Panel. The captured images will be transferred to the Control Panel for users to view.

####

 If your PIR Camera is installed at a location where the camera’s field of view is a complex environment with intense light or lots of colors, the images captured will be great in file size, possibly leading to truncation when the images are transmitted to the Control Panel.

###  Warm Up Period

When the Control Panel system enters arm mode, or when PIR Camera is put into Test Mode, the PIR Camera will warm up for 30 seconds. During the 30-second warm up period, the PIR Camera will not be activated. The Blue LED will slow flash during the warm up period only when PIR enters for Test Mode.

###  Sleep Timer

The PIR Camera has a “sleep time” of approximately 1 minute to conserve power. After transmitting for a detected movement, the PIR Camera will not retransmit for 1 minute. Any detected movement during this period will reset the sleep time to 1 minute. Continuous movement in front of the PIR Camera will therefore not exhaust the battery.

###  Battery and Low Battery Detection

The PIR Camera uses three CR123A 3V lithium batteries in series connection as its power source. Remove the Battery Compartment Cover and insert the batteries to activate the PIR Camera.

The PIR Camera features Low Battery Detection. When the battery voltage is low, the PIR Camera will transmit a low-battery signal to the Control Panel. If movement is detected under the low-battery condition, the Blue LED will flash for 2 seconds.

When changing the batteries, after removing the old batteries, press the Tamper Switch or the Function Button twice to fully discharge before inserting new batteries.

###  Tamper Protection

The PIR Camera is protected by a tamper switch which is depressed when the PIR Camera is properly installed. When the PIR Camera is removed from the mounting surface or its cover is opened, the tamper switch will be activated and the PIR Camera will send a tamper open signal to the system control panel to remind the user of the condition. If movement is detected when the tamper switch is open, the Blue LED will flash for 2 seconds.

###  Supervision

The PIR Camera will conduct a self-test periodically by transmitting a supervisory signal once every 15 to 18 minutes.

###  Test Mode

 Test mode is for you to check the PIR camera’s detection range (not shooting coverage).

 Press the Function button once to enter Test mode for 3 minutes; the Blue LED will flash for 1 second.

 The PIR camera will warm up for 30 seconds. Please do not trigger the Camera during this warming-up period.

 After the warm-up period, you can trigger the PIR camera to check IR detection range. If the PIR camera is triggered, the Blue LED will flash for 2 seconds.

###  Learning

 Remove the Battery Compartment Cover by unscrewing the Battery Compartment Screw.

 Insert the batteries. Orient the battery according to the polarity indication.

 Put the Control Panel into learning mode (refer to the Control Panel’s manual for details).

 Press and hold the function button for 3 seconds and release the button when the Blue LED lights up; the Blue LED will light up for 25 seconds in learning mode. Add the PIR Camera into the Control Panel during this period (refer to your Control Panel’s manual to finish learn in process). If the PIR is successfully added into the Control Panel, the Blue LED will flash 6 times to indicate. If the PIR is not added within 25 seconds, please repeat learning process.

####

![](<.gitbook/assets/Unknown image (399)>) ![](<.gitbook/assets/Unknown image (400)>)

####  If the PIR Camera already exists in a Control Panel system, you will need to first remove the PIR Camera from the Control Panel before you can learn it into a different Control Panel.

 When learning the PIR Camera into a repeater/router, please press the function button once (instead of pressing and holding it for 3 seconds) to send a learn code.

###  Walk Test

 After the PIR Camera is learnt-in, put the Control Panel into “Walk Test” mode; hold the PIR Camera at the desired location and press the Function Button to confirm whether this location is within the signal range of the Control Panel (refer to the Control Panel’s manual to complete Walk Test).

 When you are satisfied that the PIR Camera works at the chosen location, you can proceed to mounting.

###  Edit PIR Camera Operation Area

 Follow instructions below to change PIR Camera Area in the Control Panel:

1. Use the panel’s Edit Device function to change PIR Camera area setting.
2. ![](<.gitbook/assets/Unknown image (401)>)Press and hold the Test button for 3 seconds on the PIR Camera to send a signal to the panel, and then release the button when the LED lights up.

###  Pet Immunity Function

The PIR sensor supports pet immunity feature and will not detect pets up to 25 kg to minimize false alarm situations.

The Pet Immunity function can be enabled/disabled by setting the Jumper Switch (JP3) position. When the Jumper Switch (JP3) is set to ON, Pet Immunity is disabled. When the Jumper Switch (JP3) is set to OFF, Pet Immunity is enabled (Factory default). The pet immunity function can also be adjusted by remote setting as described below.

###  Sensitivity Increaser Function

You can use the sensitivity increaser function to increase the PIR’s detection sensitivity. To increase detection sensitivity, set the Jumper Switch (JP4) to ON. To maintain normal detection sensitivity, set the Jumper Switch (JP4) to OFF (Factory default). The sensitivity increaser function can also be adjusted by remote setting as described below.

###  Remote Setting

 The PIR camera supports remote setting of pet Immunity and sensitivity.

 When the PIR camera is powered on, its pet immunity function and sensitivity are determined by the JP3 and JP4 settings. Users can either adjust jumper settings or remotely change the pet immunity and sensitivity settings from the Control Panel. Remote setting will overwrite jumper settings.

Control Panel Webpage:

1. On the Panel local webpage, go to the Edit Device page, input the PIR Camera configuration in the Sensor Setting section. Click OK to confirm.

Please refer to the table below for configuration details. For example, if you want to disable Pet Immunity and set Sensitivity level to normal level, you can input 01.

| IR Configuration | Pet Immunity | Sensitivity |
| ---------------- | ------------ | ----------- |
| 00               | No           | High        |
| 01               | No           | Normal      |
| 02               | Yes          | High        |
| 03               | Yes          | Normal      |

1. Press the function button once on the PIR Camera to send a signal to the Control Panel, new settings will be applied immediately. If the button is not pressed, new settings will be applied upon next signal transmission, e.g. supervision signal or IR trigger signal.

Home Portal Server:

1. On Home Portal Server, go to the Device setting page, click the VST-892-IL-ADC2 device row and select “IR Configuration.”
2. Select the Pet Immunity function (Enable/Disable) and Sensitivity (High/Normal) from the drop-down lists, click “Submit” to confirm setting.
3. Press the function button once on the PIR Camera to send a signal to the Control Panel, new settings will be applied immediately. If the button is not pressed, new settings will be applied upon next signal transmission, e.g., transmission of supervision signals or IR trigger signals.

###  Proximity Detection

 VST-892-IL-ADC2 has a digital proximity detector that can detect any masking (blocking) attempt by an intruder.

 When a masking event is detected, and the masking condition lasts for 2 minutes, VST-892-IL-ADC2 will send tamper open signal to the Control Panel to notify user of the condition.

 After masking/blocking is removed for 2 minutes, VST-892-IL-ADC2 will send tamper restore signal to the Control Panel.

## Installation

###  Installation Guideline

 The PIR Camera is designed to be mounted on either a flat surface or in a corner with the fixing screws and wall plugs provided.

 The base has knockouts, where the plastic is thinner, for mounting purpose. Two knockouts are for surface fixing and a triangular mounting bracket is used for corner fixing.

 The detection range is up to 12 meters if the PIR Camera is mounted at a height of 2.3-2.5 meters above the ground.

 When Pet-Immunity function is enabled, it will not detect pets up to 25kg when mounted at a height of 2.3-2.5 meters above the ground. If required, you can adjust the height of the PIR Camera according to the size of your pet for optimal pet immune performance. Higher installation location will provide larger pet-immune space, but also increases the blind spot under the PIR Camera.

 When VST-892-IL-ADC2 is mounted with rotating bracket, it will not have the regular detection area (as in the diagram), or the typical pet immune range.

It is recommended to install the PIR Camera in the following locations:

|  | At a position where the animals cannot come to the detection area by climbing on furniture or other objects. |
| - | ------------------------------------------------------------------------------------------------------------ |
|  | Don’t aim the device at stairways on which the animals can climb.                                            |
|  | At a position such that an intruder would normally move across the PIR’s field of view.                      |
|  | At a height between 2.3 and 2.5 meters above the ground for best performance.                                |
|  | In a corner to give the widest view.                                                                         |
|  | At a position where its field of view will not be obstructed by, e.g., curtains, ornaments etc.              |

 Limitations

|  | Do not install outdoors.![](<.gitbook/assets/Unknown image (402)>)                                                                                                                          |  | Avoid large obstacles in the detection area.![](<.gitbook/assets/Unknown image (403)>)                                                           |
| - | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | - | ------------------------------------------------------------------------------------------------------------------------------------------------ |
|  | Do not expose the PIR completely to direct sunlight.![](<.gitbook/assets/Unknown image (404)>)                                                                                              |  | Avoid vapor or high humidity that can cause condensation.![](<.gitbook/assets/Unknown image (405)>)                                              |
|  | Avoid moving objects, e.g., curtains, wall hangings, etc., in the detection area.![](<.gitbook/assets/Unknown image (406)>)                                                                 |  | Avoid reflected light from bright surfaces, e.g., mirrors, windows, etc.![](<.gitbook/assets/Unknown image (407)>)                               |
|  | Avoid installing the PIR in areas where machines such as air conditioners or heaters may cause rapid change in temperature in the detection area.![](<.gitbook/assets/Unknown image (408)>) |  | Avoid reflecting surface in the detection area. Reflected infrared signatures may lead to false alarm.![](<.gitbook/assets/Unknown image (409)>) |

 Be sure to always remain the RSSI signal strength steady at “4”.



![](<.gitbook/assets/Unknown image (410)>) ![](<.gitbook/assets/Unknown image (411)>)

VST-892-IL-ADC2 Detection Range

|  | The PIR Camera is designed to be mounted on either a flat surface or in a corner with the fixing screws and wall plugs provided.                                                                                                                        |
| - | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
|  | For corner mounting, a triangular bracket is provided to add Back Tamper Protection. The bracket includes knockouts to mount it on the wall.                                                                                                            |
|  | For surface mounting, an optional rotating bracket is provided for users to adjust the range of detection. With the rotating bracket, the VST-892-IL-ADC2 can be rotated 80 degrees horizontally and 70 degrees vertically to provide optimal coverage. |

####  Corner mounting with the triangular bracket

1. 4 knockouts are made on the triangular bracket. To fix the bracket on the Wall A, break through Knockout A & B. To fix the bracket on Wall B, break through Knockout C & D. To fix the bracket on both of Wall A & B, break through Knockout A & D or B & C.
2. Use the holes as a template and drill holes on the corner surface.
3. Insert the wall plugs if the PIR camera is to be mounted on plaster or brick.
4. Screw the triangular bracket onto the wall plugs with the two pointing sticks (E) on top and facing you.
5. Fit the PIR Camera onto the hooks of the triangular bracket.

![](<.gitbook/assets/Unknown image (412)>)

####  Surface mounting

1. Separate the cover and the base by loosening the bottom fixing screw with a Phillips screwdriver.
2. ![](<.gitbook/assets/Unknown image (413)>)Break through the 2 Surface knockouts from the inside of the base.
3. Use the holes as a template and drill holes into the mounting surface.
4. Insert the wall plugs if the PIR is to be fixed onto plaster or brick.
5. Screw the base onto the wall plugs.
6. Secure the cover back to the base by tightening the bottom fixing screw.

####  Surface mounting with rotating bracket (optional item, sold separately)

The rotating bracket can be mounted on the wall with the screws provided.

1. Screw the rotating bracket onto the wall.
2. Fit the PIR onto the 3 hooks of the rotating bracket.
3. Rotate the bracket for the proper range of detection and tighten the fixing screw.

![](<.gitbook/assets/Unknown image (414)>)
