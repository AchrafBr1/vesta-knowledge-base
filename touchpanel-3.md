# VESTA-425

TouchPanel 3

## Qallmax - Touch-Screen Intrusion panel&#x20;

<figure><img src=".gitbook/assets/image (6) (1) (1) (1).png" alt=""><figcaption></figcaption></figure>

## 1. Introduction

TouchPanel-3 uses modern, intuitive user interface on a 7” full-color, high-resolution display, providing users quick access to security and smart home functions, as well as a quick on-screen control of all areas.

As an IP-based multifunctional RF, Z-Wave smart home gateway with WiFi, 4G/LTE, and Bluetooth capabilities, TouchPanel-3 provides comprehensive solutions, including home security, visual verification, home automation, energy management, emergency monitoring, and remote management, for ultra-flexibility and convenience.

Moreover, TouchPanel-3 features two-way hands-free communication through the built-in speaker and microphone.

Other innovative features include Bluetooth disarming, which allows users to conveniently disarm the security system even with their hands full. The face detection function enables the front camera to take photos when someone disarms the system, providing the basis for algorithm analysis to prevent potential harms.

#### System Feature

* **Two-way voice communication with VOIP and 4G/LTE**: Built-in microphone and speaker allows user to make hands-free voice call in case of emergency.

Additionally, TouchPanel-3 automatically answers a callback call during callback timer.

* **Ethernet, WiFi, and/or 4G/LTE connection**:

The system can be connected through Ethernet, WiFi, or 4G/LTE. When all the three connection methods are available, the Panel prioritizes its connections in the following order: Ethernet > WiFi > 4G/LTE.

WiFi connection provides backup to Ethernet to extend system flexibility.

* **Voice Prompt Reminder**: The panel plays voice prompts upon system mode change to remind user the system status.
* **AI Recognition for alarm pictures:** The panel incorporates an AI (Artificial Intelligence) algorithm for recognizing whether an alarm image contains a person. Alarm images, along with the AI detection results, are transmitted to the CMS, enabling the CMS to prioritize the new alarm queue based on this AI detection.
* **Screen Timeout**: By default, the screen of TouchPanel-3 will automatically turn off after 5 minutes of inactivity. Tap anywhere on the screen to turn it on.

The user can also select the screen timeout period in Settings. If "Never" is selected, the screen will always stay on. Please refer to _**5. Settings**_.

* **Built-in accessory device**:

TSP-Cam: The panel features a built-in Camera, extra Cameras may be included into the system to extend the coverage.

## 2. System Overview

### 2.1. Parts Identification



![Front View](<.gitbook/assets/Unknown image (122)>)

<figure><img src=".gitbook/assets/Unknown image (123)" alt=""><figcaption><p><strong>Back View</strong></p></figcaption></figure>

<figure><img src=".gitbook/assets/Unknown image (124)" alt=""><figcaption><p><strong>Internal View</strong></p></figcaption></figure>

<figure><img src=".gitbook/assets/Unknown image (125)" alt=""><figcaption><p><strong>Internal View</strong></p></figcaption></figure>

<table data-header-hidden><thead><tr><th width="162"></th><th></th></tr></thead><tbody><tr><td><strong>Power Button</strong></td><td><ul><li>If for some reason you need to power down or force restart the system, press the power button for <strong>2 seconds</strong> and then release to access the selection menu.</li><li>Pressing and holding the button for** 10 seconds** will force the system to shut down immediately.</li></ul></td></tr><tr><td><strong>Recovery Button</strong></td><td>- <mark style="color:red;">Reserved for Manufacturer Use Only</mark> – Do not press unless instructed by authorized personnel****</td></tr></tbody></table>

### 2.2. LED Indicators

The LED indicators are used show various system statuses.

<table data-header-hidden><thead><tr><th width="182"></th><th width="131"></th><th></th></tr></thead><tbody><tr><td><strong>LED</strong></td><td><strong>Behavior</strong></td><td><strong>System Status</strong></td></tr><tr><td><strong>White LED</strong></td><td>On</td><td>Panel Rebooting</td></tr><tr><td><strong>Green LED</strong></td><td>On</td><td>AC Power Connected</td></tr><tr><td><strong>Red LED</strong></td><td>On</td><td>AC Power Loss</td></tr><tr><td><strong>Orange LED</strong></td><td>On</td><td>System Fault</td></tr></tbody></table>

### 2.3. Power Supply

**Power Adapter**

* A DC 5 V 3 A USB-C switching power adapter is required to connect to a wall outlet. Be sure only to use an adapter with the appropriate AC voltage rating to prevent component damage.
* TouchPanel-3 will automatically turn on after AC power is supplied.

**Rechargeable Battery**

* In addition to the adapter, there is a rechargeable battery inside the Control Panel, which serves as a backup power in case of a power failure.
* During normal operation, the AC power adapter is used to supply power to the Control Panel and at the same time recharge the battery.
* When the adapter is disconnected from the Control Panel, the Red LED will turn on to indicate AC power loss.
* When the battery level is low, TouchPanel-3 will report a low battery status. If the AC power adapter is not reconnected after this report and the battery continues to drain, a warning message will appear on the user interface. If the battery becomes too low for the system to function, it will automatically shut down to protect data.

**Auxiliary Power Supply Accessory (Optional)**

* In addition to the standard power adapter, TouchPanel-3 can also be powered using one of the following optional power supplies:
  * **AUX-PS:** An AC power board that converts 100–240 VAC, 50/60 Hz input into a regulated 5 V DC / 3 A output. The AUX-PS must be connected to a wall outlet (mains socket).
  * **AUX-PS-DC:** A DC power board that converts 7-36 V DC input into a regulated 5 V DC / 3 A output. The AUX-PS-DC should be connected to a regulated DC power source (e.g., a power supply unit (PSU)).
* To use the Power Supply Accessory (AUX-PS or AUX-PS-DC):
  1. Connect the USB-C connector of the AUX-PS or AUX-PS-DC to the USB-C Port on TouchPanel-3.
  2. For **AUX-PS**, connect the two wires of the AC power cable to the power input terminals on AUX-PS, then plug the cable into a 100–240 VAC mains outlet.

![](<.gitbook/assets/Unknown image (126)>)

For **AUX-PS-DC**, connect the positive and negative output wires from a regulated DC power source (e.g., a PSU) to the V+ and V- terminals, respectively.

![](<.gitbook/assets/Unknown image (127)>)

* Refer to section **3.4. Auxiliary Power Supply Accessory**for installation instructions for AUX-PS and TouchPanel-3. The same installation process also applies to AUX-PS-DC.

## 3. Installation

### 3.1. System Deployment

The Control Panel is designed to be wall mounted, follow guidelines below when planning installation location:

* The Control Panel requires the mains power and Ethernet connection.
* If cellular network is used, ensure that there is good cellular coverage (it is advised to have a signal strength of at least 4 out of 5).
* Avoid mounting the Control Panel near large metal objects which may affect wireless radio strength.
* The Control Panel should be protected by sensors so that no intruder can reach the Control Panel without first activating a sensor.
* When using routers to extend wireless communication coverage, remember to use only Routers with backup batteries for security sensors. If you use a Router without backup battery for security sensors, the Router will be powered down in case of AC failure, and your security sensors will lose connection with the Panel.

### 3.2. Hardware Installation

**Detachment**

**1** Loosen the two bottom fixing screws to detach the front cover from the back plate.

**2** Loosen the screw securing the Rear Access Cover and remove the Access Cover.

![](<.gitbook/assets/Unknown image (128)>)

**Hardware Setup**

1. Connect an Ethernet cable to the Ethernet port.
2. (Optional) Insert a Micro-SIM card with the chip side facing down.

![](<.gitbook/assets/Unknown image (129)>)

{% hint style="warning" %}
Note:&#x20;

* Before inserting the SIM card, please make sure the pin code is deactivated and SMS messages are removed first.
* Insert the SIM Card when the Panel is powered off.
* Make sure to insert a SIM card with data plan.
{% endhint %}

3. (Optional) Connect the hardwired input and ouput to the Input & Output Terminal (see **5.2.7. Wired Device** for details).
4. Connect the battery connector to the batter connector terminal and route the wires along the lower sidewall.

![](<.gitbook/assets/Unknown image (132)>)

5. Insert the USB-C connector of the adapter to the USB-C Port on the Panel’s PCB.

If using the Power Supply Accessory (AUX-PS or AUX-PS-DC) with TouchPanel-3, please connect the USB-C connector on the accessory to the USB-C Port on the PCB.

6. Replace and secure the Rear Access Cover.
7. Route the cables through one of the wiring holes on the back plate, reattach the front cover to the back plate, then tighten the bottom fixing screws.

![](<.gitbook/assets/Unknown image (133)>)

&#x20;The above is an example of wiring. The back plate provides four breakaway sections as wiring hole options.

8. Plug the power adapter into a wall socket. The Green LED on TouchPanel-3 will turn on steadily to indicate AC power connected.

**Mounting**

TouchPanel-3 is designed to be mounted on the wall.

It is recommended to install the Panel at approximately chest height where the touchscreen can be easily accessed and operated.

1. Detach the front cover from the back plate.
2. Use the four knockouts on the back plate as a template to drill holes on the wall.
3. Insert the wall plugs, then screw the back plate onto the wall with the 4 provided screws.
4. Fit the top latching holes on the front cover onto the corresponding latches on the back plate, then push forward the front cover to close it. Tighten the 2 bottom fixing screws.

![](<.gitbook/assets/Unknown image (134)>)

***

### 3.3. Battery Replacement

**Battery Removal**

1. Disconnect the battery connector.
2. Insert a finger into the groove and pry out the battery.

![](<.gitbook/assets/Unknown image (135)>)

**Battery Installation**

1. Place a new battery into the battery compartment.
2. Connect the battery connector to the terminal. The foolproof design helps ensure correct connection.&#x20;

<figure><img src=".gitbook/assets/Unknown image (136)" alt=""><figcaption></figcaption></figure>

3. Route the wires along the lower sidewall

<figure><img src=".gitbook/assets/Unknown image (137)" alt=""><figcaption></figcaption></figure>

### 3.4. Auxiliary Power Supply Accessory (Optional)

The Power Supply Accessory (AUX-PS) includes a Speaker Cover. To install, users must first remove the original speaker cloth from TouchPanel-3, then mount both AUX-PS and the Cover onto the Panel.

**Part 1: Speaker Cloth Removal**

1. Unscrew the two bottom fixing screws and gently detach the front cover from the back plate.

![](<.gitbook/assets/Unknown image (138)>)

2. Turn over the front cover, unscrew the four corner screws and the screw securing the rear access cover, and carefully separate the back cover from the front cover.
3. Disengage the 5 latches and remove the speaker cloth.

![](<.gitbook/assets/Unknown image (139)>)

**Part 2: Panel & AUX-PS Installation**

1. Break out one of the pre-punched wiring holes, then secure the back plate to the wall.

![](<.gitbook/assets/Unknown image (140)>)

2. Loosen the two fixing screws, and separate the Speaker Cover and AUX-PS.

![](<.gitbook/assets/Unknown image (141)>) ![](<.gitbook/assets/Unknown image (142)>)

3. Route an Ethernet cable and the AUX-PS USB-C cable through the lowest wiring hole of the back plate.

**Use an Ethernet cable without the plastic housing on the RJ45 connector. Verify that both the cable and the RJ45 connector can fit through the desired wiring hole on the back plate and the AUX-PS opening.**

![](<.gitbook/assets/Unknown image (143)>) ![](<.gitbook/assets/Unknown image (144)>)

4. Connect the RJ45 connector to the Ethernet Port and the USB-C connector to Cover, then reattach the front cover to the USB-C Port on the PCB. the back plate.

![](<.gitbook/assets/Unknown image (145)>)

5. Replace and secure the Rear Access

![](<.gitbook/assets/Unknown image (146)>)

6. Route the other RJ45 connector through the AUX-PS opening, and tuck the paper card into the gap between the wall and the Panel.

![](<.gitbook/assets/Unknown image (147)>)

7. Remove the liner from the tape on the back of the paper card, stick the card to the wall to prevent slipping, then fasten the two bottom fixing screws of the Panel.

<figure><img src=".gitbook/assets/image (1) (1) (1) (1) (1) (1) (1) (1) (1) (1).png" alt=""><figcaption></figcaption></figure>

8. Fold the two flaps of the paper card outward, route the power cable through the AUX-PS opening, and connect power cable through the AUX-PS opening, and connect and secure the two cable wires to the AUX-PS terminals.

<figure><img src=".gitbook/assets/image (2) (1) (1) (1) (1) (1) (1) (1).png" alt=""><figcaption><p>8                                                                                                            9</p></figcaption></figure>

9. **Firmly press AUX - PS against** TouchPanel-3, then use the two holes on AUX-PS as a template to mark and drill two screw holes into the wall.&#x20;

![](<.gitbook/assets/Unknown image (151)>)

10. While firmly pressing AUX-PS against TouchPanel-3 and the wall, apply two screw to the drilled holes to ensure precise attachment.

![](<.gitbook/assets/Unknown image (153)>)

11. Attach the Speaker Cover to AUX-PS and TouchPanel-3, then fasten the two fixing screws.

![](<.gitbook/assets/Unknown image (152)>)

12. Tear and remove the paper card from the wall.

_Tear and remove it carefully when taking it off a painted wall._

<figure><img src=".gitbook/assets/Unknown image (154)" alt="" width="375"><figcaption></figcaption></figure>

## 4. Operation

On the user interface of TouchPanel-3, users can change the system mode, control automation devices, edit and bypass devices, and access videos or captured images. The five main pages,

Home, Security, Automation, Cam and Events can be selected from the bottom of the screen

### 4.1. Home

By default, the screen automatically switches between day and night modes at 6 a.m. and 6 p.m."

![Day Mode](<.gitbook/assets/Unknown image (155)>) ![Day Mode](<.gitbook/assets/Unknown image (156)>)

* **Date, Time and Weather**: The Home page displays current Date, Time and Weather info. Select the Weather info to see weather forecast.

![](<.gitbook/assets/Unknown image (157)>) ![](<.gitbook/assets/Unknown image (158)>)

* **Home Widget**: The Home Widget list is for you to control or check current status of the

HVAC sensors or devices which have been learned into the system. To set the list:

**Step 1** Tap the Home Widget icon. Check the devices that you are going to display on the list.

Up to six devices can be displayed here. Tap OK to confirm.

![](<.gitbook/assets/Unknown image (159)>)

**Step 2** The devices that you selected are displayed on the widget list.

Tap the widget that you want to check. When there is a fault or supervision failure, an orange exclamation mark icon will be displayed on the widget. The color of the widget will also fade.

![](<.gitbook/assets/Unknown image (160)>)

### **4.2. Security**

The Security page displays current system mode for quick control access.

<figure><img src=".gitbook/assets/image (3) (1) (1) (1) (1) (1).png" alt=""><figcaption></figcaption></figure>

![](<.gitbook/assets/Unknown image (162)>)

<table data-header-hidden><thead><tr><th width="162"></th><th width="164" align="center"></th><th></th></tr></thead><tbody><tr><td><strong>Section</strong></td><td align="center"><strong>Icon</strong></td><td><strong>Description</strong></td></tr><tr><td><p><strong>1. Internet</strong></p><p><strong>Indicator</strong></p></td><td align="center"><img src=".gitbook/assets/Unknown image (163)" alt=""></td><td>When the Ethernet is connected</td></tr><tr><td></td><td align="center"><img src=".gitbook/assets/Unknown image (164)" alt="" data-size="original"></td><td>When WiFi is connected <img src=".gitbook/assets/Unknown image (165)" alt="" data-size="line"> (Strong – Weak)</td></tr><tr><td></td><td align="center"><img src=".gitbook/assets/Unknown image (166)" alt="" data-size="original"><br></td><td>When cellular network is connected <img src=".gitbook/assets/image (4) (1) (1) (1) (1).png" alt=""> (Strong - Weak)</td></tr><tr><td></td><td align="center"><br><img src=".gitbook/assets/image (7) (1) (1) (1).png" alt=""></td><td>Internet is disconnected</td></tr><tr><td></td><td align="center"><strong>Note</strong></td><td>The panel supports Ethernet, Wi-Fi, and LTE. If all are available, it will prioritize in this order: Ethernet > Wi-Fi > LTE.</td></tr><tr><td><strong>2. Ongoing call</strong></td><td align="center"><img src=".gitbook/assets/Unknown image (162)" alt=""></td><td>During 2-way communication, the call icon will be displayed.****</td></tr><tr><td><strong>3. Power</strong></td><td align="center"><img src=".gitbook/assets/Unknown image (168)" alt=""></td><td>When powered by AC, a plug icon will be displayed.</td></tr><tr><td></td><td align="center"><div><figure><img src=".gitbook/assets/image (6) (1) (1) (1) (1).png" alt="" width="42"><figcaption></figcaption></figure></div></td><td>When powered by the backup battery, the battery percentage will be displayed.</td></tr><tr><td><strong>4. Setting</strong></td><td align="center"><img src=".gitbook/assets/Unknown image (170)" alt=""></td><td>Tap the gear icon to access the Settings menu. Please refer to later section <em><strong>5. Settings</strong></em>.</td></tr><tr><td><strong>5. Date, Time, and Weather</strong></td><td align="center">---</td><td>Display current date and time.</td></tr><tr><td><strong>6. Area</strong></td><td align="center">---</td><td>Tap the area to select the Area to be displayed.</td></tr><tr><td><p><strong>7. System</strong></p><p><strong>Mode</strong></p></td><td align="center"></td><td>Disarm,             Away Arm,            Home Arm<img src=".gitbook/assets/Unknown image (171)" alt=""><img src=".gitbook/assets/Unknown image (172)" alt=""><img src=".gitbook/assets/Unknown image (173)" alt=""></td></tr><tr><td><strong>8. SOS Button</strong></td><td align="center"><img src=".gitbook/assets/Unknown image (174)" alt=""></td><td>Press and hold the SOS button for 3 seconds to activate an Emergency alarm.</td></tr><tr><td><strong>9. Panel Status</strong></td><td align="center"><img src=".gitbook/assets/Unknown image (175)" alt=""></td><td>When Fault event exists within the panel, a number will be displayed over the icon. Tap the icon to view the fault events.</td></tr><tr><td><p><strong>10. Door</strong></p><p><strong>Contact</strong></p></td><td align="center"><img src=".gitbook/assets/Unknown image (176)" alt=""></td><td>The total number of Door Contacts in the alarm system will be displayed. When Fault event exists within the Door Contacts, a number will be displayed over the icon. Tap the icon to view the fault events.</td></tr><tr><td><p><strong>11. Device</strong></p><p><strong>Status</strong></p></td><td align="center"><img src=".gitbook/assets/Unknown image (177)" alt=""></td><td>The total number of non-Door Contact sensors in the alarm system will be displayed. When Fault event exists within the devices, a number will be displayed over the icon. Tap the icon to view the fault events.</td></tr></tbody></table>

#### **4.2.1. Change System Mode**

* Select the area you wish to control, then tap the mode icon to change mode.&#x20;

![ Home arm                                 Disarm                                Away Arm](<.gitbook/assets/Unknown image (178)>)

You will be required to enter one of the Control Panel User PIN Code to confirm the action.

The panel will play voice prompts upon system mode change to remind user the system status. Please refer to _**6. Voice Prompts**_ for details.

![](<.gitbook/assets/Unknown image (179)>)

If incorrect PIN Code is entered, TouchPanel-3 will display error message and arming will be aborted.

![](<.gitbook/assets/Unknown image (180)>)

* When Arm Fault Type is set as Confirm, and the system has existing faults when arming, a fault message will appear. If you still want to arm the system, you will need to bypass the faults on the fault list first or repeat the arming action within 30 seconds to Force Arm.

![](<.gitbook/assets/Unknown image (181)>)

By checking all faults and tapping **Bypass**, the faults will be bypassed and the system will be armed.

![](<.gitbook/assets/Unknown image (182)>)

**Face Detection**

When the Face Detection feature is turned on, the system must detect a face to disarm the system, adding an extra layer of protection. Please refer to _**5.1. Face Detection**_ to turn on the feature.\*\*\*\*

* When **Disarm** is tapped, the following dialog box will be displayed, requesting the user to position his/her face in the camera frame to activate pin entering for disarming.

<figure><img src=".gitbook/assets/Unknown image (183)" alt=""><figcaption></figcaption></figure>

* The Panel will auto capture a photo when a face is detected and display the captured image for 3 seconds.
* After 3 seconds, the panel will display PIN code page with disarm icon. Enter the user PIN code to disarm the system.

![](<.gitbook/assets/Unknown image (184)>)

* Whether disarming is completed or aborted, the captured face will be reported and displayed in the event log.

#### **4.2.2. Alarm Dashboard**

When there is an alarm, the Alarm dashboard will be displayed:

![](<.gitbook/assets/Unknown image (185)>)

* **Area**: It will be indicated that the alarm is occurred in which area. When there are alarms in both areas, you can tap the icon to view the alarm list for each area respectively.
* **Alarm list**: The devices that have been triggered will be displayed here.
* **Disarm**: Tap the icon and then enter the PIN code to disarm the system.

![](<.gitbook/assets/Unknown image (184)>)

After disarming the system, you can view these events again through the list. Tap the Close icon to close the alarm dashboard and go back to Security page.

![](<.gitbook/assets/Unknown image (186)>)

### **4.3. Automation**

The Automation page provides access to home automation functions in the Control Panel. The Automation page includes Scene, Room, Group, Device, and Rule.

![](<.gitbook/assets/Unknown image (187)>)

#### **4.3.1. Scene**

The Scene subpage allows you to set a group of actions which the Control Panel may perform with its Home Automation devices. The user can program the Scene to manually activate a set of devices, or automatically activate them by pre-programmed Rule. \*\*\*\*

![](<.gitbook/assets/Unknown image (188)>)

* Create a New Scene.

**Step 1** Tap the **+** icon to access Add Scene menu.

**Step 2** Enter your Scene Name.

**Step 3** Choose a desired Action Type from the drop-down menu. The options available are dependent upon learnt device(s) in the Control Panel and up to 5 actions can be associated with each scene.

* Device Action: To toggle on/off, switch on/on for/on until/off, open, or close a device in specified zone.
* Group Control: The Group function allows the user to control the same type of devices.
* Change Mode: The system will change to the disarm/full arm/home arm mode as specified.
* SD LED Control: To switch on / off the Smoke detector LED.
* IP Cam Request Media: The IP Camera in specified zone will record a video.
* IP Cam Request Media (All): All IP Cameras in the system will record a video.
* Request Image: The PIR Camera in specified zone will take a picture.
* Request Image (All): All PIR Cameras in the system will take a picture.
* Request Image (No flash): The PIR Camera in specified zone will take a picture without activating its LED flash.
* Request Image (All, No flash): All PIR Cameras in the system will take a picture without activating its LED flash.
* Change Internal Memory Status: To change Internal Memory Status (True / False).

**Step 4** You can create a new Action type by tapping the **+** icon. To remove an existing Action

type, simply tap the icon. ![](<.gitbook/assets/image (411).png>)

![](<.gitbook/assets/Unknown image (191)>)

**Step 5** Tap **Save** to confirm scene setting. The Scene page will be updated with the new Scene.

* Delete a Scene

To remove an existing Scene, simply tap the icon. <img src=".gitbook/assets/image (412).png" alt="" data-size="line">

<figure><img src=".gitbook/assets/image (413).png" alt=""><figcaption></figcaption></figure>

* Apply Scene

You can tap the icon ![](<.gitbook/assets/image (414).png>) after the scene name to manually execute a scene’s action. You may

apply 1 Scene at most each time.

<figure><img src=".gitbook/assets/image (415).png" alt=""><figcaption></figcaption></figure>

* Edit Scene

To edit an existing scene, tap the ![](<.gitbook/assets/Unknown image (196)>) icon to view scene content.

<figure><img src=".gitbook/assets/image (416).png" alt=""><figcaption></figcaption></figure>

#### **4.3.2. Room**

The Room subpage allows you to associate several sensors to create one Room. This feature provides a hassle-free way if you wish to turn a light on in the living room. You will not end up turning on a light in the kitchen by mistake. Each device can only be assigned to one Room.

![](<.gitbook/assets/Unknown image (198)>)

You can create more rooms by tapping the **+** icon at top right.

* Up to 20 Rooms can be created.
* Enter the Room name in Name field for identification.
* You can assign Home Automation Devices to each room to monitor and control them.

<figure><img src=".gitbook/assets/image (417).png" alt=""><figcaption></figcaption></figure>

#### **4.3.3. Group**

The Group function allows the user to control the same type of devices. The user can control over 6 types of devices, including Switch, Dimmer, Hue, Shutter, Radiator, and Thermostat. Up to 10 subgroups can be created under each type.

![](<.gitbook/assets/Unknown image (42)>)

* **Switch**

Tap ![](<.gitbook/assets/image (418).png>) to turn on/off Switch of each Group. To add/delete a group, tap ![](<.gitbook/assets/image (419).png>). To view details, add/remove a device or rename a group, tap ![](<.gitbook/assets/image (420).png>)

<figure><img src=".gitbook/assets/image (421).png" alt=""><figcaption></figcaption></figure>

<figure><img src=".gitbook/assets/image (422).png" alt=""><figcaption></figcaption></figure>

* **Dimmer**

Tap ![](<.gitbook/assets/image (423).png>) to control Dimmer of each group. To view details, control a group, add/remove a

device, or rename a group, tap ![](<.gitbook/assets/image (424).png>)

<figure><img src=".gitbook/assets/image (425).png" alt=""><figcaption></figcaption></figure>

In the Group Control page, the user can change the brightness of the devices by adjusting the bar.

![](<.gitbook/assets/Unknown image (51)>)

![](<.gitbook/assets/Unknown image (52)>)

* **HUE Bulb**

Tap ![](<.gitbook/assets/image (426).png>)  to control Hue of bulbs in each group. To view details, control a group, add/remove a device, or rename a group, tap ![](<.gitbook/assets/image (427).png>)

<figure><img src=".gitbook/assets/image (428).png" alt=""><figcaption></figcaption></figure>

In the Group Control page, the user can control Hue by adjusting the bar or tap Color, Whites, or Preset to change the color of devices in a preset group.

![](<.gitbook/assets/Unknown image (55)>)

![](<.gitbook/assets/Unknown image (56)>)

***

**Color**: Tap the color directly to set the group with your desired color.

**Whites**: Tap the color directly to set the group with your desired color temperature.&#x20;

**Preset**: Tap the color directly to set the group with the preset certain color.

* **Shutter**

Tap ![](<.gitbook/assets/image (429).png>) to control Shutter of each group. To view details, control a group, add/remove a device or rename a group, tap ![](<.gitbook/assets/image (430).png>)

<figure><img src=".gitbook/assets/image (431).png" alt=""><figcaption></figcaption></figure>

In the Group Control page, the user can control the shutters at a desired level by adjusting the bar.

<figure><img src=".gitbook/assets/Unknown image (59)" alt=""><figcaption></figcaption></figure>

<figure><img src=".gitbook/assets/Unknown image (60)" alt=""><figcaption></figcaption></figure>

* **Radiator**

Tap ![](<.gitbook/assets/image (432).png>) to turn on/off Radiator of each group. To view details, control a group, add/remove a device or rename a group, tap ![](<.gitbook/assets/image (433).png>)

<figure><img src=".gitbook/assets/image (434).png" alt=""><figcaption></figcaption></figure>

In the Group Control page, the user can control the radiator by adjusting the bar. The mode set points are displayed on the bar. Toggle the bar to increase or decrease the mode set points.

<figure><img src=".gitbook/assets/Unknown image (63)" alt=""><figcaption></figcaption></figure>

<figure><img src=".gitbook/assets/Unknown image (64)" alt=""><figcaption></figcaption></figure>

* **Thermostat**

Tap ![](<.gitbook/assets/image (435).png>)  to turn on/off Thermostat of each group. To view details, control a group, add/remove

a device or rename a group, tap ![](<.gitbook/assets/image (436).png>)

<figure><img src=".gitbook/assets/image (437).png" alt=""><figcaption></figcaption></figure>

In the Group Control page, the user can check the list of devices and toggle 2 bars to increase or decrease the mode set points. Tap Auto, Cool, Heat, or Away button to change the modes.

![](<.gitbook/assets/Unknown image (67)>)

![](<.gitbook/assets/Unknown image (68)>)

#### **4.3.4. Device**

The device page lists all available devices which can be displayed according to different categories.

Select device category from the dropdown menu on the top right corner to determine the devices to be displayed.

![](<.gitbook/assets/Unknown image (69)>)

<table data-header-hidden><thead><tr><th width="80"></th><th width="64"></th><th width="82"></th><th width="79"></th><th width="64"></th><th width="67"></th><th width="52"></th><th width="119"></th><th></th><th></th></tr></thead><tbody><tr><td><strong>Device Status</strong></td><td>Fault</td><td>Low Battery</td><td>Bypass</td><td>RSSI </td><td>Level</td><td></td><td>Entry Delay Time</td><td>Wired Device</td><td></td></tr><tr><td><strong>Icon</strong></td><td><img src=".gitbook/assets/Unknown image (70)" alt=""></td><td><img src=".gitbook/assets/Unknown image (71)" alt=""></td><td><img src=".gitbook/assets/Unknown image (72)" alt=""></td><td><img src=".gitbook/assets/Unknown image (73)" alt=""> 1-3</td><td><img src=".gitbook/assets/Unknown image (74)" alt=""> 4-6</td><td><img src=".gitbook/assets/Unknown image (75)" alt=""> 7-9</td><td><div><figure><img src=".gitbook/assets/image (439).png" alt=""><figcaption></figcaption></figure></div></td><td><div><figure><img src=".gitbook/assets/image (438).png" alt=""><figcaption></figcaption></figure></div></td><td><div><figure><img src=".gitbook/assets/image (440).png" alt=""><figcaption></figcaption></figure></div></td></tr></tbody></table>

* Categories: All, Fault, DC Open, Sensors, Automation Device, Keypad, Door Sensor, Siren.
* The device list displays device information:
  * Device Status will be displayed in each device column.
  * Current on/off conditions will be shown for switch devices.
  * Current wattage and accumulated power consumption will be displayed for power    \
    switches with meters.
  * Current power output level will be displayed for dimmers.
  * Temperature and humidity will be displayed for temperature and humidity sensors.
* Use the device column to control each device or check detailed information.
  * For Camera type security devices, e.g., PIR Camera, you can tap the camera icon <img src=".gitbook/assets/Unknown image (76)" alt="" data-size="line"> at the end of device column to manual control the camera to take a picture. The requested image will be displayed in the event page.
  * For Switches or Locks, tap the ON/OFF or LOCK/UNLOCK icon <img src=".gitbook/assets/Unknown image (77)" alt="" data-size="line"> to toggle its status.
  * For Dimmers, either tap the ON/OFF icon to toggle or tap the bar to adjust the output percentage.
  * For the devices with more detailed data or control options, tap the icon ![](<.gitbook/assets/image (436).png>)  to enter the device’s own page.&#x20;

![](<.gitbook/assets/Unknown image (79)>) ![](<.gitbook/assets/Unknown image (80)>)

#### **4.3.5. Rule**

The Rule page allows you to set up rules to automate actions based on specific triggers, such as turning on heating when the temperature drops below a certain degree.

Additionally, each rule can include optional conditions, such as the panel being in disarmed mode or within a specified time frame (e.g., 6:00 p.m. to 10:00 p.m.), to further refine when the rule should be activated.

You can also select the action type to be performed, or simply apply the scene previously created under the Scene subpage.

Input the “Master Code (default: 1111)” to enter the Rule setting page.

![](<.gitbook/assets/Unknown image (81)>)

**Step 1** Tap the **+** icon to create a new rule.

***

![](<.gitbook/assets/Unknown image (82)>)

**Step 2** You can enter up to 31 characters as your Rule Name.

**Step 3** To set up a Rule, choosing a Trigger Type from the drop-down menu is indispensable. Up to 25 trigger types are available. The options available are dependent upon learnt device(s) in the Control Panel and 1 trigger type can be associated with each rule.

![](<.gitbook/assets/Unknown image (83)>)

* Mode Change: The system will change to the disarm/full arm/home arm mode as specified.
* Mode Change and Exit Timer Stopped: When the system changes to the mode as specified and Exit Timer expires, the rule will be activated according to rule condition and execution setting.
* Mode Change and Entry Timer Start: When the system begins to countdown Entry Delay, the rule will be activated according to rule condition and execution setting.
* DC Open: When the Door Contact is open in specified zone.
* DC Closed: When the Door Contact is closed in specified zone.
* DC Open for a While: When the Door Contact is open for a preset duration in specified zone.
* DC Closed for a While: When the Door Contact is closed for a preset duration in specified zone.
* Motion Detected: When movements are detected by Motion Sensor in specified zone, the rule will be activated according to rule condition and execution setting. (SVGS Glass break Sensor supports Motion Detected as a rule trigger).
* Motion Restored: When movements detected by Motion Sensor in specified zone become static, the rule will be activated according to rule condition and execution setting.
* Scene Button Pressed: When the Scene Button is pressed to activate sensors in specified zone.
* Trigger Alarm: Choose to activate a specified Alarm Sensor in specified zone.
* Schedule: The system will follow the schedule time to respond accordingly.
* Temperature Above: If the temperature detected by specified temperature sensor exceeds the set threshold, the rule will be activated according to rule condition and execution setting.
* Temperature Below: If the temperature detected by specified temperature sensor drops below the set threshold, the rule will be activated according to rule condition and execution setting.
* Humidity Above: If the humidity reading from specified room sensor rises above the level specified, the rule will be activated according to rule condition and execution setting.
* Humidity Below: If the humidity reading from specified room sensor falls below the level specified, the rule will be activated according to rule condition and execution setting.
* Lux Above: If the lux reading from specified light sensor rises above the level specified, the rule will be activated according to rule condition and execution setting.
* Lux Below: If the lux reading from specified light sensor falls below the level specified, the rule will be activated according to rule condition and execution setting.
* Power Consumption Above: If the power output watt from a specified Power Switch exceeds set threshold, the rule will be activated according to rule condition and execution setting.
* Air Quality Index: If the Air Quality Index from specified air quality sensor rises above the level specified, the rule will be activated according to rule condition and execution setting.
* Air Quality CO2: If the CO2 reading from specified air quality sensor rises above the level specified, the rule will be activated according to rule condition and execution setting.
* DI/DO(DI) Opened: When the loop opens, the terminal will activate sensor in specified zone.
* DI/DO(DI) Closed: When the loop closes, the terminal will activate sensor in specified zone.
* DIO52(DI) Status for 0: Users can select input action type. This indicates the device is inactive.
* DIO52(DI) Status for 1: Users can select input action type. This indicates the device is active.

**Step 4** Choose a desired Condition Type (optional) from the dropdown menu. The options available are dependent upon learnt device(s) in your Control Panel. \*\*\*\*

* None: Set up a Rule without choosing any condition.
* Mode: The system will change to the disarm/full arm/home arm mode as specified.
* Temperature Range: If the temperature detected by specified temperature sensor falls/rises within the range specified, the rule will be activated according to rule condition and execution setting.
* Lux Level Range: If the lux reading from specified light sensor falls below the level specified, the rule will be activated according to rule condition and execution setting.
* Time Period: The system will follow the schedule time to respond accordingly.
* Alarm: Users can specify the rule to perform the action when a trigger is detected AND

an alarm is ON. For example, an emergency light will be turned on when there is an alarm and a door contact is open at the same time.

**Step 5** You can create a new Condition type by tapping the ![](<.gitbook/assets/Unknown image (84)>) icon; and remove an existing Condition type by tapping the ![](<.gitbook/assets/Unknown image (85)>) icon.

**Step 6** Choose a desired Action Type from the drop-down menu. You can also apply a pre-programmed Scene under Rule function.

Up to 11 options of action types are available. The options available are dependent upon learnt device(s) in your Control Panel.

* Device Action: To toggle on/off, switch on/on for/on until/off, open, or close a device in specified zone.
* Group Control: The Group function allows the user to control the same type of devices.
* Change Mode: The system will change to the mode as specified.
* Alarm: The system will trigger an alarm sensor in specified zone.
* Apply Scene: The system will execute the preprogrammed Scene Number.
* Request Video: The PIR Video Camera or IP Camera in specified zone will record a video.
* Request Video (All): All PIR Video Cameras and IP Cameras in the system will record a video.
* Request Image: The PIR Camera in specified zone will take a picture.
* Request Image (All): All PIR Cameras in the system will take a picture.
* Request Image (No flash): The PIR Camera in specified zone will take a picture without activating its LED flash.
* Request Image (All, No flash): All PIR Cameras in the system will take a picture without activating its LED flash.

**Step 7** You can create a new Action type by tapping the **+** icon.

To remove an existing Action type, simply tap the <img src=".gitbook/assets/Unknown image (85)" alt="" data-size="line"> icon.

**Step 8** Tap “Save” to confirm scene setting. The Rule page will be updated with the new Scene.

**Step 9** You can tap the **+** icon on top right of the List menu to create a new list. To remove an

existing Rule, simply tap the icon. ![](<.gitbook/assets/image (412).png>)

![](<.gitbook/assets/Unknown image (82)>)

* Enable/Disable Rule: Toggle on/off the <img src=".gitbook/assets/Unknown image (77)" alt="" data-size="line"> icon to enable/disable the rule.
* Edit Rule: To edit an existing rule, tap the ![](<.gitbook/assets/Unknown image (86)>) icon to view rule content.

### **4.4. Cam**

The page provides access to VDP and IP Camera live streaming video.

TouchPanel-3 is compatible with Climax Video Door Phone and IP Camera. Up to 6 IP Cameras and VDPs are supported. Ensure to update device and panel firmware to the latest version for compatibility.

Ensure your Control Panel, VDP, and TouchPanel-3 are in the same Local Area Network (LAN). Moreover, both the VDP and TouchPanel-3 should be added into the same Control Panel, or the devices will not be identified.

<figure><img src=".gitbook/assets/image (441).png" alt=""><figcaption></figcaption></figure>

* Privacy mode: The icon <img src=".gitbook/assets/image (442).png" alt="" data-size="line">  indicates that the IP Cam is now in privacy mode.
* No connection: The icon <img src=".gitbook/assets/image (443).png" alt="" data-size="line">  indicates that the connection is lost between TouchPanel3 and the device.

![](<.gitbook/assets/Unknown image (87)>)

#### **4.4.1. Add New VDP / IP CAM**

**Step 1** Tap the Add icon ![](<.gitbook/assets/image (444).png>) to add a new VDP.

![](<.gitbook/assets/Unknown image (92)>)

**Step 2** Select the wireless device for WiFi setup. Follow the onscreen instructions to proceed.

#### **4.4.2. Monitoring Mode**

TouchPanel-3 provides a full screen 3-minute real-time live streaming video. Tap the device you want to check and have a full view on the screen.

![](<.gitbook/assets/Unknown image (93)>) ![](<.gitbook/assets/Unknown image (94)>)

* Listen-in / Talk: When access the monitoring view, tap the button once to turn on the speaker to listen-in. Tap the button once again to turn on the microphone to talk.
* Unlock the door: Tap the button <img src=".gitbook/assets/Unknown image (95)" alt="" data-size="line"> to unlock the door.
* Tap the button <img src=".gitbook/assets/Unknown image (96)" alt="" data-size="line"> to go back to the Cam list.
* There will be a reminder before the duration is going to end. Tap “Continue” to continue the monitoring view.

![](<.gitbook/assets/Unknown image (97)>)

#### **4.4.3. VDP Communication**

When there is an incoming call from VDP, you can answer it by controlling the buttons on the screen:

![](<.gitbook/assets/Unknown image (98)>) ![](<.gitbook/assets/Unknown image (94)>)

* Listen-in / Talk: Tap the button once to pick up the call. The speaker will be turned
* on for you to listen-in. Tap the button once again to turn on the microphone to talk.
* Unlock the door: Tap the button <img src=".gitbook/assets/Unknown image (95)" alt="" data-size="line"> to unlock the door.
* Hang up: Tap the button <img src=".gitbook/assets/Unknown image (99)" alt="" data-size="line"> to terminate the communication.
* The default duration of the communication is 3 minutes. If the communication needs to be continued, access the VDP on the Cam list to enter the monitoring view.

***

#### **4.4.4. Cam Settings**

To change settings of the IP Cam, tap the button  ![](<.gitbook/assets/image (445).png>) on each device.

![](<.gitbook/assets/Unknown image (101)>)

* **Device Name**: Name or rename your device for easy identification. Enter a desired name and tap Submit.
* **Speaker Volume**: Tap the slider to adjust the volume to a desired level.
* **Door lock binding**: Assign the VDP to the relevant door lock.
* **Wi-Fi setup**: Change the Wi-Fi setting of the device.&#x20;
* &#x20;**Delete**: Delete the item.

![](<.gitbook/assets/Unknown image (102)>)

### **4.5. Events**

The Event page records all alarm/status events, pictures and video transmitted by the Control

Panel. You can view the image or video by tapping the icon <img src=".gitbook/assets/Unknown image (103)" alt="" data-size="line">.  If AI recognizes a person /

persons in the image, an AI icon ![](<.gitbook/assets/image (446).png>) will be displayed alongside it.

![](<.gitbook/assets/Unknown image (105)>)

![](<.gitbook/assets/Unknown image (107)>)

## 5. Settings

Tap the gear icon <img src=".gitbook/assets/Unknown image (170)" alt="" data-size="line"> at the top-right corner of the screen to open the **Settings** menu. This menu provides quick access to basic features and settings that don't require an Installer or Master code.

However, the **Equipment Management** section within the Settings menu contains advanced options for the Panel and is protected by the Panel's Installer code.

The **Hotspot Sharing** and **Bluetooth Disarm** functions require a Master user or Installer to enable it.

{% hint style="warning" %}
Note:

Certain settings, including Face Detection, Equipment Management, Bluetooth Disarm, Tablet Settings, and About, can only be accessed when the Control Panel is **disarmed**.
{% endhint %}

![](<.gitbook/assets/Unknown image (155)>) ![](<.gitbook/assets/Unknown image (108)>) ![](<.gitbook/assets/Unknown image (109)>)

<table data-header-hidden><thead><tr><th width="152"></th><th></th></tr></thead><tbody><tr><td><strong>Setting</strong></td><td><strong>Description</strong></td></tr><tr><td><strong>Brightness</strong></td><td>Change the brightness of the screen by dragging the slider.</td></tr><tr><td><strong>Volume</strong></td><td>Change the volume of the user interface by dragging the slider.</td></tr><tr><td><strong>Face Detection</strong></td><td>Tap the toggle to enable or disable this function. When it is enabled, your face needs to be detected to disarm the system. Please refer to <em><strong>5.1.</strong></em><strong>****</strong><em><strong>Face Detection</strong></em>section for details.</td></tr><tr><td><strong>Display Home Screen</strong></td><td>Enable this function to display home screen when screen has been idle for 1 minute/3 minutes, or select Never to disable this function.</td></tr><tr><td><strong>Screen Saver</strong></td><td>Enable this function after the screen has been idle for 1 minute / 5 minutes, or select Never to disable this function. The Panel screen will display the images stored in the SD card.</td></tr><tr><td><strong>Screen Timeout</strong></td><td>Enable this function to turn off the screen after the specified idle period ( 15 secs / 30 secs / 1 min / 2 mins / 5 mins / 10 mins / 30 mins) Select "Never" to keep the screen always on.</td></tr><tr><td><strong>Device Bypass</strong></td><td><p>This function allows user to bypass sensors when the system is disarmed. The system panel will not respond at all when a bypassed sensor is triggered. The system can be armed directly if a device is bypassed, regardless of any device faults. However, the faults will still be monitored, logged, and displayed on the webpage.</p><ul><li>Permanently bypass will bypass selected device(s) until they are deselected. It requires** Installer Code** to access, and is allowed for Installer/Master user only.</li><li>One-time bypass provides temporary bypass function of any device until the system turns to disarm mode. It requires <strong>User PIN</strong></li></ul><p><strong>Code</strong> to access, and is allowed for Installer/Master/Slave user.</p></td></tr><tr><td><strong>Equipment Management</strong></td><td>The Equipment Management provides advanced settings for the Panel. It is protected by the Panel's installer code. Please refer to <em><strong>5.2.</strong></em><strong>****</strong><em><strong>Equipment Management</strong></em>section for details.</td></tr><tr><td><strong>Hotspot Sharing</strong></td><td>TouchPanel-3 can function as a hotspot, sharing its internet connection with nearby devices by configuring the SSID and password. Please refer to <em><strong>5.3. Hotspot Sharing</strong></em>section for details.</td></tr><tr><td><strong>Bluetooth Disarm</strong></td><td>The Bluetooth Disarming feature allows the users to disarm the system via Bluetooth simply by approaching the panel with their smartphones. Please refer to <em><strong>5.4. Bluetooth Disarm</strong></em>section for Bluetooth Setup instructions.</td></tr><tr><td><strong>Region Format</strong></td><td>Select date and time format for the user interface.</td></tr><tr><td><strong>Language</strong></td><td>Change the Panel’s language</td></tr><tr><td><strong>Setting</strong></td><td><strong>Description</strong></td></tr><tr><td><strong>Sync Logo</strong></td><td>This function allows the Panel to sync customized dealer logo with Vesta Server. Enter installer code to proceed.</td></tr><tr><td><strong>About</strong></td><td>The information about App version / Panel version, ROM version, TSP Mac, and Panel Mac will be displayed in this page. Please refer to <em><strong>5.5 About</strong></em>section for details.</td></tr></tbody></table>

### 5.1. Face Detection

When the Face Detection feature is turned on, the system must detect a face to disarm the system, adding an extra layer of protection.\*\*\*\*

* When **Disarm** is tapped, the following dialog box will be displayed, requesting the user to position his/her face in the camera frame to activate pin entering for disarming.

<figure><img src=".gitbook/assets/Unknown image (183)" alt=""><figcaption></figcaption></figure>

* The Panel will auto capture a photo when a face is detected and display the captured image for 3 seconds.
* After 3 seconds, the panel will display PIN code page with disarm icon. Enter the use PIN code to disarm the system.
* Whether disarming is completed or aborted, the captured face will be reported and displayed in the event log.

### 5.2. Equipment Management

The Equipment Management under the setting page provides advanced setting for the Panel.\*\*\*\*

Enter the default **Installer Code** **7982** to access full setting functions.

![](<.gitbook/assets/Unknown image (110)>) ![](<.gitbook/assets/Unknown image (111)>)

#### **5.2.1. Device**

The Device setting subpage includes the following functions:

Tap the respective icon for different function setting (from left to right).

![](<.gitbook/assets/Unknown image (112)>)

#### **5.2.1.1. Device Search**

* &#x20;<img src=".gitbook/assets/Unknown image (113)" alt="" data-size="line"> Users can directly search for the device they are seeking without scrolling through the entire list of devices.

![](<.gitbook/assets/Unknown image (114)>)

#### **5.2.1.2. Device Learning**

**Step 1** Tap **+** icon to enter learning mode.

![](<.gitbook/assets/Unknown image (115)>) ![](<.gitbook/assets/Unknown image (116)>)

**Step 2** Refer to accessory device manual to transmit learn signal from the device. When the panel receives learn signal, the device info will be displayed.

**Step 3** Check the box in front of device info, then tap OK to add the device into Control Panel.

![](<.gitbook/assets/Unknown image (117)>)

**Step 4** After a new device has been added / learnt / included into the Control Panel, a Device Wizard will pop up, allowing users to edit area, zone, and device name.

![](<.gitbook/assets/Unknown image (118)>)

**Step 5** Adding device is complete. Tap **OK** to close the dialog box.

![](<.gitbook/assets/Unknown image (119)>)

#### **5.2.1.3. Device Exclusion: (For removing Z-Wave device only)**&#x20;

**Step 1** Tap **–** icon to enter removing Z-Wave device mode.

![](<.gitbook/assets/Unknown image (120)>)

**Step 2**  Refer to the Z-Wave device manual to transmit signal. When the panel receives exclusion signal, the webpage will display device info.

**Step 3** Tap OK to remove the Z-Wave device.

**Step 4** Tap icon to refresh device list info. The Z-wave device is removed from the device list. ![](<.gitbook/assets/image (447).png>)

#### **5.2.1.4. Walk Test**

**Step 1** Tap icon  ![](<.gitbook/assets/image (448).png>) to enter Walk Test mode.

![](<.gitbook/assets/Unknown image (203)>)

**Step 2** Refer to device menu and press the test button to transmit a test signal for signal range test. When the signal is received, the device info and signal strength in RSSI value will be displayed. (IP Camera will send signal automatically upon entering Walk Test and does not require button press.)

![](<.gitbook/assets/Unknown image (204)>)

#### **5.2.1.5. Refresh Device List**

Tap <img src=".gitbook/assets/Unknown image (205)" alt="" data-size="line"> icon to refresh device list info.

**5.2.1.6. Delete Device**

**Step 1** To remove learnt in devices, tap ![](<.gitbook/assets/image (411).png>) icon to access delete device menu.

![](<.gitbook/assets/Unknown image (207)>)

**Step 2** Check the box at end of device column and tap **OK** to remove the selected devices from the system.

![](<.gitbook/assets/Unknown image (208)>)

#### **5.2.1.7. Edit Device**

Tap the icon ![](<.gitbook/assets/image (436).png>) at end of each device info column to enter Edit Device Page.

![](<.gitbook/assets/Unknown image (210)>)

The following is an example of VST-892’s settings and remote configuration.

<figure><img src=".gitbook/assets/Unknown image (211)" alt=""><figcaption></figcaption></figure>

![](<.gitbook/assets/Unknown image (212)>)

**Setting**

* **Area:** Assign an area for the device.
* **Zone:** Assign a zone in the selected area.
* **Name:** Enter a name for the device.
* **Permanently Bypass:** This function allows user to permanently deactivate (bypass) the selected device.
  * If bypassed, the Control Panel will not respond at all when the sensor is triggered.
  * If bypassed, the system can be armed directly regardless the device’s fault situation. However, its fault will still be monitored, logged, and displayed on the webpage.
* **24 HR**: This function enables the device to activate selected alarm event whenever it is triggered regardless of system mode. System mode response will be disabled if 24HR attribute is enabled.
* **Disarm Response / Full Arm Response / Home Arm Response:The System Mode Response setting determines system behavior under particular mode when the sensor is triggered.**
  * **No Response**: When a sensor set to “No Response” is triggered, the Control Panel will not respond.
  * **Start Entry Delay 1/ Start Entry Delay 2**
    * When the Control Panel is in the Full Arm mode, if a sensor with **Start Entry Delay 1/2** attribute is triggered, the Entry Delay 1/2 timer starts counting down. If a valid PIN code is not entered during the entry delay timer to disarm the system, the Control Panel will report a burglar perimeter alarm (**CID code:131**) immediately after entry delay timer 1/2 expires.
    * When the Control Panel is in the Home Arm mode, if a sensor with **Start Entry Delay 1/2** attribute is triggered, the Entry Delay 1/2 timer starts counting down. If a valid PIN code is not entered during the entry delay period to disarm the system, the Control Panel will report a burglar interior alarm (**CID code: 132**) immediately after entry delay timer 1/2 expires.
* **Chime**
* When a sensor set to Chime is triggered, the Control Panel will sound a Door Chime (Ding-Dong Sound).&#x20;
* **Burglar Follow**
* When the system is in Disarm / Full Arm / Home Arm mode, if a sensor set to **Burglar Follow** is triggered, the Control Panel will report a burglar alarm immediately.
* When a Start Entry sensor is triggered and the system is under Entry Delay Timer countdown, if a sensor set to **Burglar Follow** is triggered, the Control Panel will wait until the Entry Delay Timer expires before activating a burglar alarm. If the system is disarmed before the timer expires, the Control Panel will not activate the alarm.  **Burglar Instant**
* When the system is under Full arm or Home Arm / Disarm / Entry Time mode, if a sensor set to\*\* Burglar Instant\*\* is triggered, the Control Panel will report a burglar alarm immediately.
* _**Burglar Outdoor**_
  * When the system is in Full Arm or Home Arm / Disarm / Entry Time mode, if a sensor set to **Burglar Outdoor** is triggered, the Control Panel will report a burglar outdoor event immediately.
* _**Cross Zone**_
  * When two or more intrusion sensors are triggered within a specified time frame, the Control Panel will confirm the event and activate an alarm.
* _**Apply Scene**_
  * This function is only avaiable for Remote Keypad and Remote Control.
  * Select a Home Automation Scene number for a Remote Keypad or Remote Control button. When the button is pressed, the Panel will execute the actions programmed in the Scene accordingly. For more information, please see _**4.3.1. Scene**_.

**Home Automation Attributes:**

The Home Automation Attributes allows a device to control Home Automation function.  _**Trigger Response**_

* When the device is triggered, the Control Panel will activated the selected Home Automation Scene number. Please see _**4.3.1. Scene**_ webpage for details.  _**Restore Response**_
* When the device transmits a restore signal after activation, the Control Panel will activate the selected Home Automation Scene number.

**Other Attributes:**

* _**Permanent Bypass**_
  * When checked, the Panel will completely ignore all signals received from this device. A bypassed device will be unable to trigger any response, including alarm or fault from the Control Panel. All other attribute settings will be also be ignored.
* _**Exit (No Response)**_
* &#x20;If checked, the Panel will ignore the trigger signal from this sensor during Exit Time countdown. If deselected, the Panel will activated burglar alarm and report immediately when the sensor is triggered during Exit Delay Timer.
* _**24HR**_
  * A sensor set to 24HR attribute will ignore Disarm, Full Arm, Home Arm and Exit response setting. The Panel will activate the selected alarm when this sensor is triggered regardless of system mode under any time.
  * \*\*Panel AI Recognition:\*\*This function is avaible only when the Panel AI Recognition function is enabled in Panel Settings.
    * Enable this option to allow the Panel to utilize AI algorithms for processing alarm images received from this PIR Camera. The AI detection results, along with the alarm images, will be transmitted to the CMS, enabling it to prioritize the new alarm queue based on this AI detection.
    * Disable this option to prevent the Panel from using AI algorithms to process alarm images received from this specific PIR Camera.

{% hint style="warning" %}
Note:&#x20;

Some devices have their own unique functions and will have its own attribute setting which is not listed in this section. Please refer to the device manual for its setting detail.
{% endhint %}

**Remote Configuration**

***

![](<.gitbook/assets/Unknown image (215)>)

* Select to turn on / off the Pet immunity feature and set the sensitivity level (High/Low) from the dropdown menus for VST-892 PIR Cameras, then tap **Submit** to save the settings.

***

#### **5.2.2. Panel Settings**

![](<.gitbook/assets/Unknown image (216)>)

#### **5.2.2.1. Security**

![](<.gitbook/assets/Unknown image (217)>)

**All Mode**

* **Area**: Select the operation area to apply the setting.
* **Final Door**:If set to On, when the system is Away Armed and under exit timer countdown, if an opened Door Contact set to Entry attribute is closed, the system will automatically arm the system even if the exit delay timer has not expired yet.
* **Arm Fault Type**: Select how the system should respond when it is being armed under fault condition.
  * Confirm: The Panel will first display a “Mode Change Fault” message and emit 2 beeps. If you still want to arm the system, you will need to bypass the faults on the fault list first or repeat the arming action within 30 seconds to Force Arm the system.
  * Direct Confirm: The system will force arm directly without displaying fault messages and report an event.
* **Tamper Alarm**: Select whether the siren should sound when the tamper is triggered.
* Full Arm: when tamper is triggered under Full arm mode, Control Panel raises a local alarm and sends report to the monitoring center. While in Home Arm or Disarm mode, no alarm will be activated and no report will be sent.
* Always: The Control Panel raises a local alarm and send a report for tamper trigger in all modes.
* **Supervision Check**: Select to enable or disable system supervision function. When **ON** is selected, the Control Panel will monitor the accessory devices according to the supervision signal received.
* **Supervision for Fixed Device:**
  * The Control Panel monitors fixed accessory devices according to the supervision signal transmitted regularly from the device. Fixed accessory devices refer to devices such as Door Contacts, IR Motion Sensors, Smoke Detectors, etc. which are fixed in place.
  * Use this option to set the interval for receiving supervision signals. If the Control Panel does not receive the supervision signal from a fixed device within this interval, it will consider the device out of order and report the event accordingly.
* **Supervision Timer for Pendant:**
  * The Control Panel monitors the operation of portable devices such as emergency pendants, wrist transmitters, etc. according to the regular battery signals transmitted from them. If the Control Panel does not receive the battery signals from a pendant device within the set interval, it will consider the device out of order and report the event accordingly.
* **Alarm Length**: Set the duration the external siren should sound when an alarm is activated.
* **Cross Zone Timer**: Cross Zone Verification is used to setup cross verification for intrusion sensors. To use Cross Zone Verification, the following sensor and panel setting must be adjusted:
  * At least\*\* 1\*\*intrusion sensor must be set to **Cross Zone** attribute.
  * The **Cross Zone Timer** option under Panel Setting webpage must be enabled.
  * Cross Zone function does not activate under Exit and Entry Time. When a sensor set to Cross Zone attribute is triggered, the Panel begins to sound the alarm, count down Cross Zone Timer, and report a Cross Zone First Trip event (CID 693).
* **Fire Verification Timer**: Fire Verification is used to setup verification for Smoke Detector.

To use Fire Verification, the following sensor and panel setting must be adjusted:

* At least 1 Smoke Detector must be set to 24 HR – Fire with Verification attribute.
* The Fire Verification Timer option under Panel Setting webpage must be enabled.
* When a Smoke Detector set to Fire Verification attribute is triggered, the Panel begins to sound the alarm, count down Fire Verification Timer, and report a Near Alarm event (CID 118).
* **Door Chime**: this function is available only when the attribute of Door Contact **(DC)** and/or PIR detector **(IR)is set as Door Chime**.

The Control Panel sounds a Door Chime (Ding-Dong Sound) while the DC and/or IR is activated in Disarm / Full / Home / Entry mode.

* \*\*Confirm Sound:\*\*Select whether to turn off or adjust the Control Panel beeping sounds when changing Arm/Home Arm/Disarm mode.
* **Warning Beep**: Select whether the Control Panel will sound a warning beep whenever a fault condition has been detected and displayed. The warning beep will be silenced after the Fault message has been read by the user. When a new fault condition is detected, it will then again emit a warning beep every 30 seconds.
* \*\*Entry / Exit Only Final Beeps:\*\*Select when the Control Panel should start warning beep during the Entry or Exit delay. For example, if the setting is set to 5 seconds, the Control Panel will only start warning beeps during the last 5 seconds of Entry or Exit timer. When set to _Disable_, the Control Panel will sound warning beeps throughout the entire Entry or Exit countdown period.

![](<.gitbook/assets/Unknown image (218)>)

**Away**

* **Entry Delay Time 1**: Set Entry Delay Timer 1 for full arm mode. When a sensor set to Entry Delay 1 is triggered under Full Arm mode, the Control Panel will begin Entry Delay countdown according to duration set in this option.

If the Control Panel is disarmed before the Entry Delay Timer expires, the panel returns to Disarm mode and no alarm is activated. If the Control Panel is not disarmed before the Entry Delay Timer expires, the alarm will be activated and the panel will send report.

* **Entry Delay Time 2:** Set Entry Delay Timer 2 for full arm mode. When a sensor set to Entry Delay 2 is triggered under Full Arm mode, the Control Panel will begin Entry Delay countdown according to duration set in this option.

If the Control Panel is disarmed before the Entry Delay Timer expires, the Panel returns to Disarm mode and doesn’t activate an alarm. If the Control Panel is not disarmed before the timer expires, it will activate an alarm and send a report.

* **Exit Delay Time**: Set the Exit Delay Timer when entering Full Arm mode. When the user changes system mode to Full Arm, the Panel will begin Exit Delay countdown and enter Full Arm mode when the timer expires. The user must leave the areas protected by sensors before the timer expires, otherwise the sensor will trigger an alarm.
* **Entry Delay Sound**: Select whether the Control Panel sounds countdown beeps during the entry delay time in the full arm mode and set the beep volume.
* **Exit Delay Sound**: Select whether the Control Panel sounds countdown beeps during the exit delay timer in the full arm mode and set the beep volume.

![](<.gitbook/assets/Unknown image (219)>)

**Home**

* **Entry Delay Time 1**: Set Entry Delay Timer 1 for Home Arm mode. When a sensor set to Entry Delay 1 is triggered under Home Arm mode, the Control Panel will begin Entry Delay countdown according to duration set in this option.

If the Control Panel is disarmed before the Entry Delay Timer expires, the Panel returns to Disarm mode does not activate an alarm. If the Control Panel is not disarmed before the Entry Delay Timer expires, it will activate an alarm and send a report.

* **Entry Delay Time 2:** Set Entry Delay Timer 2 for Home Arm mode. When a sensor set to Entry Delay 2 is triggered under Home Arm mode, the Control Panel will begin Entry Delay Timer countdown according to duration set in this option.

If the Control Panel is disarmed before the Entry Delay Timer expires, the Panel returns to Disarm mode and does not activate an alarm. If the Control Panel is not disarmed before the Entry Delay Timer expires, it will activate an alarm and send a report.

* **Exit Delay Time**: Set the Exit Delay Timer when entering Home Arm mode. When the user changes system mode to Home Arm, the Panel will begin Exit Delay Countdown and enter Home Arm mode when the timer expires. The user must leave the areas protected by sensors before the timer expires, otherwise the sensor will trigger an alarm.\*\*\*\*
* **Entry Delay Sound**: Select whether the Control Panel sounds countdown beeps during the entry delay time in the home arm mode and set the beep volume.
* **Exit Delay Sound**: Select whether the Control Panel sounds countdown beeps during the exit delay timer in the home arm mode and set the beep volume.

#### **5.2.2.2. Panel**

![](<.gitbook/assets/Unknown image (220)>)

**Panel Settings**

* **AC Fail Report**: When an AC power failure is detected, your Control Panel will report to the Central Monitoring Station according to the duration set under AC Fail Report. If 5 minutes is set, the event will be automatically reported to the CMS after 5 minutes. Your Control Panel will then be powered by the backup battery until the fault is cleared.
* **Jamming Report**: Jamming period is specified as background RSSI level detected exceeds the threshold for a duration. The jamming period detected will be accumulated. 3 options, Disable, 1 minute, and 2 minutes, are provided. If 1 minute is set, once the total jamming period exceeds 30 seconds within 1 minute, a “Jamming” message will be reported to the Central Monitoring Station. If 2 minutes is set, once the total jamming period exceeds 60 seconds within 2 minutes, a “Jamming” message will be reported. If Diable is set, the Panel will not send a jamming report when detecting a jamming fault.
* **Auto Check-in Interval**:**Select whether the Control Panel needs to send check-in reporting to the Central Station automatically and to select the interval between check-in reports. Options available are Disable, 1 hour**,\*\* 2 hours\*\*,\*\* 3 hours… up to 4 Weeks\*\*.
* **Auto Check-in Offset Period**:\*\*\*\*Set the time delay before the first **Auto Check-In** report is made. After power is supplied or re-supplied to the Control Panel, a test report will be sent to the Central Monitoring Station (CMS) based on the Offset Period. This is used to test whether the CMS can receive the report from the Panel successfully. After this test report is sent, the Control Panel will then send reports at regular interval based on the setting of the Auto Check-in Report. For example, if **Offset** **Period** is set to 2 Hours, and **Auto Check-in Report** is set to 12 hours, the Control Panel will transmit an event code 602 to the CMS after 2 hours, and then report event 602 periodically at a regular interval of 12 hours.
* **IR Camera Resolution of Alarm Images**:\*\*\*\*Select the resolution and number of pictures taken by PIR Camera when the camera detects a movement in armed mode.
* **Outdoor IR Camera in Greysclae**:\*\*\*\*Select whether pictures from Outdoor PIR Camera should be taken in greyscale instead of color pictures. Options available are: **Disable**(Color Picture) and **Enable** (Greyscale picture)
* **Bypass Ethernet Fault**:\*\*\*\*Select whether to enable or disable Bypass Ethernet function. When **ON** is selected, the Control Panel will bypass connection fault when Ethernet cable is unplugged.
* **Panel AI Recognition:**
* Enable this function to activate the Panel's AI feature for processing alarm images to detect humans. After enabling this function in the Panel settings, the AI recognition feature must still be enabled individually for each PIR Camera. This allows the Panel to process images specifically from cameras with this feature activated. When the AI recognizes a person in the image, an AI icon will be displayed alongside the image on the Event page." Alarm images, along with the AI detection results, are transmitted to the CMS, enabling the CMS to prioritize the new alarm queue based on this AI detection.
* Disable this option to turn off the Panel's AI feature completely.

**Program RF Siren**

* \*\*Siren Tamper On:\*\*You can enable all RF Sirens tamper protection with this function. Select to turn on the sirens tamper function.
* \*\*Siren Tamper Off:\*\*You can disable all RF Sirens tamper protection with this function. Select to turn off the sirens tamper function.

{% hint style="info" %}
Note:

When turned off, siren tamper will be enabled again automatically after one hour if not turned on manually during the one-hour period.
{% endhint %}

**Panel Info**

* The Control Panel’s information, including firmware version, mac address, RF version, Z-wave version, and GSM version, will be displayed.

![](<.gitbook/assets/Unknown image (223)>)

#### **5.2.2.3. Code**

The Master Code, Installer Code, Duress Code, Guard Code, and Temporary Code add the flexibility of different security levels for operation in **Code Settings** menu.

![](<.gitbook/assets/Unknown image (224)>)

Key in your preferred 4-6 digit codes.

* **Master Code**

The default Master codes are 1111 and 2222 for all areas. <mark style="color:red;">For security reasons, please change both default master codes.</mark>

* **Installer Code**

The Installer Code is used for advanced Programming. The default Installer code is **7982**.

* **Duress Code:The Duress Code is designed for transmitting a secret & silence alarm. When Duress Code is used for accessing the system, the Control Panel will report a secret alarm message without sounding the siren to the Central Monitoring Station to indicate of a Duress Situation in Progress. The Duress Code consists is not activated as default by the factory.**
* **Guard Code:The Guard Code is designed for security patrol personnel to arm/disarm the system. It can be set the same as a User PIN Code.**
* **Temporary Code:Temporary Code is also used to arm/disarm the system, but it is for a temporary user. The temporary Code is ONLY valid for one-access per arming and disarming. Afterwards, the Temporary Code will be automatically erased and needs to be reset for a new Temporary user.**
* **Latch Option:** This is to program the Latch Key Reporting feature for Temporary Code.

![](<.gitbook/assets/Unknown image (225)>)Latch -> **Latch Report ON** = Whenever the Temporary Code is used to change system mode, the panel will report the event.

![](<.gitbook/assets/Unknown image (226)>)Latch -> **Latch Report OFF** = Whenever the Temporary Code is used to change system mode, the panel will not report the event.

**Delete**

Except Master Code and Installer Code which can’t be disabled in any way, Temporary, Duress, and Guard Codes can be disabled by cleaning the code box and leaving the box as blank.

After completing all settings, tap **Submit**to save the changes.

#### **5.2.2.4. Date and Time**

![](<.gitbook/assets/Unknown image (227)>)

* **Time Zone:** Choose your time zone, and then the system will calculate the daylight-saving time automatically (if necessary).
* \*\*Date & Time:\*\*Set current month, date, and time.
* \*\*Internet Time:\*\*the system will automatically synchronize with an internet time server. Tick the check box to enable this function. Available options: pool.ntp.gov, time.nist.gov and tick.usno.navy.mil.

Tap **Submit** to save the settings.

#### **5.2.2.5. Factory Reset**

![](<.gitbook/assets/Unknown image (228)>)

* Tick the **Keep the current network setting** box to keep the current Network settings. Otherwise, the system will reset its value back to factory default.
* Tick the **Keep the current device list**box to keep the current learnt-in devices. Otherwise, the system will reset its value back to factory default.

Tap **Submit** to save the settings.

#### **5.2.2.6. Area Name**

Users can rename the area. All related label will be updated to the renamed area name.

Tap **Submit** to save the settings (submission is not allowed if the fields are left blank).

![](<.gitbook/assets/Unknown image (229)>)

#### **5.2.3. User PIN**

The User PIN Codes are used to control system mode. Each consists of 4-6 digits (numeric number 0\~9).

User PIN code #1 for each Area is always activated factory default. <mark style="color:red;">For security reasons, please remember to change default PIN codes.</mark>

User PIN #1 in Area 1                        User PIN #1 in Area 2

Password: **1234**                           Password: **4321**

Tag Number will be displayed if the Panel has learned in any device (e.g. keypad, tag reader) that supports remote Tag configuration.

![](<.gitbook/assets/Unknown image (230)>)

**Area**

**Area**: Select the area for setting User PIN Code.

**User PIN Setting**

* **Username**: Enter a user name for easy recognition of system events. Up to 18 alphanumerical characters are allowed for each user name.
* **PIN Code**: Enter the 4-6 digit code in the field.\*\*\*\*
* **Latch:**

![](<.gitbook/assets/Unknown image (225)>)Latch -> **Latch Report ON** = Whenever the User PIN Code is used to change system mode, the panel will report the event.

![](<.gitbook/assets/Unknown image (226)>)Latch ->  **Latch Report OFF**= When the User PIN Code is used to change system mode, the panel will not report the event.

* **Tag Numer**: When the keypad / tag reader reads a new tag, pressing the **Load button** will load the tag number.

**Clear**

To clear PIN Code information, tap <img src=".gitbook/assets/Unknown image (231)" alt="" data-size="line"> on the upper right to access the clear menu. Select PIN code(s) to be removed, and tap Clear.

**User#1** in each area cannot be deleted.

![](<.gitbook/assets/Unknown image (232)>)

***

After completing all settings, tap **Submit** to save the changes.

#### **5.2.4. Cross-area User PIN**

The Cross-area User PIN page is used to program multi-area system mode control function.

![](<.gitbook/assets/Unknown image (233)>)

Use the Slider to enable/disable multi-area change mode.

When enabled, you will see the option to change mode for both areas in the system when arming/disarming the control panel.

![](<.gitbook/assets/Unknown image (234)>)

Enter the username and PIN code, then select Area 1 and/or Area 2 to determine whether this PIN code can be used to control mode for both areas simultaneously.

#### **5.2.5. Network**

The system can be connected through Ethernet, WiFi, or 4G/LTE. When all the three connection methods are available, the Panel prioritizes its connections in the following order: Ethernet > WiFi > 4G/LTE.

WiFi connection provides backup to Ethernet to extend system flexibility.

![](<.gitbook/assets/Unknown image (235)>)

#### **5.2.5.1. GSM**

![](<.gitbook/assets/Unknown image (236)>)

**GSM**

* The IMEI, IMSI, Carrier info, and RSSI value will be displayed.
* **SIM Card Detection:Select to enable or disable SIM card detection function.**

**SMS**

* **SMS Keyword:For sending remote commands to system via SMS message, a personalized password is required for the Control Panel to recognize your authority.**
* **SMS P-Word:Program Keyword is used to recognize the identity of a valid user; and to give authority for Remote Installing (through SMS Text) or Remote Upgrading purposes (through GPRS). This keyword will need to be inserted whenever the Remote Setting or Remote Upgrading is required. A maximum of 15 characters is allowed.**

**Two-way**

Speaker Volume: Adjust the speaker volume during two-way communication.

Tap “Submit” to confirm the settings.

#### **5.2.5.2. GPRS**

![](<.gitbook/assets/Unknown image (237)>)

**GPRS**

* **APN (Access Point) Name:** It is the name of an access point for [GPRS.](http://en.wikipedia.org/wiki/GPRS) Please inquire your service provider for an APN. When APN is set, the system becomes valid for internet connection.\*\*\*\*
* **Username:** It is the Log-in name to input before accessing the [GPRS](http://en.wikipedia.org/wiki/GPRS)feature. Please inquire your service provider.\*\*\*\*
* **Password:It is the User Password to input before accessing the** [**GPRS**](http://en.wikipedia.org/wiki/GPRS)**feature. Please inquire your service provider.**

#### **5.2.5.3. Wireless**

![](<.gitbook/assets/Unknown image (238)>)

**Wireless**

Select the WiFi SSID of the router for the Control Panel to connec to. Enter the WiFi network password if required, and tap “OK”.

Adding WiFi connection is NOT allowed when the Panel is connected through Ethernet.

#### **5.2.6. Report**

![](<.gitbook/assets/Unknown image (239)>)

#### **5.2.6.1. Report**

This page allows installers to configure report-related settings for reporting purposes.

![](<.gitbook/assets/Unknown image (240)>)

**Step 1** Tap **+** to add a report destination. A dialogbox will pop up for you to program the report destination.

**Step 2** Select the **Report Format**, and tap **Next** to input up information.

**Step 3** Select **Groupt number** to determine reporting sequence, and report condition. gram the report destination.

Tap “Submit” at bottom of page to confirm setting.&#x20;

**Report Format**

Tap the info icon ![](<.gitbook/assets/Unknown image (241)>) to display the Report format.

![](<.gitbook/assets/Unknown image (242)>)

* Climax CID protocol via IP

Format: ip://(Account Number)@(server ip):(port)/CID xample: ip://1234@54.183.182.247:8080/CID

* SIA DC-09 protocol via IP

Format: ip://(Account Number)@(server ip):(port)/SIA

Example: ip://1234@54.183.182.247:8080/SIA

* SIA DC-09 protocol via IP with AES encryption

Format: ip//(Account Number)@(server ip):(port)/SIA/KEY/(128,196 or 256 bits Key) Example: ip://1234@54.183.182.247:8080/SIA/KEY/ 4A46321737F890F654D632103F86B4F3

* SIA DC-09 protocol using CID event code via IP

Format: ip://(Account Number)@(server ip):(port)/CID\_SIA

Example: ip://1234@54.183.182.247:8080/CID\_SIA

* SIA DC-09 protocol using CID event code via IP, with HEX encryption.

Format: ip//(Account Number)@(server ip):(port)/CID\_SIA/KEY/(HEX) Example:

ip://1234@54.183.182.247:8080/CID\_SIA/KEY/4A46321737F890F654D632103F86B4F

3

* Manitou protocol via IP

Format: ip://(Account Number)@(server ip):(port)/MAN

Example: ip://1234@54.183.182.247:8080/MAN

* Manitou protocol via IP, with TLS encryption

Format: ip://(Account Number)@(server ip):(port)/MAN\_TLS

Example: ip://1234@54.183.182.247:8080/MAN\_TLS

* CSV protocol via IP

Format: ip//(Account Number)@(server ip):(port)/CSV

Example: ip://1234@54.183.182.247:8080/CSV

* CSV protocol via IP including username and password

Format: ip//(Account Number)@(server ip):(port)/CSV/User/Pasword

Example: ip://1234@54.183.182.247:8080/CSV/abcd/1357

* Email

Format: mailto:user@example.com

Example: mailto:john@gmail.com

**Group**

**Reporting Sequence:** Select a group for your report destination The system will make report according to the following principle:

* Group with higher priority will be reported first: Ex: Group 1  Group 2  Group 3….
* If reporting to the first destination in a group fails, the system will move on to the next report destination in the group.
* If reporting to one of the report destinations in a group is successful, the system will consider reporting to this group successful and stop reporting to rest of the destinations in the group. It will then move on to report to the next group.
* If reporting to all destinations in a group fails, the system will retry report to group according to retry times set below. If reporting is still unsuccessful after retries, the system will move on to report the the next group according to Essential/Optional setting below.
* After completing a round of reporting (From Group 1  Group 2 ….. Group5), If there is any group set as Essential which has not received report successfully, the system will restart the reporting cycle to retry reporting until every group set as Essential is reported successfully.

**Essential/Optional:**

* Essential: the system will report to all groups set as **Essential**. The system will never give up trying to report to any group set as Essential until at least one of the destinations in every Essential group successfully receives the report. Group 1 is always set as **Essential** and cannot be changed.
* Optional: The system will only report to group set as **Optional**when reporting to its previous group fails. For example: if Group 3 is set is optional, the Control Panel will only report to Group 3 if reporting to Group 2 fails.

**Retry:** If reporting to all destinations in a group fails, the system will retry reporting to the group according to the retries times set here.

**Level**

Select a reporting condition:

All events: The system will report all events to this destination.

Alarm events: The system will only report alarm event to this destination.

Status events: The system will only report status event(non-alarm events) to this destination.

**Test Button:** There is a "Test" button on the right of each report destination row. When tapped, the system will send a manual test report. A green check indicates that the report was sent successfully, and a red cross indicates the report failed.

![](<.gitbook/assets/Unknown image (243)>)

#### **5.2.6.2. Media Upload**

The system can deliver captured images and video clips captured by PIR Cameras and PIR Video Camera to cell phone, e-mail, or ftp.

![](<.gitbook/assets/Unknown image (244)>)

**Step 1** Tap **+** icon to add an upload destination. A dialogbox will pop up for you to program the upload destination.

**Step 2** Select the **Upload Method**, and tap **Next** to input up information.

Tap **Submit** to save the settings.

**Upload Method**

Tap the info icon to display the upload method.

![](<.gitbook/assets/Unknown image (245)>)

* **FTP:**[ ftp://user.password@server/path](ftp://user.password@server/path)
* **HTTP:** http://ip:port/path
* **Email**: mailto:user@server (transmitting an alarm image over Ethernet)
* **Manitou**: manitou://user@server:port&#x20;

#### **5.2.6.3. SMS**

This is used for setting SMS reporting.

![](<.gitbook/assets/Unknown image (13) (1) (1) (1)>)

**Step 1** Tap **+** to add an SMS report destination. A dialogbox will appear, allowing you to program the report destination.

**Step 2** Select the\*\* SMS Report Format\*\*, and tap **Next** to input up information.

Tap **Submit** to save the settings.

**SMS Report Format**

Tap the info icon ![](<.gitbook/assets/Unknown image (241)>) to display the SMS report format.

![](<.gitbook/assets/Unknown image (1) (1) (1) (1) (1)>)

* SMS in CID

Format: sms://ACCT@telephone

* SMS TEXT

Format: sms://ACCT@telephone/TEXT

**Level**

Select a reporting condition:

All events: The system will report all events to this destination.

Alarm events: The system will only report alarm event to this destination.

Status events: The system will only report status event (non-alarm events) to this destination.

#### **5.2.6.4. Voice**

TouchPanel-3 with microphone and speaker is able to make voice call during alarm reporting and establish two-way voice communication with call recipient. Each two-way voice session lasts 3 minutes at most.

**The panel will make voice report after the first successful alarm reporting. At least one report destination must be programmed to use voice reporting function.**

![](<.gitbook/assets/Unknown image (2) (1) (1) (1) (1)>)

TouchPanel-3 supports two types of Voice Report: GSM and VOIP. Program and select the type you would like to use for reporting.

**GSM**

* **Telephone**

The panel will make voice report to this telephone number after the first alarm report is completed.

* **Callback Timer**

The panel will enter a waiting period for call back after initial alarm report has ended.

![](<.gitbook/assets/Unknown image (3) (1) (1) (1) (1)>)

**VOIP**

![](<.gitbook/assets/Unknown image (4) (1) (1) (1) (1)>) ![](<.gitbook/assets/Unknown image (5) (1) (1) (1) (1)>)

VOIP SIP Settings

* **Callback Timer:** The panel will enter a waiting period for call back after initial alarm report has ended.
* Username: Enter your username in the VOIP server   Password: Enter the password.
* **Server Info:** Enter Domain, Port, Proxy Server, STUN Server info. Make sure to check **Enable STUN.**
* SIP: Enter the SIP number of call recipient for the Panel to dial to.

Tap **Submit** to confirm.

#### **5.2.6.5. SMTP**

Program the mail server related settings. The email account you set here would be used to send report for events or picture and video clip captured by PIR Camera and PIR Video Camera.

![](<.gitbook/assets/Unknown image (6) (1) (1) (1) (1)>)

**Step 1** Enter the following settings:

* **Server:** Set the mail server (max. 60 digits/alphabets).
* **Port**: Set the port number (max. 5 digits/alphabets).
* **Username:** Set the mail account name (max. 30 digits/alphabets).
* **Password:** Set the password corresponding to the mail account name (max. 30 digits/alphabets).
* **From:** Set the email address according to your mail server and account name. If your mail server supports other email address, you can enter the email address here. (max. 30 digits/alphabets).
* **Using TLS/SSL encrypted channels (Secure SMTP):**&#x49;f your mail server uses TLS or SSL encryption method for secure transfer, please tap the box to enable the setting

&#x20;**Step 2** Tap **Submit** to confirm the settings.

#### **5.2.7. Wired Device**

![](<.gitbook/assets/Unknown image (7) (1) (1) (1) (1)>)

There are two on-board wired zones on TouchPanel-3.

* One wired control output (open collector)
* One wired input (non powered)

![](<.gitbook/assets/Unknown image (8) (1) (1) (1) (1)>)

**Device 1 (Wired Output)**

**Type**: Select to activate the power switch from the Type dropdown menu. The default setting is “Disabled”

**Edit** ![](<.gitbook/assets/image (449).png>) Tap to assign the output power switch to a zone and area.

<figure><img src=".gitbook/assets/image (450).png" alt=""><figcaption></figcaption></figure>

**Device 2 (Wired Input)**

**Type**: Select the type of the wired sensor for each hardwired zone from the dropdown menu.

**Loop**: Select the number of loop (1 or 2) corresponding to the wiring for each device from the dropdown menu.

<figure><img src=".gitbook/assets/image (5) (1) (2).png" alt=""><figcaption></figcaption></figure>

Tap the info icon   ![](<.gitbook/assets/image (1) (1) (1) (2) (1) (1) (1).png>)to display wiring diagrams of Loop 1 & 2 for your reference.

![](<.gitbook/assets/Unknown image (13) (1) (1) (1) (1)>)

**Edit**<img src=".gitbook/assets/Unknown image (14) (1) (1) (1)" alt="" data-size="line"> :Tap to assign the wired input device to a zone and area.

After completing all settings, tap **Submit** to save the changes.

### 5.3. Hotspot Sharing

TouchPanel-3 can function as a hotspot, sharing internet connection for nearby devices by setting the SSID and Password.

This function is available whether the Panel is connected through Ethernet, WiFi, or GPRS. Only master user or installer can turn on this function and program its settings.

Enter the **Master Code** (default: 1111) or **Installer Code** **7982** to access hotspot setting.

<figure><img src=".gitbook/assets/image (2) (1) (1) (2) (1) (1).png" alt=""><figcaption></figcaption></figure>

Toggle ON/OFF the Hotspot Sharing function.

![](<.gitbook/assets/Unknown image (16) (1) (1) (1)>)

* Enter the SSID and Password, and tap Submit. (Both SSID and Password can be edited no matter what toggle status is. Toggle status won't be changed after SSID or Password is edited.)

![](<.gitbook/assets/Unknown image (17) (1)>)

***

### 5.4. Bluetooth Disarm

The Bluetooth Disarming feature allows users to disarm the system via Bluetooth by simply approaching TouchPanel-3 with their smartphones.

Up to **5 smartphones** can be paired with TouchPanel-3 for disarming the system.

Enter the **Master Code** (default: 1111) or **Installer Code** **7982** to enter Bluetooth Disarming setting.

![](<.gitbook/assets/Unknown image (18)>)

![](<.gitbook/assets/Unknown image (81)>)

**Pairing your smartphone with TouchPanel-3**

**Step 1. On your smartphone, tap on Settings** >> **Bluetooth**, and toggle the switch to turn on Bluetooth. Stay on this page.

![](<.gitbook/assets/Unknown image (19)>) ![](<.gitbook/assets/Unknown image (20)>)

**Step 2.** On TouchPanel-3, navigate to the Bluetooth Disarming settings page and tap <img src=".gitbook/assets/image (3) (1) (1) (2) (1) (1).png" alt="" data-size="line"> to enter Bluetooth pairing mode.

A Bluetooth icon ![](<.gitbook/assets/image (4) (1) (1) (2) (1) (1).png>) will appear, indicating that Bluetooth is active.

![](<.gitbook/assets/Unknown image (22)>) ![](<.gitbook/assets/Unknown image (23)>) ![](<.gitbook/assets/Unknown image (24)>)

**Step 3.** The scanned mobile device will be displayed. Select the device by tapping the radio button and then tap **Submit**.

![](<.gitbook/assets/Unknown image (25)>)

**Step 4.** The Bluetooth pairing request with a pairing code will appear on both devices. Confirm and tap **Pair** on both devices to complete the pairing.

![](<.gitbook/assets/Unknown image (26)>) ![](<.gitbook/assets/Unknown image (27)>)

**Step 5.** When pairing is successful, tap OK to proceed to **Set User PIN** page. Input the corresponding User PIN for applicable area(s), then tap Submit.

![](<.gitbook/assets/Unknown image (28)>) ![](<.gitbook/assets/Unknown image (29)>)

**Step 6.** Bluetooth pairing is complete. You can go back to **Bluetooth Disarming** setting page to verify that your smartphone is listed as a paired device.

![](<.gitbook/assets/Unknown image (30)>)

Also, go to your smartphone’s **Bluetooth** settings and verify that TouchPanel-3

(**TPxxxxxx**, where xxxxxx is the last 6 digits of the panel’s MAC address) is listed as a paired device.

![](<.gitbook/assets/Unknown image (31)>)

It is normal for TouchPanel-3 to show as "Not Connected" on your smartphone, as the system only searches for nearby Bluetooth devices when in **Away Arm Mode**.

**Disarming the System via Smartphone**

To disarm the system via a paired smartphone:

* When the system is away armed, approach TouchPanel-3 with the paired smartphone. Once TouchPanel-3 detects the paired smartphone within the BLE range, the system will automatically disarm.

_**Note:**_

* The smartphone’s Bluetooth function needs to be turned ON. The effective BLE range may differ depending on different mobile devices.
* After the system arms, **a 30-second buffer** is configured for the paired mobile to be out of TouchPanel-3 BLE range. TouchPanel-3 will start detecting only after the system is armed for 30 seconds. If the paired mobile is within the BLE range when the system arms, the system will **not** Disarm\*\* until the 30-second buffer passes.\*\*

**Edit User PIN Code for the paired Smartphone**

Go to **Bluetooth Disarming** setting page to access a list of paired devices. Tap the Edit icon ![](<.gitbook/assets/Unknown image (32)>)at the device row to enter **Set User PIN** page. Input the corresponding User PIN for applicable area(s), then tap Submit.

![](<.gitbook/assets/Unknown image (33)>) ![](<.gitbook/assets/Unknown image (34)>)

**Unpair your smartphone from TouchPanel-3**

**Step 1.** Go to **Bluetooth Disarming** setting page to access a list of paired devices. Tap the Delete icon <img src=".gitbook/assets/image (412).png" alt="" data-size="line"> at the device row. A confirm message“ Are you sure to remove this item” will pop up. Tap **Yes** to confirm.

![](<.gitbook/assets/Unknown image (37)>)

<figure><img src=".gitbook/assets/image (5) (1) (2) (1).png" alt=""><figcaption></figcaption></figure>

**Step 2.** Then, delete TouchPanel-3 from your smartphone. Navigate the Smartphone’s **Settings > Bluetooth > My Devices**. Tap the paired TouchPanel-3 and select **Forget This Device** to remove it from the device list.

### 5.5. About

The App version, Panel version, ROM version, TSP Mac, and Panel Mac information will be displayed on this page.

![](<.gitbook/assets/Unknown image (38)>)

When you tap "About," the system will automatically check for updates. If a new version is available, tap  **Install** to download and apply the update. Ensure TouchPanel-3 is connected to the internet before Installing.

![](<.gitbook/assets/Unknown image (39)>)

If the Panel is updated to the latest version, a <mark style="color:green;">**GREEN**</mark> check mark will appear next to the App version. If an update is available, a <mark style="color:red;">**RED**</mark> exclamation mark will be displayed.

![](<.gitbook/assets/Unknown image (40)>) ![](<.gitbook/assets/Unknown image (41)>)

## 6. Voice Prompts

TouchPanel-3 will play voice prompts according to different conditions. Below are two quick reference charts of all the voice prompts of TouchPanel-3 and the conditions under which they are played.

<table data-header-hidden><thead><tr><th width="55"></th><th></th><th></th></tr></thead><tbody><tr><td><strong>No.</strong></td><td><strong>Condition</strong></td><td><strong>Voice Prompt</strong></td></tr><tr><td>1</td><td>Plays when the user taps the mode switch to change modes, prompting the system to display the PIN entry page as a status reminder</td><td>Please enter your PIN.</td></tr><tr><td>2</td><td>Plays when Disarm is tapped, triggering a dialog box that asks the user to position their face in the camera frame to enable PIN entry for disarming</td><td>Position your face in the camera frame to activate pin entering for disarming.</td></tr><tr><td>3</td><td>Plays when an incorrect PIN is entered, causing the system to display a Wrong PIN Code dialog box</td><td>Wrong PIN Code</td></tr><tr><td>4</td><td>Plays when the system changes to Away mode</td><td>The mode has been changed to Away.</td></tr><tr><td>5</td><td>Plays when the system changes to Home mode</td><td>The mode has been changed to Home.</td></tr><tr><td>6</td><td>Plays when the system changes to Disarm mode</td><td>The mode has been changed to Disarm.</td></tr><tr><td>7</td><td>Plays when the system starts to countdown the entry delay</td><td>Entry delay started. [beep...]</td></tr><tr><td>8</td><td>Plays when the system starts to countdown the exit delay</td><td>Exit delay started, please leave the place. [beep...]</td></tr></tbody></table>

| **No.**            | **Condition**                                    | **Voice Prompt**      |
| ------------------ | ------------------------------------------------ | --------------------- |
| **Door Contact**   |                                                  |                       |
| 1                  | Plays when a normally-closed Door Contact opens  | Burglar - open        |
| 2                  | Plays when a normally-opened Door Contact closes | Burglar - closed      |
| **IR/IR Camera**   |                                                  |                       |
| 3                  | Plays when the IR/PIR Camera is triggered        | Burglar - trigger     |
| **Smoke Detector** |                                                  |                       |
| 4                  | Plays when the Smoke Detector detects smoke      | Burglar- detect smoke |
| **Glass Sensor**   |                                                  |                       |
| 5                  | Plays when the Glass Sensor detects shocks       | Burglar- detect shock |
