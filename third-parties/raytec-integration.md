---
icon: lightbulb-exclamation-on
---

# RAYTEC INTEGRATION

## Manual for Integrating RAYTEC Lights with VESTA Panels

<figure><img src="../.gitbook/assets/image (3) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1).png" alt=""><figcaption><p><a href="https://bydemes.com/es/marcas/raytec">RAYTEC</a></p></figcaption></figure>

This manual explains how to integrate RAYTEC lights with VESTA security panels using HTTP GET commands. These commands can be configured in scenes and automatic rules of the VESTA panels via the **SmartHomeSec** platform. Below are detailed examples for turning off, turning on, and making a RAYTEC light blink.

### **1. Initial Preparation**

Before starting the configuration, make sure you have the following information and items:

* **RAYTEC Light IP Address**: The IP address of the device (e.g., `192.168.1.63`).
* **Access Credentials**: Username (`admin`) and password (`Admin1234`) for the RAYTEC device.
* **Access to VESTA Panel**: Access the VESTA security panel through the **SmartHomeSec** user interface.

### **2. HTTP Commands to Control the RAYTEC Light**

The commands will be sent via HTTP GET from the VESTA panel to control the RAYTEC lights. Below are examples of commands for different actions:

*   **Turn off the light:**

    ```url
    urlCopiar códigohttp://admin:Admin1234@192.168.1.63/power.cgi?Power=off&LightType=WL
    ```
*   **Turn on the light for 5 seconds:**

    ```url
    urlCopiar códigohttp://admin:Admin1234@192.168.1.63/power.cgi?LightType=WL&Power=on&Level=100&Time=5
    ```
*   **Make the light blink for 5 seconds:**

    ```url
    urlCopiar códigohttp://admin:Admin1234@192.168.1.63/deter.cgi?Deter=on&Level=20&DeterFreq=fast&DeterPat=sos&Time=5
    ```

### **3. Configuring Commands on the VESTA Security Panel**

To configure these commands on the VESTA security panel, follow these steps:

#### **Step 1: Access the SmartHomeSec Platform**

1. Log in to your **SmartHomeSec** account from a web browser.
2. Select your corresponding VESTA panel.

#### **Step 2: Configure Commands in Scenes**

1. Go to the **Scenes** section.
2. Create a new scene or edit an existing one.
3. Select the option to add an **HTTP GET** action.
4. Enter the desired HTTP command in the corresponding field:
   * To turn off the light, copy the command provided in the **Turn off** section.
   * To turn on the light for a specific duration, use the command provided in the **Turn on** section.
   * To make the light blink, use the command from the **Blink** section.
5. Assign a descriptive name to the scene, such as "Turn off RAYTEC Light", "Turn on RAYTEC Light 5s", or "Blink RAYTEC Light".
6. Save the changes.

#### **Step 3: Configure Commands in Automatic Rules**

1. Go to the **Rules** section.
2. Create a new rule or edit an existing one.
3. Set the rule trigger (e.g., alarm activation, motion detection, etc.).
4. In the actions, select **Execute HTTP GET Command**.
5. Paste the corresponding HTTP command for the desired action.
6. Save the rule with an appropriate name.

#### **4. Verification and Testing**

After configuring the commands:

1. **Execute the Scenes**: From the SmartHomeSec interface, run the configured scenes to verify that the RAYTEC light responds correctly.
2. **Trigger the Rules**: Test the automatic rules by generating the events that trigger them and observe if the RAYTEC light behaves as expected.

#### **5. Troubleshooting Common Issues**

* **Authentication Error:** Ensure that the login credentials for the RAYTEC device (`admin:Admin1234`) are correct.
* **Network Connectivity:** Verify that the IP address of the RAYTEC light is correct and that both devices (VESTA panel and RAYTEC light) are on the same local network.
* **Commands Not Executed:** Ensure that the HTTP commands are correctly written and do not contain spaces or additional characters.

#### **6. Security Considerations**

* Change the default credentials of the RAYTEC light to prevent unauthorized access.
* Ensure that the local network where the devices are located is protected with a strong password and adequate encryption.

#### **7. Conclusion**

Integrating RAYTEC lights with VESTA panels using HTTP GET commands is a straightforward process that allows for automated lighting control based on the user’s needs. By following these steps, you can effectively control RAYTEC lights from the VESTA security panel.



8. **Video**&#x20;



{% embed url="https://www.youtube.com/watch?ab_channel=ByDemesEspa%C3%B1a&v=fk_DxcPl_qc" %}



