# VESTA-459

## VESTA control module for Yale Doorman lock

<figure><img src=".gitbook/assets/image (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1).png" alt=""><figcaption></figcaption></figure>

### **Specifications**

* VESTA Wireless Integration Module
* Compatible with Yale Doorman locks (V2N version and compatible)
* Communication frequency: F1 868 MHz
* Allows control of the alarm system from the lock
* Allows arming and disarming of the system by locking or unlocking the door
* Installation inside the lock
* Powered from Yale lock (no external power supply required)
* Typical communication range of 500 m in open field
* Compatible with VESTA panels and F1 receivers
* Compact and unobtrusive design



## **Integration Module for Yale Doorman Locks (DDL-C3)**

The DDL-C3 is an RF module that works with Yale Doorman L3 Lock and Yale Doorman V2N Lock. It is inserted into the Yale door lock to enable the integration of the lock with Climax F1 Gateway Panel (HSGW-MAX8).

The integration allows user to remotely monitor the door & door lock's statuses, set user codes/tags, and remotely lock/unlock the door from smartphone app or portal.

Moreover, it offers the convenience of arming and disarming the alarm system by simply locking or unlocking the door.

### _**Parts Identification**_

<figure><img src=".gitbook/assets/image (2) (1) (1) (1) (1) (1) (1) (1) (1).png" alt=""><figcaption></figcaption></figure>

### _**Installation and Learning**_

Please follow the steps below to install the DDL-C3 module into the Yale doorman lock and learn the lock into the Panel.

* **Make sure to perform these steps when the door is open.**

#### **Rest the Lock and Register a master code**

This step can be skipped if you already know your master code

<figure><img src=".gitbook/assets/image (8) (1) (1) (1).png" alt=""><figcaption></figcaption></figure>

#### **Insert DDL-C3 module & Pair with Panel**

<figure><img src=".gitbook/assets/image (1) (1) (1) (1) (1) (1) (1) (1) (1) (1).png" alt=""><figcaption></figcaption></figure>

1. Put your Control Panel into learning mode.
2. Open your door and enter **#Master Code#**, e.g. if your code is 123456, enter\*\*\*\*#123456#.
3. The Door Lock (Yale) will be displayed on the Panel webpage. Click "Add" to include the door lock into the Panel.
4. Enter **Master code** and press the Unlock button.
5. The Door Lock (Yale) will be displayed on the Panel webpage. Click "Add" to include the door lock into the Panel.

### _**Supervision**_

After installation and paring, the Door Lock will automatically send a periodic supervision signal to the Control Panel.

When the Control Panel fails to receive a supervision signal within the preprogrammed period, a fault will be indicated by the Control Panel.

### _**Low Battery**_

When the door lock is low on battery, a low battery signal will be transmitted for the system to display the low battery status and remind the user of the situation.



### _**Remote Configuration**_

**Manage User Code and Key Tag**

The user can manage user codes & key tags for all integrated Yale Doorman Locks in the system. On Home Portal Server, click **“Equipment Settings”** to access the Setting page.

Enter the **Installer Code** (default: **7982**) to access full programming fucntions. Go to **Equipment Settings** > **Doorman Code**

![](<.gitbook/assets/Unknown image (10) (1) (1) (1) (1) (1)>)

#### _**User Code**_

* User codes (**6 digits**) are used for unlocking your door locally or remotely from Portal/APP. Additionally, the user codes can be employed to arm the system locally from the lock itself.
* The Yale Doorman V2N Lock supports a maximum of **10 user codes**, while the Yale Doorman L3 Lock supports up to **30 user codes**.
* If there are L3 and V2N door locks integrated in the system, the user interface will display 30 rows for user code settings, with the first 10 rows applicable to V2N, and all 30 rows applicable to L3.
* **The default User Code 1 is 000000. For security reasons, please change the default User Code 1 immediately after the door lock is learned into the system.**

![](<.gitbook/assets/Unknown image (11) (1) (1) (1) (1) (1)>)



* **User Code:** Enter the User PIN Code (**6 digits**).
* **Name:** Enter the user name assigned to this PIN Code. Max length limit is 18 characters.**\_ \_** Each name must be unique and cannot be duplicated with any other user code name or tag user name\*\*.\*\*
* **Status:** Check to disable the PIN Code completely.

After editing, click “Submit.” A verification email will be sent to the registered user. Please enter the verification code to complete authentication.

![](<.gitbook/assets/Unknown image (12) (1) (1) (1) (1)>)

#### _**Key Tag**_

* Key Tags are used for locally unlocking your door. Additionally, the key tags can be used for arming the system locally from the lock itself.
* Key Tags can be registered with or without an optional 4 digit PIN code.
* **(For the Yale Doorman L3 Lock Only)** If the door is **locked in secure mode**, and user code is blocked for L3, the door can only be unlocked with key tag.
* The Yale Doorman V2N Lock supports a maximum of **10 key tags**, while the Yale Doorman L3 Lock supports up to **30 key tags**.
* If there are L3 and V2N door locks integrated in the system, the user interface will display 30 rows for Tag settings, with the first 10 rows applicable to V2N, and all 30 rows applicable to L3.

![](<.gitbook/assets/Unknown image (13) (1) (1) (1) (1) (1)>)

* **Tag Number:** Hold the Key Tag on the lock reader, wait for the sound signal. Click the **Load**



button on the page. The corresponding tag number will be loaded.

* **User Code:** If you want to use a 4 digit PIN code with the key tag, enter an optional PIN code. If you do not want to use a PIN code with the key tag, just leave this field blank.
* **Name:** Enter the user name assigned to this Key Tag. Max length limit is 18 characters.

Each name must be unique and cannot be duplicated with any other user code name or tag user name.

After editing, click “Submit.” A verification email will be sent to the registered user. Please enter the verification code to complete authentication.

**Individual Door Lock Setting**

### _**Door Lock Setting**_

* Go to the **Device Settings** page, click the Door Lock device row and select “**Settings**.”

![](<.gitbook/assets/Unknown image (14) (1) (1) (1) (1)>)

* **Area:** Select the area which the Door Lock belongs to\*\*.\*\*
* **Zone:** Select the Door Lock zone number.
* **Version:** DDL module’s and Doorman lock’s hardware and software versions will be displayed.
* **Bypass:** If turned on, the system will completely ignore all signals received from the door lock. After editing, click Submit to confirm.

### _**Remote Configuration**_

* Go to the **Device setting** page, click the Door Lock device row and select “**Remote Configuration**.”



![](<.gitbook/assets/Unknown image (15) (1) (1) (1) (1)>)

* **Volume:** Select volume level of the door lock: **Off, Low, and Hgh**.
* **Language:** Select language of the door lock: **English, Danish, Norwegian, and Swedish**.
* **Auto Lock:** Select to turn on/off auto-lock function. When the auto-lock function is enabled, the door will automatically lock within 2 seconds after it is closed. If the door is unlocked but not opened, it will return to the locked state within 5 seconds.

In secure locking mode, auto-lock function is disabled. Please refer to the Local Operation section below for details.

* **Block User Code: (For the Yale Doorman L3 Lock Only)** This is to block user codes in secure locking mode. When enalbed, the user cannot unlock with any user codes either locally or remotely, the lock can only be opened with key tag.

After editing, click Submit to confirm.

### _**Operation**_

**Local Operation**

1. Close the door.
2. If Auto Lock is enabled, the door will automatically lock within 2 seconds. If Auto Lock is disabled, press the lock button to lock the door.

**Arm the system when the door is locked**



1. When the door is locked, arm the system by pressing and holding the lock button for 2 seconds, and then entering user codes or presenting the tag / tag + pin code.
2. Press the lock button again. The lock should announce when it's armed.

**Unlock the door and disarm the system**

1. Present the Tag or Tag + PIN code, or enter User Code, and then press the unlock button.
2. If the system is not armed, unlock the door.

If the system is armed, unlock the door and disarms the system.

### **Secure Mode**

With Secure Mode, the door is securely locked both from inside and outside. The door can only be opened with registered user code or key tags from outside, or with the Lock’s remote control from both inside and outside.

**(For the Yale Doorman L3 Lock Only)** If user code blocking is activated, you cannot unlock with remote control or any user code. The lock can only be opened with tag. When the door is opened, secure mode is deactivated.

To lock the door in secure mode:

1. Open the door.
2. Push down the button on forend of the lock.
3. Close the door.
4. Lock the door with credentials (user code, key tag, or key tag + PIN)

### **Remote Operation**

**Check Door and Lock Status**

Go to the **Main Page - Device** page, the door and lock status will be displayed.



* Door (Open / Closed)
* Lock (Unlocked / Locked / Locked in Secure Mode)

![](<.gitbook/assets/Unknown image (17) (1) (1)>)

**Toggle Lock and Unlock the door**

1. Toggle from Lock to Unlock  and then enter User Code. Door is unlocked.
2. Toggle from Unlock ![](<.gitbook/assets/Unknown image (18) (1)>) to Lock ![](<.gitbook/assets/Unknown image (19) (1)>). Door is locked.

{% hint style="success" %}
**(In secure mode)** When the door is locked in secure mode, but blocking user codes is disabled, the lock can still be opened by remote toggling with user code. (For V2N and L3)
{% endhint %}

### **Auto Lock**

The Auto Lock function can be enabled for each individual lock. Please refer to remote configuration section for details. When the Auto Lock function is enabled, the door will automatically lock within 2 seconds after it is closed. If the door is unlocked but not opened, it will return to the locked state within 5 seconds.

In secure locking mode, auto lock is disabled. Please refer to the Local Operation section for details.

### **Operation Log**

The system will report local Door Lock operations using user credentials (User Code, Tags), including actions like locking/unlocking the door, arming/disarming the system, and fault events like Access Attempts Exceeded, Hook Bolt Change, Failed to Lock, Bad Floating ID, and Deadbolt Jammed. It will also report remote additions or deletions of door lock users (User Code, Tag). Please check the event page for details.

![](<.gitbook/assets/Unknown image (20) (1)>)

