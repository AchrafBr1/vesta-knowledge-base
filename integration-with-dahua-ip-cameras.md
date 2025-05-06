# INTEGRATION WITH DAHUA IP CAMERAS

Integration **DAHUA**:

_**If the camera has a disarm function**_

\- The Vesta panel will be able to control the arming and disarming of the IVS, therefore, functions such as lights and sound, for example, when crossing a line, will follow the arming and disarming of the panel.

\- Alarm activation and captures will function normally.

_**If the camera does not have a disarm function**_

\- In this case, control over the IVS is lost, so it will always be activated. Even if the Vesta panel is disarmed, the lights and sound will always activate, as the panel cannot control them.

\- The camera functions the same whether the panel is armed or disarmed.

_**Image capture time**_

The correct capture time is between 1 and 3 seconds. A capture time of about 5 seconds or more indicates a slowdown in the network.

A practical way to determine this time is by executing an HTTP command, where we request a photograph. This command is as follows: http://user:password@CAMERA\_IP/cgi-bin/snapshot.cgi?

Real example: http://admin:Admin1234@192.168.10.182/cgi-bin/snapshot.cgi?

_**DAHUA P2P Camera**_

With SmartHomeSec, you can add the camera to a zone using its serial number (P2P ID). This will allow the master or slave user with permission to view the live video from the app itself. Therefore, it is essential to first add the camera to the VESTA panel, and then, if video recording is required, integrate it via its IP address with a Dahua recorder. Image recording can also be done locally by inserting a micro SD card into the camera itself.

_**\<Note>**_

• The VESTA system works with photos, not videos, so the relevant settings must be made in the zone where the camera was added.

_**Time between alarms**_

For proper verification, allow 3 minutes between detections.
